---
title: "クラス GoToRemoteAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.GoToRemoteAction クラス。リモートの goto アクションを表します。これは通常の goto アクションと似ていますが、現在のファイルではなく別の PDF ファイル内の宛先へジャンプします。"
type: docs
weight: 1930
url: /ja/net/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class

通常の go-to アクションと似ていますが、現在のファイルではなく別の PDF ファイル内のデスティネーションへジャンプする remote go-to アクションを表します。

```csharp
public sealed class GoToRemoteAction : GoToAction
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GoToRemoteAction](gotoremoteaction/#constructor)(string, ExplicitDestination) | GoToRemoteAction オブジェクトを初期化します。 |
| [GoToRemoteAction](gotoremoteaction/#constructor_1)(string, int) | GoToRemoteAction オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Destination](../../aspose.pdf.annotations/gotoremoteaction/destination/) { get; set; } | ジャンプ先の宛先を取得または設定します。 |
| [File](../../aspose.pdf.annotations/gotoremoteaction/file/) { get; set; } | 宛先が存在するファイルの仕様を取得または設定します。 |
| [NewWindow](../../aspose.pdf.annotations/gotoremoteaction/newwindow/) { get; set; } | 宛先ドキュメントを新しいウィンドウで開くかどうかを指定するフラグを取得または設定します。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | シーケンス内の次のアクション。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript アクションの文字列を取得します。 |

### 関連項目

* class [GoToAction](../gotoaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


