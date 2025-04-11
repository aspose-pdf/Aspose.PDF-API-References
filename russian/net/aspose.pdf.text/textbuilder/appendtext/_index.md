---
title: TextBuilder.AppendText
second_title: Aspose.PDF for .NET API Reference
description: Метод TextBuilder. Добавляет текстовый фрагмент на страницу Pdf
type: docs
weight: 30
url: /ru/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

Добавляет текстовый фрагмент на страницу Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFragment | TextFragment | Объект текстового фрагмента. |

## Примеры

Пример демонстрирует, как создать объект текстового фрагмента, настроить его текстовые сегменты и добавить его на страницу Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// create text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// set it's text properties
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// add one more segment to text fragment's Segments collection
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### См. также

* класс [TextFragment](../../textfragment/)
* класс [TextBuilder](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Добавляет список текстовых фрагментов на страницу Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFragments | List`1 | Коллекция текстовых фрагментов |

### См. также

* класс [TextFragment](../../textfragment/)
* класс [TextBuilder](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)