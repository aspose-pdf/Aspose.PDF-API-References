---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextFragmentAbsorber メソッド。指定されたページで検索を実行します"
type: docs
weight: 150
url: /ja/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

指定された Page で検索を実行します。

```csharp
public override void Visit(Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | PDF document page オブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページ上のテキストを見つけて置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
absorber.Visit(doc.Pages[1]);

// すべての検索結果のテキストを変更する
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定された Document で検索を実行します。

```csharp
public override void Visit(Document pdf)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pdf | Document | PDF document オブジェクト。 |

## 例

この例は、PDF document 上でテキストを検索し、すべての検索結果のテキストを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
absorber.Visit(doc);

// 最初のテキスト出現箇所のテキストを変更します。
absorber.TextFragments[1].Text = "hi world";

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

指定されたフォームオブジェクトで検索を実行します。

```csharp
public void Visit(XForm xForm)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xForm | XForm | Pdf フォーム オブジェクト。 |

### 関連項目

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


