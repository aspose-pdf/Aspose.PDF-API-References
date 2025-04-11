---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.GoToAction クラス。指定された宛先ページの位置と拡大率にビューを変更する goto アクションを表します。
type: docs
weight: 1830
url: /ja/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction クラス

指定された宛先（ページ、位置、拡大率）にビューを変更する go-to アクションを表します。

```csharp
public class GoToAction : PdfAction
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | コンストラクター。 |
| [GoToAction](gotoaction/#constructor_3)(Page) | GoToAction クラスのコンストラクター。 |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | 名前付き宛先にリンクされたアクション。 |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | GoToAction クラスのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | ジャンプする宛先を取得または設定します。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | シーケンス内の次のアクション。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript アクションの文字列を取得します。 |

### 参照

* クラス [PdfAction](../pdfaction/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)