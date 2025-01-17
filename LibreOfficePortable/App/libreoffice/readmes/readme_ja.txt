
======================================================================
LibreOffice 6.0 ReadMe
======================================================================


この readme ファイルの最新版については、http://www.libreoffice.org/welcome/readme.htmlをご覧ください。

このファイルはソフトウェア LibreOffice についての重要な情報を含んでいます。インストールを始める前に十分注意してこれを読むことをお勧めします。

LibreOffice コミュニティはこの製品の開発に対して責任を負い、あなたにコミュニティメンバーとして参加することを考えていただくようご案内します。あなたが新しい利用者なら、LibreOffice のサイトを訪れることができます。そこで LibreOffice プロジェクトやその周りに存在するコミュニティについての多くの情報を見つかります。http://www.libreoffice.org/ へどうぞ。

LibreOffice は本当にどの利用者に対してもフリーですか?
----------------------------------------------------------------------

LibreOffice は誰でも自由に利用できます。LibreOffice のコピーを用意して、それを好きなだけたくさんのコンピューターにインストールし、そしてそれを(商用や政府向け、行政向け、教育での利用などを含む)好きな目的で使ってかまいません。さらなる詳細についてはこの LibreOffice ダウンロードに同梱されているライセンスの文面を見てください。

なぜ LibreOffice はどの利用者に対してもフリーなのですか？
----------------------------------------------------------------------

あなたは LibreOffice のこのコピーを無償で利用することができます。なぜなら、個人の貢献者や企業スポンサーが設計し、開発し、検証し、翻訳し、文書化し、サポートし、マーケティングをし、その他の多くの方法で助けることによって、LibreOffice は今日あるような形 - 世界で最も優れた家庭およびオフィス向けのオープンソースプロダクティビティソフトウェアになっているからです。

彼らの努力に感謝し、LibreOffice が将来にわたって利用し続けられることを確かなものにしたいとお考えなら、プロジェクトに貢献することを検討してみてください - 詳しくは http://www.documentfoundation.org/contribution/ をご覧ください。誰でも何らかの形で貢献できます。

----------------------------------------------------------------------
インストールに関する注記
----------------------------------------------------------------------

LibreOffice のすべての機能を使うにはJava 実行環境 (JRE) の最近のバージョンが必要です。JREは LibreOffice には含まれていないので、別途インストールする必要があります。

システム要件
----------------------------------------------------------------------

* Microsoft Windows 7, 8.x, または 10

注: インストールを実行するには、管理者権限が必要です。

Microsoft Office 形式のデフォルトアプリケーションとして LibreOffice を登録するか否かは、次のようにコマンドラインでインストーラーのオプションを使用して指定できます。

* REGISTER_ALL_MSO_TYPES=1 を指定すると、強制的に LibreOffice をMicrosoft Officeフォーマットの既定アプリケーションとして登録します。
* REGISTER_NO_MSO_TYPES=1 を指定すると、 LibreOffice をMicrosoft Office フォーマットの既定アプリケーションとして登録しません。

システムの一時ディレクトリに十分なメモリーがあることを確認してください、そして読み込み、書き込み、および実行権限があることを確認してください。インストール処理を開始する前に他の全てのプログラムを閉じてください。

LibreOffice を Debian/Ubuntu ベースのLinuxシステムにインストールする方法
----------------------------------------------------------------------

言語パックを（英語版の LibreOffice のインストール後に）インストールする場合は、次の「言語パックのインストール」セクションを参考にしてください。

ダウンロードされたアーカイブを展開する際、1つのサブディレクトリにその内容が展開されます。ファイルマネージャーのウィンドウを開き、"LibreOffice_" で始まりバージョン番号とプラットフォームの情報が続くディレクトリに現在のディレクトリを変更してください。

このディレクトリは"DEBS"と呼ばれるサブディレクトリを含みます。"DEBS"ディレクトリへ現在のディレクトリを変更してください。

そのディレクトリで右クリックをし、"ターミナルを開く"を選択してください。ターミナルウィンドウが開きます。ターミナルウィンドウのコマンドラインから、以下のコマンドを入力してください(コマンドが実行される前に root ユーザーのパスワードを入力するよう促されます):

次のコマンドを実行すると、LibreOfficeとデスクトップ統合パッケージをインストールします。（コマンドは入力するのではなく、端末画面にコピー＆ペーストするといいでしょう）:

sudo dpkg -i *.deb

これでインストールのプロセスが完了しました、デスクトップのアプリケーション/オフィスのメニューに全ての LibreOffice アプリケーションのアイコンがあるはずです。

LibreOffice を Fedora, openSUSE, Mandriva や他のRPMを採用したLinuxシステムにインストールする方法
----------------------------------------------------------------------

言語パックを（英語版の LibreOffice のインストール後に）インストールする場合は、次の「言語パックのインストール」セクションを参考にしてください。

ダウンロードされたアーカイブを展開する際、1つのサブディレクトリにその内容が展開されます。ファイルマネージャーのウィンドウを開き、"LibreOffice_" で始まりバージョン番号とプラットフォームの情報が続くディレクトリに現在のディレクトリを変更してください。

このディレクトリは"RPMS"と呼ばれるサブディレクトリを含みます。"RPMS"ディレクトリへ現在のディレクトリを変更してください。

そのディレクトリで右クリックをし、"ターミナルを開く"を選択してください。ターミナルウィンドウが開きます。ターミナルウィンドウのコマンドラインから、以下のコマンドを入力してください(コマンドが実行される前に root ユーザーのパスワードを入力するよう促されます):

Fedora ベースのシステム向け: su -c 'yum install *.rpm'

Mandrivaベースのシステム向け: sudo urpmi *.rpm

他のRPMを使用するシステム(openSUSE等)向け: rpm -Uvh *.rpm

これでインストールのプロセスが完了しました、デスクトップのアプリケーション/オフィスのメニューに全ての LibreOffice アプリケーションのアイコンがあるはずです。

代わりに、このアーカイブを伸張したフォルダーの直下にある「インストール」スクリプトを使用し、ユーザー権限でインストールすることもできます。このスクリプトは通常の LibreOffice  プロファイルとは別の LibreOffice  独自のプロファイルを作成します。注意として、この方法ではデスクトップメニューアイテムとデスクトップMIMEタイプ登録といったシステム統合部分はインストールされません。

ここまでのインストールガイドでカバーされなかった、Linuxディストリビューションのデスクトップ統合環境に関しての注意
----------------------------------------------------------------------

これらのインストールの説明で明示的に扱っていない他の Linux ディストリビューションで LibreOffice をインストールするのは簡単にできるはずです。違いが見つかる主な面はデスクトップインテグレーションです。

RPM (やDEBSなど) のディレクトリには libreoffice6.0-freedesktop-menus-6.0.0.1-1.noarch.rpm (あるいは libreoffice6.0-debian-menus_6.0.0.1-1_all.debなど) というパッケージもあります。これは Freedesktop.org specifications/recommendations (http://en.wikipedia.org/wiki/Freedesktop.org)に対応している全ての Linux ディストリビューションのためのパッケージで、上で述べた説明で扱っていない他の Linux ディストリビューションでのインストールのために提供されています。

言語パックのインストール
----------------------------------------------------------------------

お望みの言語およびプラットフォームの言語パックをダウンロードしてください。それらは主要なインストールアーカイブとして同じ場所から取得できます。Nautilus ファイルマネージャーから、ダウンロードしたアーカイブを1つのディレクトリ(例えば、デスクトップ)に展開してください。LibreOffice のアプリケーション(もし開始していれば、クイックスターターも含め)すべてを終了していることを確認してください。

現在のディレクトリをダウンロードした言語パックを展開したディレクトリに変更してください。

ここで現在のディレクトリを展開の処理の間に作成されたディレクトリに変更してください。例えば、32bit の Debian/Ubuntu ベースのシステム向けのフランス語の言語パックでは、そのディレクトリは LibreOffice_ に続けてバージョン情報、続けて Linux_x86_langpack-deb_fr という名前になっています。

ここで現在のディレクトリをインストールするパッケージを含むディレクトリに変更してください。Debian/Ubuntu ベースのシステムでは、このディレクトリは DEBS です。Fedora や openSUSE、Mandriva システムでは、RPMS です。

Nautilus ファイルマネージャーから、そのディレクトリで右クリックしてコマンド"ターミナルを開く"を選択してください。そこで開いたターミナルウィンドウで、言語パックをインストールするコマンドを実行してください(以下の全てのコマンドについて、root ユーザーのパスワードを入力するよう促されることがあります):

Debian/Ubuntu ベースのシステム向け: sudo dpkg -i *.deb

Fedora ベースのシステム向け: su -c 'yum install *.rpm'

Mandrivaベースのシステム向け: sudo urpmi *.rpm

他のRPMを使用するシステム(openSUSE等)向け: rpm -Uvh *.rpm

ここでLibreOfficeのアプリケーションの1つ - 例えば Writer を開始します。ツールメニューに行きオプションを選択してください。オプションのダイアログボックスで、"言語設定"をクリックしそして"言語"をクリックしてください。"ユーザーインタフェース"リストをドロップダウンし、インストールした言語を選択してください。お望みなら、同じことを"ロケール設定"や"既定の通貨"、"文書のための既定の言語"でも行ってください。

これらの設定を調整した後、OK をクリックしてください。ダイアログボックスが閉じて、LibreOffice を終了して再度起動した(もし起動していれば、クイックスターターも終了することを忘れないでください)ときに初めて変更が有効になるということを知らせる情報メッセージが出てくるでしょう。

次回にLibreOfficeを起動させると、インストールした言語で開始されます。

----------------------------------------------------------------------
プログラム起動時の問題
----------------------------------------------------------------------

LibreOffice 起動時の問題 (たとえばアプリケーションがハングする) や、画面表示の問題の多くは、グラフィックスカードドライバーが原因です。このような問題が発生した場合は、グラフィックスカードドライバーを更新するか、OS 付属のグラフィックスドライバーを使用してみてください。3D オブジェクト表示の問題は、「ツール」→「オプション」→「LibreOffice」→「表示」→「3D 表示」の下にある「OpenGL の使用」オプションをオフにすると解決されることがあります。

----------------------------------------------------------------------
Windows上でのALPS/Synaptics製のノートブックPCタッチパッド
----------------------------------------------------------------------

Windows ドライバーに問題があるため、ALPS/Synaptics 製のタッチパッド上で指を動かしても LibreOffice のドキュメントをスクロールすることはできません。

タッチパッドでスクロールできるようにするには、下記の行を C:\Program Files\Synaptics\SynTP\SynTPEnh.ini 設定ファイルに追加して、コンピューターを再起動してください。

[LibreOffice]

FC = "SALFRAME"

SF = 0x10000000

SF |= 0x00004000

注意事項: この設定ファイルの場所は、Windows のバージョンによって異なる場合があります。

----------------------------------------------------------------------
ショートカットキー
----------------------------------------------------------------------

LibreOffice で使用できるショートカットキー (キーの組み合わせ) は、オペレーティングシステムで使用されていないものだけです。LibreOffice のショートカットキーが LibreOffice ヘルプの記述どおりに動作しない場合は、そのショートカットキーがすでにオペレーティングシステムで使用されているかどうかを確認してください。このような競合を解決するには、オペレーティングシステムによって割り当てられているキーを変更してください。または、LibreOffice 側でキーの割り当てを変更します (ほとんどのキー割り当ては変更が可能です)。詳細については、LibreOffice のヘルプまたはオペレーティングシステムのヘルプを参照してください。

----------------------------------------------------------------------
LibreOffice からドキュメントを E-mail として送信するときの問題
----------------------------------------------------------------------

「ファイル」→「送る」→「ドキュメントを E-mail として送信」または「PDF 添付としてのドキュメント」を使用してドキュメントを送信するときに、プログラムがクラッシュまたはハングアップすることがあります。これは、Windows システムファイル「Mapi」(Messaging Application Programming Interface) が一部のファイルバージョンで問題を引き起こすことが原因です。どのバージョン番号で問題が発生するかは特定できていません。詳細については、http://www.microsoft.com/japan で「mapi dll」のサポート技術情報を検索してください。

----------------------------------------------------------------------
重要な利用を手助けするためのノート
----------------------------------------------------------------------

LibreOffice でのアクセシビリティの機能についてのさらなる情報は、http://www.libreoffice.org/accessibility/ をご覧ください

----------------------------------------------------------------------
ユーザーサポート
----------------------------------------------------------------------

LibreOfficeのヘルプが欲しい場合、 http://www.libreoffice.org/support/ がサポートページなので、こちらをご覧ください。 すでに答えられているかもしれない質問は、 http://www.documentfoundation.org/nabble/ のコミュニティフォーラムをチェックしてください。あるいは、 http://www.libreoffice.org/lists/users/にある'users@libreoffice.org' のメーリングリストを検索してみてください。あるいは、質問したい場合は users@libreoffice.org に送ってください。このリストを購読したい場合は、空メールを users+subscribe@libreoffice.orgに送ってください。日本語では、 http://ja.libreofficeforum.org/ にフォーラムが、 http://wiki.documentfoundation.org/Local_Mailing_Lists#Japanese にメーリングリストがあります。

また http://www.libreoffice.org/faq/ にある FAQ の節も確認してください。

----------------------------------------------------------------------
バグと問題の報告
----------------------------------------------------------------------

バグを報告し追跡し、解決するためのシステムは現在 BugZilla であり、https://bugs.libreoffice.org/ でホストされています。全てのユーザーに対し個別のプラットフォームで生じるバグを報告する資格があり歓迎されているとお考えください。バグの精力的な報告は、ユーザーコミュニティが LibreOffice で進行中の開発や改善に対してできる最も重要な貢献のひとつです。

----------------------------------------------------------------------
コミュニティへの参加
----------------------------------------------------------------------

LibreOffice コミュニティでは、この重要なオープンソースプロジェクトの発展への積極的な参加をお待ちしています。

利用者として、あなたは既にこのスイートの開発プロセスの価値のある一部分であり、コミュニティにとって長期に渡る貢献者となるように、一層のアクティブな役割を果たすことを勧めます。ぜひ参加して、 http://www.libreoffice.org/contribution/にある貢献のページを調べてみてください。

始め方
----------------------------------------------------------------------

貢献を始めるために最善の方法は、1つまたはそれ以上のメーリングリストを購読し、しばらく様子を見て、徐々にメールのアーカイブを使って2000年10月まで遡るLibreOfficeのソースコードがリリースされて以来出てきているたくさんの話題に親しむことです。良い状態になれば、あとは自己紹介のメールを送って飛び込むだけです。オープンソースプロジェクトに慣れているなら、http://www.libreoffice.org/develop/で私たちの To-Do リストを調べて手伝いたいと思うものがないか見てください。

購読
----------------------------------------------------------------------

購読できるメーリングリストが次の場所にあります: http://www.libreoffice.org/contribution/

* お知らせ: announce@documentfoundation.org *すべてのユーザーに推奨* (小流量)
* メインのユーザー向けリスト: users@global.libreoffice.org *議論を簡単に見守ることができます* (多流量)
* マーケティングプロジェクト: marketing@global.libreoffice.org *開発を越えて* (流量が増えつつあります)
* 一般的な開発者向けリスト: libreoffice@lists.freedesktop.org (多流量)

一つ以上のプロジェクトに参加
----------------------------------------------------------------------

ソフトウェアの設計やコーディングの経験が少なくても、この重要なオープンソースプロジェクトに貢献する方法はあります。

新しい LibreOffice 6.0 をどうぞお楽しみください。そして、オンラインコミュニティに参加していただけることを願っています。

LibreOffice コミュニティ

----------------------------------------------------------------------
使用された / 修正されたソースコード
----------------------------------------------------------------------

Portions Copyright 1998, 1999 James Clark. Portions Copyright 1996, 1998 Netscape Communications Corporation.
