---
title: "XslFoLoadOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF ドキュメントへの XSL-FO ファイルの読み込み/インポート オプションを表します。"
type: docs
weight: 1820
url: /ja/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

PDF ドキュメントへの XSL-FO ファイルの読み込み/インポート オプションを表します。

XslFoLoadOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| XslFoLoadOptions() | XSL データなしで [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) オブジェクトを作成します。 |
| XslFoLoadOptions(xsl_file) | XslFoLoadOptions クラスの新しいインスタンスを初期化します |
| XslFoLoadOptions(xsl_stream) | XslFoLoadOptions クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバック。<br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。<br/>            Continue はデフォルトのアクションで、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止すべきです。 |
| load_format | ファイル形式を表します。この形式は[LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)で記述されています。 |
| xsl_stream | XML を PDF ドキュメントに変換するための xsl データを取得します。 |
| base_path | ロードされた SVG ファイルで参照されている外部リソース（存在する場合）への相対パスが検索されるベースパス/URLです。 |
| parsing_errors_handling_type | ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この enum は、そのエラーの処理に対する可能な戦略を列挙します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

