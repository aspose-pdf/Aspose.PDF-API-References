---
title: "EpubLoadOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "EPUB ファイルを PDF ドキュメントにロード/インポートするためのオプションを含みます。"
type: docs
weight: 310
url: /ja/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

EPUB ファイルを PDF ドキュメントにロード/インポートするためのオプションを含みます。

EpubLoadOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| EpubLoadOptions() | EPUB ファイルを PDF ドキュメントに変換するためのデフォルトのロードオプションを作成します。<br/>            デフォルトの PDF ページサイズ - A4 300dpi 2480 X 3508。 |
| EpubLoadOptions(page_size) | EpubLoadOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバック。<br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。<br/>            Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| load_format | ファイル形式を表します。この形式は[LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)で記述されています。 |
| page_size | インポート時の出力ページサイズを取得または設定します。 |
| margin | 余白情報を表すオブジェクトへの参照を取得します。 |
| margins_area_usage_mode | 余白領域の使用モードを表します。インポートされたドキュメントのCSS指示（存在する場合）の処理を<br/>              余白の使用に関連して定義します。 |
| page_size_adjustment_mode | 注意！ この機能は実装されていますが、サンプルドキュメントでOSHARED層にブロッカー問題が判明したため、まだパブリックAPIに公開されていません。<br/>              OSHARED層で問題が明らかになったサンプルドキュメント。<br/>              <br/>             <br/>              変換時のページサイズ使用モードを表します。<br/>             HTML、EPUB などのフォーマットは通常フロート設計であるため、必要なページサイズに合わせることができます。しかし、コンテンツが水平位置やサイズを指定している場合、必要なページサイズに収めることができません。<br/>               そのような場合、コンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わないときに何をすべきかを定義できます。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

