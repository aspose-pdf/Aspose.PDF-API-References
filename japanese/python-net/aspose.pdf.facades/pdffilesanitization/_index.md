---
title: "PdfFileSanitization"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "サニタイズと復元の API を表します。<br/>            他の方法でドキュメントを作成/開くことができない場合に使用してください。"
type: docs
weight: 290
url: /ja/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

サニタイズと復元の API を表します。<br/>            他の方法でドキュメントを作成/開くことができない場合に使用してください。

PdfFileSanitization 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfFileSanitization() | PdfFileSanitization クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| ログ | ファイルが保存された後、ファイルに対して何が行われたかを確認できます。 |
| use_trim_top | pdf データの前のデータを削除できるようにします。 |
| use_trim_bottom | pdf データの後のデータを削除できるようにします |
| use_rebuild_xref_and_trailer | ドキュメント用に新しい xref とトレーラを生成できるようにします。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(input_file) | サニタイズ用に Pdf ファイルをバインドします。 |
| bind_pdf(input_stream) | サニタイズ用に Pdf ストリームをバインドします。 |
| bind_pdf(src_doc) | ファサードを初期化します。 |
| save(output_file) | 結果の PDF をファイルに保存します。 |
| save(output_stream) | 結果の PDF をストリームに保存します。 |
| close() | ファサードを閉じます。 |
| recover() | ドキュメントを復元します。<br/>            カスタマイズするにはプロパティを使用します。 |
| trim_top() | %PDF の前のデータを削除します。 |
| trim_bottom() | 最後の %%EOF の後のデータを削除します。 |
| rebuild_xref_and_trailer() | 古い xref とトレーラを削除し、新しい xref とトレーラを作成します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

