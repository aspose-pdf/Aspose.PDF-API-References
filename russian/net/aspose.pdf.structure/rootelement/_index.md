---
title: "Класс RootElement"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Structure.RootElement класс. Корневой структурный элемент"
type: docs
weight: 10350
url: /ru/net/aspose.pdf.structure/rootelement/
---
## RootElement class

Элемент корневой структуры.

```csharp
public class RootElement : Element
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Optional; PDF 1.4) Текст, который является точной заменой структурного элемента и его дочерних элементов. Этот заменяющий текст (который должен применяться к максимально небольшому куску содержимого) полезен при извлечении содержимого документа в целях обеспечения доступности для пользователей с ограниченными возможностями или для других целей. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Optional) Альтернативное описание структурного элемента и его дочерних элементов в человекочитаемой форме, которое полезно при извлечении содержимого документа в целях обеспечения доступности для пользователей с ограниченными возможностями или для других целей. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Получает коллекцию дочерних элементов. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Optional; PDF 1.5) Расширенная форма аббревиатуры. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Optional; PDF 1.4) Язык, указывающий естественный язык для всего текста в структурном элементе, за исключением случаев, когда он переопределяется спецификациями языка для вложенных структурных элементов или помеченного контента. |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Удалить элемент. |

### См. также

* class [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)


