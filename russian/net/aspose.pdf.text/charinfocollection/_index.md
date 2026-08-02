---
title: "Класс CharInfoCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.CharInfoCollection. Представляет коллекцию объектов CharInfo"
type: docs
weight: 10630
url: /ru/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Представляет коллекцию объектов CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Возвращает количество элементов объекта [`CharInfo`](../charinfo/), фактически содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Возвращает элемент CharInfo по указанному индексу. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Возвращает объект, который можно использовать для синхронизации доступа к коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Коллекция только для чтения, генерирует NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Коллекция только для чтения. Всегда генерирует NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Определяет, содержит ли коллекция конкретное значение. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Возвращает перечислитель для всей коллекции. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Коллекция только для чтения, генерирует NotImplementedException. |

## Примечания

Обеспечивает доступ к информации о позиционировании символов текстового сегмента.

## Примеры

Пример демонстрирует, как перебрать все символы и получить символ

```csharp
//открыть документ
Document pdfDocument = new Document(inFile);
//создать объект TextFragmentAbsorber для сбора всех текстовых объектов страницы
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//принять поглотитель для всех страниц
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//получить извлечённые фрагменты текста
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//перебрать фрагменты
foreach (TextFragment textFragment in textFragmentCollection)
{
    //перебрать сегменты
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //перебрать символы
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // вывести позицию символа и информацию о прямоугольнике
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### См. также

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


