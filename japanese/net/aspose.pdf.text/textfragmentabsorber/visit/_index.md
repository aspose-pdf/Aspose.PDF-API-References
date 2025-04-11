---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber メソッド。指定されたページで検索を実行します
type: docs
weight: 150
url: /ja/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

指定されたページで検索を実行します。

```csharp
public override void Visit(Page page)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| page | Page | PDF ドキュメントページオブジェクト。 |

## 例

この例では、最初の PDF ドキュメントページでテキストを見つけて、テキストを置き換える方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

指定されたドキュメントで検索を実行します。

```csharp
public override void Visit(Document pdf)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdf | Document | PDF ドキュメントオブジェクト。 |

## 例

この例では、PDF ドキュメントでテキストを見つけ、すべての検索結果のテキストを置き換える方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

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

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xForm | XForm | Pdf フォームオブジェクト。 |

### 参照

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)