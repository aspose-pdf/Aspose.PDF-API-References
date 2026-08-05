---
title: "PdfSaveOptions"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF 形式へのエクスポート用保存オプションです。"
type: docs
weight: 1240
url: /ja/python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

PDF 形式へのエクスポート用保存オプションです。

PdfSaveOptions 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfSaveOptions() | PdfSaveOptions クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| warning_handler | 生成された警告を処理するコールバックです。 <br/>            WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。 <br/>            Continue はデフォルトのアクションで、保存操作は継続しますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。 |
| save_format | データ保存の形式です。 |
| close_response | ドキュメントがレスポンスに保存された後に Response オブジェクトを閉じるかどうかを示すブール値を取得または設定します。 |
| temp_path | 一時ファイルのパスです。 |
| default_font_name | コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名です。<br/>            PDF に保存されるドキュメントに、ドキュメント自体やデバイスに存在しないフォントが含まれている場合、API はこれらのフォントを<br/>            デフォルトフォントに置き換えます（デバイス上に [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) というフォントが見つかった場合）。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

