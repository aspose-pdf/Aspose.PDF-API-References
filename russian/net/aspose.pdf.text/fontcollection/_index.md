---
title: "Класс FontCollection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.FontCollection. Представляет коллекцию шрифтов."
type: docs
weight: 10710
url: /ru/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

Представляет коллекцию шрифтов.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Получает количество элементов объекта [`Font`](../font/), фактически содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Возвращает значение, указывающее, является ли коллекция только для чтения |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Получает элемент шрифта по указанному индексу. (2 индексатора) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Возвращает объект, который можно использовать для синхронизации доступа к коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Добавляет новый шрифт в ресурсы шрифтов и возвращает автоматически присвоенное имя ресурса шрифта. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Определяет, содержит ли коллекция конкретное значение. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Проверяет, существует ли шрифт в коллекции шрифтов. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Возвращает перечислитель для всей коллекции. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Удаляет указанный элемент из коллекции. |

## Примечания

Коллекции шрифтов, представленные классом `FontCollection`, используются в нескольких сценариях. Например, в ресурсах со свойством [`Fonts`](../../aspose.pdf/resources/fonts/).

## Примеры

Пример демонстрирует, как сделать все шрифты, объявленные на странице, встроенными.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// убедитесь, что все шрифты, объявленные в ресурсах страницы, встроены
// обратите внимание, что если шрифты объявлены в ресурсах формы, они недоступны из ресурсов страницы
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### См. также

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


