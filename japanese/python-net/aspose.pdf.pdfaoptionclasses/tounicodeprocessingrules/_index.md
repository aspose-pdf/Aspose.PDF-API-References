---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "このクラスは、Adobe Preflight エラー <br/>            「Text cannot be mapped to Unicode」を解決するために使用できるルールを記述します。"
type: docs
weight: 20
url: /ja/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

このクラスは、Adobe Preflight エラー <br/>            「Text cannot be mapped to Unicode」を解決するために使用できるルールを記述します。

ToUnicodeProcessingRules 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| ToUnicodeProcessingRules() | コンストラクタ |
| ToUnicodeProcessingRules(remove_spaces) | ToUnicodeProcessingRules クラスの新しいインスタンスを初期化します |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | ToUnicodeProcessingRules クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| remove_spaces_from_c_map_names | 一部のフォントには、名前にスペースが含まれる ToUnicode 文字コードマップがあります。これらのスペースは、Unicode テキストマッピングでエラーを引き起こす可能性があります。<br/>            このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。<br/>            デフォルトは falseです。 |
| map_non_linked_symbols_on_space | 一部のフォントは、特定のテキストシンボルに対する Unicode 情報を提供しません。 <br/>            この情報欠如によりエラー \"Text cannot be mapped to Unicode\" が発生します。<br/>            このフラグを使用して、非リンクシンボルを Unicode の \"space\"（コード 32）にマップします。 |

### 関連項目

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

