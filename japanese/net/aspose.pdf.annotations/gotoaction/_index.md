---
title: "クラス GoToAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.GoToAction クラス。指定された宛先ページ位置と拡大率にビューを変更する goto アクションを表します。"
type: docs
weight: 1920
url: /ja/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction class

指定されたデスティネーション（ページ、位置、拡大率）にビューを変更する go-to アクションを表します。

```csharp
public class GoToAction : PdfAction
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | コンストラクタ。 |
| [GoToAction](gotoaction/#constructor_3)(Page) | GoToAction クラスのコンストラクタです。 |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | 名前付き宛先にリンクされたアクションです。 |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | GoToAction クラスのコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | ジャンプ先の宛先を取得または設定します。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | シーケンス内の次のアクション。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript アクションの文字列を取得します。 |

### 関連項目

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


