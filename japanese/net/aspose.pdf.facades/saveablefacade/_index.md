---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.SaveableFacade クラス。すべての保存可能なファサードの基本クラス
type: docs
weight: 4700
url: /ja/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade クラス

すべての保存可能なファサードの基本クラスです。

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | ファサードが作業しているドキュメントを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | ファサードにバインドされた Aspose.Pdf.Document を破棄します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | PDF ドキュメントを指定されたファイルに保存します。 |

### 参照

* クラス [Facade](../facade/)
* インターフェース [ISaveableFacade](../isaveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)