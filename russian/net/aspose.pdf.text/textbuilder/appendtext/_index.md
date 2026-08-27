---
title: "TextBuilder.AppendText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextBuilder. Добавляет фрагмент текста на страницу Pdf"
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
| textFragment | TextFragment | Объект фрагмента текста. |

## Примеры

Пример демонстрирует, как создать объект фрагмента текста, настроить его сегменты текста и добавить его на страницу Pdf.

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

Добавляет список текстовых фрагментов на страницу Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFragments | List`1 | Коллекция фрагментов текста |

### См. также

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


