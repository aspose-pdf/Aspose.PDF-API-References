---
title: "Класс OptimizationOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Optimization.OptimizationOptions. Класс, который описывает алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources."
type: docs
weight: 8120
url: /ru/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Класс, описывающий алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources().

```csharp
public class OptimizationOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Если true, содержимое страниц будет переиспользовано, когда документ оптимизируется для одинаковых страниц. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Если этот флаг установлен в `true`, объекты Pdf будут упакованы в потоки Objest Streams и сжаты для уменьшения размера pdf‑файла. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Набор параметров, описывающих, будут ли изображения в документе сжаты и параметры сжатия. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Кодировка изображения, которая будет использоваться. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Если этот флаг установлен в true, потоки ресурсов будут проанализированы. Если найдены дублирующие потоки (т.е. если содержимое потоков одинаково), то эти потоки будут сохранены как один объект. Это позволяет уменьшить размер документа в некоторых случаях (например, когда один и тот же документ был конкатенирован несколько раз). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Указывает максимальное разрешение изображений. Если у изображения разрешение выше, оно будет масштабировано. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Удалить личную информацию (информация о части страницы). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Если этот флаг установлен в true, все объекты документа будут проверены, и неиспользуемые объекты (т.е. объекты, не имеющие ссылок) будут удалены из документа. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Если этот флаг установлен в true, каждый ресурс проверяется на использование. Если ресурс никогда не используется, он удаляется. Это может уменьшить размер документа, например, когда страницы были извлечены из документа. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Шрифты будут преобразованы в подмножества, если установлен флаг true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Не встраивать шрифты, если установлен флаг true. |

## Методы

| Имя | Описание |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Создаёт стратегию оптимизации со всеми активированными параметрами. Обратите внимание, что активируются только те параметры, которые не изменяют функциональность документа. Т.е. сжатие изображений и отключение встраивания шрифтов не будет включено (их можно включить вручную). |

### См. также

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


