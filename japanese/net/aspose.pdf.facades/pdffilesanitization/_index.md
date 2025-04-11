---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization クラス。サニタイズおよびリカバリー API を表します。他の方法でドキュメントを作成/開くことができない場合に使用します。
type: docs
weight: 4540
url: /ja/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization クラス

サニタイズおよびリカバリー API を表します。他の方法でドキュメントを作成/開くことができない場合に使用します。

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | デフォルトコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | ドキュメントファサードが作業しているドキュメントを取得します。 |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | ファイルが保存された後、ファイルに対して行われた操作を確認できます。 |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | ドキュメントの新しい xref とトレーラーを生成することを許可します。 |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | PDF データの後のデータを削除することを許可します。 |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | PDF データの前のデータを削除することを許可します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | サニタイズ用に PDF ストリームをバインドします。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | サニタイズ用に PDF ファイルをバインドします。 |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | ファサードを閉じます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | 古い xref とトレーラーを削除し、新しい xref とトレーラーを作成します。 |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | ドキュメントをリカバリーします。プロパティを使用してカスタマイズします。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 結果の PDF をストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 結果の PDF をファイルに保存します。 |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 最後の %%EOF の後のデータを削除します。 |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | %PDF の前のデータを削除します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)