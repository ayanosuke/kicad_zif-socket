# kicad_zif-socket
Kicad用zif（ゼロプレッシャー）ICソケットのパーツ・フットプリント・３Dモデルデータです。
300milのみ。
データについては無保証です。
ご使用される場合は、十分に確認をお願いします。

寸法図は3Mの
http://www.mmm.co.jp/electrical/textool/dip/pdf/f05.pdf
を参考にして作りました。


3Dモデルはdesignspark mechanicalを使用して、作成。rsdocファイルをうpしました。

ちなみに、どうやってkicad用のデータを作ったかと言いますと
１、designspark mechanicalでモデリング
２、stl形式でエクスポート
３、Wings3Dで、色付け
４、Wrl形式でエクスポート
５、kicadに取り込み各設定を行う。


回路図用部品データ
zif_socket.dcm
zif_socket.lib

*.mod
フットプリントデータ

*.wrl
３Dモデルデータ
