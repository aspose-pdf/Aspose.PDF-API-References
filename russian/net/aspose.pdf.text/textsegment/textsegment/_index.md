---
title: "TextSegment.TextSegment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор TextSegment. Создаёт объект TextSegment"
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

В примере демонстрируется, как создать объект фрагмента текста, добавить сегмент текста в коллекцию фрагментов текста и добавить его на страницу Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// создать фрагмент текста
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// установить его свойства текста
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// добавить ещё один сегмент в коллекцию Segments фрагмента текста
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// создать объект TextBuilder
TextBuilder builder = new TextBuilder(page);

// добавить фрагмент текста на страницу Pdf
builder.AppendText(tf);

//сохранить документ
doc.Save(outFile);
```

### См. также

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

Создает объект TextSegment.

```csharp
public TextSegment(string text)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | String | Текст сегмента. |

## Примеры

В примере демонстрируется, как создать объект фрагмента текста, добавить сегмент текста в коллекцию фрагментов текста и добавить его на страницу Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// создать фрагмент текста
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// установить его свойства текста
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// добавить ещё один сегмент в коллекцию Segments фрагмента текста
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// создать объект TextBuilder
TextBuilder builder = new TextBuilder(page);

// добавить фрагмент текста на страницу Pdf
builder.AppendText(tf);

//сохранить документ
doc.Save(outFile);
```

### См. также

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


