---
title: "クラス SaveableFacade"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.SaveableFacade クラス。すべての保存可能ファサードの基底クラス"
type: docs
weight: 4820
url: /ja/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class

保存可能なすべてのファサードの基底クラスです。

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |

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

### 関連項目

* class [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


