---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.FontCollection. Представляет коллекцию шрифтов
type: docs
weight: 10530
url: /ru/net/aspose.pdf.text/fontcollection/
---
## Класс FontCollection

Представляет коллекцию шрифтов.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Получает количество элементов объекта [`Font`](../font/) фактически содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к коллекции (безопасно для потоков). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Получает элемент шрифта по указанному индексу. (2 индексатора) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Добавляет новый шрифт в ресурсы шрифтов и возвращает автоматически назначенное имя ресурса шрифта. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Определяет, содержит ли коллекция конкретное значение. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Проверяет, существует ли шрифт в коллекции шрифтов. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Возвращает перечислитель для всей коллекции. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Удаляет указанный элемент из коллекции. |

## Примечания

Коллекции шрифтов, представленные классом `FontCollection`, используются в нескольких сценариях. Например, в ресурсах с свойством [`Fonts`](../../aspose.pdf/resources/fonts/).

## Примеры

Пример демонстрирует, как сделать все шрифты, объявленные на странице, встроенными.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### См. также

* класс [Font](../font/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)