---
title: Class RootElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Structure.RootElement. Корневой элемент структуры
type: docs
weight: 10170
url: /ru/net/aspose.pdf.structure/rootelement/
---
## Класс RootElement

Корневой элемент структуры.

```csharp
public class RootElement : Element
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Необязательно; PDF 1.4) Текст, который является точной заменой для элемента структуры и его дочерних элементов. Этот текст замены (который должен применяться к как можно меньшему объему контента) полезен при извлечении содержимого документа в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в читаемой форме, которое полезно при извлечении содержимого документа в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Получает коллекцию дочерних элементов. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Необязательно; PDF 1.5) Расширенная форма аббревиатуры. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Необязательно; PDF 1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или отмеченного контента. |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Удалить элемент. |

### См. также

* класс [Element](../element/)
* пространство имен [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* сборка [Aspose.PDF](../../)