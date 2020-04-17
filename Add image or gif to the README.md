## Add image to the Readme.md
https://www.youtube.com/watch?v=nvPOUdz5PL4

- go to "issues"
- press "new issue" button on the right
- drag a file to here
- copy the shown code and paste it to the README file.

## Add gif to the Readme.md
GithubのReadmeに荒くないgifを作成から貼り付けまで(https://qiita.com/kosuke0820/items/ebeb0c59b603c7224eac)

cd 動画のあるディレクトリ
- ffmpeg -i screen_recording.mov -an -r 10 %04d.png  // 10frames/secでpng作成
- convert *.png -resize 40% output_%04d.png  // 作成したpngを40%にリサイズ
- convert output_*.png screen_recording.gif  //  gifに変換

* 動画サイズが大きい場合(over 10MB)
２コマンド目
- convert *.png -resize 20% output_%04d.png
- convert output_*.png kekka.gif
