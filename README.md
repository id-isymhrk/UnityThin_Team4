# UnityThon_Team4
## 簡単な流れ
1. [Issues]→[new issue] で新しくissueを作成する
1. [Feature]と[Bug]の項目があるのでそのテンプレートを活用してください
1. 作業に移る時は`git pull origin main`で最新版にしてからの方がマージ時に考えることが減るのでお勧めです
1. 最新版にしたら"ブランチの作り方"を参考にしてブランチを作成し、そのブランチ内で作業を進めてください。
1. 作業の区切りごとに`git add 変更したファイル名` `git commit -m "わかりやすい名前"`のように一連の流れを行うことで何かミスがあっても復元し易くなります
2. 作業が終了したら（issueの内容を達成したら）`git push origin 自分のブランチ名` 
3. githubのページ（本ページ）の[PullRequest]のタブに新しく緑色で[Compare&PullRequest]とあると思うのでそれをクリック
4. プルリクエストの詳細を書いて他の人に確認してからメインブランチにくっつけましょう
5. 作業が終わったら、また一番上から始めます


## ブランチの作り方
`git checkout -b feature/#issue番号/わかる名前` または `git branch feature/#issue番号/わかる名前`

※issueを作った時にできる"#01"のような番号を「issue番号」と呼称しています。

ブランチは作業ごとに新しく作成してもらえると助かります

## pushの時の注意点
`git push origin 自分のいるブランチの名前` 

↑mainにpushしないように注意してください
