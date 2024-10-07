# ls (list segments)
* ls -オプション　パス
**オプション** | **用途**<br>
| -a | 不可視ファイルも表示<br>
| -l | タイプや権限、所有者や所有グループなどの詳細情報を表示

# ls /
* / ルートディレクトリでディレクトリ構造が表示される

# pwd (Print Working Directory)
* 現在自分が位置しているディレクトリ＝ワーキングディレクトリがどこか出力してくれます

# cd (Change Directory)
* cd パス
**指定** | **移動先**<br>
| ~ | ホームディレクトリ<br>
| / | ルートディレクトリ<br>
| - | 移動前に位置していたディレクトリ<br>
| . | ワーキングディレクトリ<br>
| .. | ワーキングディレクトリの一階層上のディレクトリ<br>
| ../../ | ワーキングディレクトリの二階層上のディレクトリ<br>

# mkdir (Make Directory)
* mkdir ディレクトリ名<br>
**オプション** | **用途**<br>
| -p | 親ディレクトリも作成する

# touch
* touch ファイル名
* touchはファイル作成するコマンドです

# &&
* &&はAND演算子です

# cp (Copy)
* cp コピー元 コピー先
**オプション** | **用途***<br>
| -r | ディレクトリの複製をする<br>

# mv (Move)
* mv 変更元 変更先
* mvはファイルやディレクトリの移動するコマンド
* また、元のファイル名と違うファイル名を指定することで、移動と同時にファイル名の変更も可能

# rm (ReMove)
* rm 削除するファイルorディレクトリ
**オプション** | **用途**<br>
| -r | ディレクトリの削除をする

# ＊ (ワイルドカード)

# > or >>
## >
* \ >は左辺の実行結果の出力を右辺で指定したファイルに書き込む記号です
* 例) echo 'Hello World' > README.md
      cat README.md
* ※ 存在するファイル名を指定した場合は、中身を上書きしてしまうので注意
## >>
* \ >>は左辺の実行出力結果を右辺で指定したファイルの末尾に書き込む記号です
* 例) echo 'Linux Practice' >> README.md
      echo '--------------' >> README.md
      cat README.md

# cat (CATnate)
* catは指定したファイルの内容をターミナル上に出力するコマンド

# vim
* vim or vi ファイル名
* 上記コマンドでvimエディタを起動しファイルの編集・保存を行うことができる

