# GitLabに登録する
GitLabに登録しなければ、forkをすることはできません。   
これに限っては検索などでやり方を確認して下さい。    

# forkする
1. [このrepoのトップページを開く](https://gitlab.com/AnKoushinist/nuclear-missiles-by-krsw)
2. このボタンを押す(`Fork`ボタン) ![画像](/uploads/706ffda577df755bdebbeed56210b1bc/pds6L6H_-_Imgur.jpg)
3. fork完了。貴職のアカウントにこのrepoの複製ができるはずです

# 設定をする
## `Job Timeout`を2日にする
1. `Settings`にカーソルを合わせ、`CI/CD`をクリック
2. 一番右上の`Expand`をクリック
3. 下にスクロールして、`Timeout`の値を`2d`に変更する
4. `Auto-cancel redundant, pending pipelines`を外しておく (任意)
5. `Save Changes`をクリック
6. 完了。最大実行時間は2日となりました。