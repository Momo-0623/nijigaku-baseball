Safari / GitHub Pages 公開用

構成
- index.html : 運営画面（URLのトップ）
- ranking.html : ランキング画面
- assets/baseball.png : 透過野球ボール
- assets/team-placeholder.png : 仮チームロゴ

GitHub Pages
1. 新しいリポジトリを作成
2. ZIPを解凍
3. index.html / ranking.html / assets フォルダをリポジトリ直下へアップロード
4. Settings → Pages
5. Build and deployment の Source を Deploy from a branch
6. Branch を main、フォルダを /(root) にして Save
7. 表示されたURLをSafariで開く

注意
現在の得点・生徒・チーム・挑戦履歴は localStorage 保存です。
そのためSafariで操作できますが、端末やブラウザをまたいだ同期はまだありません。
ranking.html を他の参加者が同じ得点で見る公開ランキングにするには、次工程でオンラインDB同期が必要です。
