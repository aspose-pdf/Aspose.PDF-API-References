---
title: Class StructElement
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Structure.StructElement. Общий элемент структуры
type: docs
weight: 10180
url: /ru/net/aspose.pdf.structure/structelement/
---
## Класс StructElement

Общий элемент структуры.

```csharp
public class StructElement : Element
```

## Свойства

| Название | Описание |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Необязательно; PDF 1.4) Текст, который является точной заменой для элемента структуры и его дочерних элементов. Этот текст замены (который должен применяться к как можно меньшему объему контента) полезен при извлечении содержимого документа в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Необязательно) Альтернативное описание элемента структуры и его дочерних элементов в читаемой форме, которое полезно при извлечении содержимого документа в поддержку доступности для пользователей с ограниченными возможностями или для других целей. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Получает коллекцию дочерних элементов. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Необязательно; PDF 1.5) Расширенная форма аббревиатуры. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Необязательно; PDF 1.4) Язык, указывающий естественный язык для всего текста в элементе структуры, за исключением случаев, когда он переопределен языковыми спецификациями для вложенных элементов структуры или размеченного контента. |

## Методы

| Название | Описание |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Удалить элемент. |

### См. также

* класс [Element](../element/)
* пространство имен [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* сборка [Aspose.PDF](../../)