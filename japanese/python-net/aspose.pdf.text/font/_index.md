---
title: "Font"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フォントオブジェクトを表します。"
type: docs
weight: 100
url: /ja/python-net/aspose.pdf.text/font/
---

## Font class

フォントオブジェクトを表します。

Font 型は次のメンバーを公開します:
## プロパティ
| 名前 | 説明 |
| :- | :- |
| font_name | [Font](/pdf/python-net/aspose.pdf.text/font/) オブジェクトのフォント名を取得します。 |
| decoded_font_name | PDF フォント（主に中国語/日本語/韓国語フォント）は特定のフォント名を持つことがあります。<br/>            この名前は PDF フォントプロパティ "BaseFont" の値で、場合によっては 16 進形式で表されることがあります。直接この名前を読むと、非可読形式になることがあります。可読形式を取得するには、そのフォント固有の規則でフォント名をデコードする必要があります。<br/>            このプロパティはデコードされたフォント名を返すので、非可読な [font_name](/pdf/python-net/aspose.pdf.text/font/) に遭遇した場合に使用してください。<br/>            プロパティ [font_name](/pdf/python-net/aspose.pdf.text/font/) が可読形式であれば、このプロパティは同じものとなります。そのため、フォント名を可読形式で取得する必要があるあらゆるケースでこのプロパティを使用できます。 |
| base_font | PDF フォントオブジェクトの BaseFont 値を取得します。フォントの PostScript 名としても知られています。 |
| is_embedded | フォントが埋め込まれているかどうかを示す値を取得または設定します。<br/>            IFont に基づくフォントは自動的にサブセット化され、埋め込まれます |
| is_subset | フォントがサブセットかどうかを示す値を取得または設定します。<br/>             IFont に基づくフォントは自動的にサブセット化され、埋め込まれます |
| is_accessible | フォントがシステムに存在（インストール）されているかどうかを取得します。 |
| font_options | フォントの動作を調整するための便利なプロパティ |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_last_font_embedding_error() | このメソッドの目的は、フォントの埋め込みが失敗した場合にエラーの説明を返すことです。<br/>            エラーが発生しない場合は空文字列を返します。 |
| save(stream) | フォントをストリームに保存します。<br/>            フォントは、元のドキュメントの変換コピーでのみ使用されることを想定した中間TTF形式で保存されます。<br/>            フォントファイルは、元のドキュメントのコンテキスト外で使用することは想定されていません。 |
| measure_string(str, font_size) | 文字列を測定します。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

