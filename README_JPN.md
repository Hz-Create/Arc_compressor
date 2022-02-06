# Arc_compressor

この度はArc_compressorをダウンロードしていただき、ありがとうございます！

こちらに使い方や使用上の注意などを記載するので必ず最後までお読みください。

## ～使い方～
プログラムでは複数の.arcファイルを処理可能です。

1.対象の.arcファイルをarc_compresser(Arc_compressor.exeがある）フォルダに入れます。
2.Arc_compressor.exeを起動します。
3.ターミナルが起動し、ログが流れます。ログの見方は「ログの見方」をご参照ください。
4.Outputsフォルダに*.arc.LHが生成されます。

(3の過程で生成される*_LH.binや*_LH_LH.binは自動的に削除されます。ですが初回のみ削除に失敗しますので、手動での削除をお願いします。）

## ～ログの見方～

ログではプログラムの進行の様子が確認できます。
ログの見方はエラーなどが発生した際に参考になります。基本的な使用の際は、特に見る必要はありません。

ERRORが表示された場合プログラムがうまく動作していないので、「対処」をご参照の上、再度お試しください。

file found. --- *_LH.binが生成され、プログラムが検出したことを意味します。正常なログです。

file not found. ERROR --- *_LH.binをプログラムが検出できなかったことを意味します。エラーです。

.arc.LH file already there. it will replace. CONTINUE --- *.arc.LHファイルが既にOutputsフォルダに存在していることを意味します。ですが置き換わるので対処の必要はありません。

.arc.LH file already there. Also replace failed. ERROR --- *.arc.LHファイルが既にOutputsフォルダに存在していることを意味します。また置き換えに失敗しています。エラーです。

rename and save success --- *_LH.binファイルを*.arc.LHファイルに変更し、保存したことを意味します。正常なログです。

rename and save failed. ERROR --- *_LH.binファイルを*.arc.LHファイルに変更または保存に失敗したことを意味します。エラーです。

Unnecessary files deleted --- 不要な*_LH.binや*_LH_LH.binが削除されたことを意味します。正常なログです。

Unnecessary files delete failed. ERROR --- 不要な*_LH.binや*_LH_LH.binの削除が失敗したことを意味します。エラーです。

successfully -- すべての処理が完了したことを意味します。

pless enter key --- エンターキーを押してプログラムを終了されてください。

## ～対処～

エラーが発生した場合はこちらを参考にして対処してください。対処しても直らなかった場合はお問い合わせください。

file not found. ERROR:

compress.batとntcompress.exeがフォルダ内にあることを確認してください。


.arc.LH file already there. Also replace failed. ERROR:

Outputsフォルダ内を空にしてください。


rename and save failed. ERROR:

Outputsフォルダ内を空にしてください。


Unnecessary files delete failed.:

不要な*_LH.binや*_LH_LH.binを手動で削除してください。頻発する場合はお問い合わせください。


すべてのエラーに共通する対処法:

プログラムを再インストールしてください。

## ～その他～

このプログラムを作者・代理人に無断で配布しないでください。
配布したい場合はお問い合わせください。

プログラムの修正点・改善点などありましたら、ご連絡ください。

その他不明な点等ございましたら、ご連絡ください。

プログラム名: Arc_compressor

作者: Hz

連絡先:スターかる@star_karu_SKC (代理人）
作者に伝わります。

copyright© 2022 Hz