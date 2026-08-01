---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FreeTextAnnotation メソッド。パラメータ textStyle によって決定される書式設定をすべての注釈テキストに適用します"
type: docs
weight: 150
url: /ja/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

パラメータ textStyle によって決定された書式設定を、すべてのアノテーションテキストに適用します。

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| textStyles | RichTextFontStyles | 注釈テキストに適用されるスタイル。 |
| fontName | String | 注釈テキストに適用されるフォント名。 |
| fontSize | Double | 注釈テキストに適用されるフォントサイズ。 |
| fontColor | Color | 注釈テキストに適用されるフォントカラー。 |

### 関連項目

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

パラメータ textStyle によって決定された書式設定を、fromInd インデックスから toInd インデックスまでのテキストフラグメントに適用します。

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fromInd | Int32 | テキストフラグメントの開始インデックス（0 から）。 |
| toInd | Int32 | テキストフラグメントの終了インデックス（0 から数え、含まれません）。 |
| textStyles | RichTextFontStyles | テキストフラグメントに適用されるスタイル。 |

### 関連項目

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


