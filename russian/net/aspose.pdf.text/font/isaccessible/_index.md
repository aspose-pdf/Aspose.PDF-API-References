---
title: "Font.IsAccessible"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Font. Возвращает, установлен ли шрифт в системе"
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

Получает индикатор того, установлен ли шрифт в системе.

```csharp
public bool IsAccessible { get; }
```

## Примечания

Некоторые операции недоступны для шрифтов, которые не найдены в системе.

## Примеры

В примере демонстрируется, как искать текст на первой странице и получить значение, указывающее, установлен ли шрифт в системе.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Просмотр значения IsSubset шрифта первого вхождения текста
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


