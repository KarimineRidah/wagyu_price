# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリは、チームや他のデバイスと共有するための共同作業の場。
ローカルリポジトリは、個人のパソコンにあるソロ活動（個人作業）のリポジトリ。

## プッシュとマージの違いは何でしょうか？

プッシュというのは、<ins>リモートリポジトリ（今回であればGitHub）に編集、変更内容をアップロードすること。</ins>
マージは、<ins>別々のブランチ（作業）をメインのブランチに統合すること。</ins>

## コミットとプッシュの違い。

コミットは、ローカルのリポジトリに変更を保存すること。自分だけにしか見えない。

プッシュとは、コミットしたローカルリポジトリの内容を、リモートリポジトリに移す操作のこと。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

何をどのようにしたのかが分かるようにするのが最適。長すぎたり、具体的に何を編集したのかがわからないメッセージはNG。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルマージは、個人のローカルな環境でブランチを統合できるので、単純作業とか個人のプロジェクトがあるときは向いている。

プルリクエストでマージをすると、リモートリポジトリでメンターさんなどからレビューを受けたりできるので、共同開発で向いている。。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

まずはコンフリクトがどこで起こっているのかを見つける。
↓
コンフリクト箇所を手動で治す
↓
git addでファイルをステージングして、もう一度コミットする。
あるいはプッシュする。
