---
title: "TextFragment.TextState"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragment. Получает или задаёт состояние текста, представленного объектом TextFragment."
type: docs
weight: 150
url: /ru/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

Получает или задаёт состояние текста, представленного объектом [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Примечания

Предоставляет возможность изменить следующие свойства текста: Font FontSize FontStyle ForegroundColor BackgroundColor.

## Примеры

В примере показано, как изменить цвет текста и размер шрифта с помощью объекта `TextState`.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить цвет переднего плана первого вхождения текста.
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Изменить размер шрифта первого вхождения текста.
absorber.TextFragments[1].TextState.FontSize = 15;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


