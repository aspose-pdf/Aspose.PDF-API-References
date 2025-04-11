---
title: TextSegment.TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Конструктор TextSegment. Создает объект TextSegment
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

Создает объект TextSegment.

```csharp
public TextSegment()
```

## Примеры

Пример демонстрирует, как создать объект текстового фрагмента, добавить сегмент текста в коллекцию текстовых фрагментов и добавить его на страницу Pdf.

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

* класс [TextSegment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Создает объект TextSegment.

```csharp
public TextSegment(string text)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст сегмента текста. |

## Примеры

Пример демонстрирует, как создать объект текстового фрагмента, добавить сегмент текста в коллекцию текстовых фрагментов и добавить его на страницу Pdf.

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
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// create TextBuilder object
TextBuilder builder = new TextBuilder(page);

// append the text fragment to the Pdf page
builder.AppendText(tf);

//save document
doc.Save(outFile);
```

### См. также

* класс [TextSegment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)