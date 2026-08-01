---
title: "クラス PdfFileSanitization"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileSanitization クラス。サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。"
type: docs
weight: 4660
url: /ja/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | ファイルが保存された後、ファイルに対して行われた処理を確認できます。 |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | ドキュメントの新しい xref とトレーラを生成できるようにします。 |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | PDF データの後にデータを削除できるようにします。 |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | PDF データの前にデータを削除できるようにします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | サニタイズ用に Pdf ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | サニタイズ用に Pdf ファイルをバインドします。 |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | ファサードを閉じます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | トレーラ付きの古い xref を削除し、トレーラ付きの新しい xref を作成します。 |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | ドキュメントを復元します。プロパティを使用してカスタマイズしてください。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 結果の PDF をストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 結果の PDF をファイルに保存します。 |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 最後の %%EOF の後のデータを削除します。 |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | %PDF の前のデータを削除します。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


