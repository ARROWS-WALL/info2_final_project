# PortPholio

## このサイトの目的
・画像認識を使って、顔認証システムを作る　←　特定の顔が表示された時、特定のウェブサイトへと飛ばされる

### 仕様
<p>・始まりのページは簡素にする</P>
<p>・ページ上にあるのはボタンとカメラから取得した動画情報を表示するための枠、それと「ログイン画面」と書かれたページのタイトル</p>
<p>・ボタンは一つだけ設置。ボタンの役割はカメラ起動。押したときに前に映っている人物を認識し、ライブラリ上に登録されている顔であれば特定のウェブページに移動する仕掛けにする</p>
<p>・登録された顔以外の人がカメラに映った場合、「ログイン拒否」という文字が表示されるか、またはログインが拒否された時専用のページを作り、そこに飛ばすようにする</p>

### 使用する要素
<p>・getElementByIDを利用し、カメラが起動すると同時にタイトルの文字が「ユーザーをサーチ中・・・」と変わるようにする</p>
<p>・センサー情報とライブラリを使用する。場合によってはマッシュアップも使う。</p>
