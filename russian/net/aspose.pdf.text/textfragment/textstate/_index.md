---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextFragment. Получает или устанавливает состояние текста для текста, который представляет объект TextFragment
type: docs
weight: 150
url: /ru/net/aspose.pdf.text/textfragment/textstate/
---
## Свойство TextFragment.TextState

Получает или устанавливает состояние текста для текста, который представляет объект [`TextFragment`](../).

```csharp
public TextFragmentState TextState { get; }
```

## Примечания

Предоставляет способ изменить следующие свойства текста: Шрифт РазмерШрифта СтильШрифта ЦветПереднегоПлана ЦветЗаднегоПлана

## Примеры

Пример демонстрирует, как изменить цвет текста и размер шрифта текста с объектом `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [TextFragmentAbsorber](../../textfragmentabsorber/)
* класс [Document](../../../aspose.pdf/document/)
* класс [TextFragmentState](../../textfragmentstate/)
* класс [TextFragment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)