---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Optimization.OptimizationOptions. Класс, который описывает алгоритм оптимизации документа. Экземпляр этого класса может быть использован в качестве параметра метода OptimizeResources
type: docs
weight: 7980
url: /ru/net/aspose.pdf.optimization/optimizationoptions/
---
## Класс OptimizationOptions

Класс, который описывает алгоритм оптимизации документа. Экземпляр этого класса может быть использован в качестве параметра метода OptimizeResources().

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
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Если true, содержимое страниц будет повторно использовано, когда документ оптимизируется для равных страниц. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Если этот флаг установлен в `true`, объекты Pdf будут упакованы в потоки объектов и сжаты для уменьшения размера pdf файла. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Набор параметров, который описывает, будут ли изображения в документе сжаты и параметры сжатия. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Кодек изображения, который будет использоваться. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Если этот флаг установлен в true, потоки ресурсов будут проанализированы. Если найдены дублирующие потоки (т.е. если содержимое потока одинаково), то эти потоки будут сохранены как один объект. Это позволяет уменьшить размер документа в некоторых случаях (например, когда один и тот же документ был несколько раз объединен). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Уровень сканирования. Более глубокие сканирования (большее значение) занимают больше времени, но могут привести к меньшим итоговым файлам. Значение по умолчанию: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Указывает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Удалить личную информацию (информация о частях страниц). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Если этот флаг установлен в true, все объекты документа будут проверены, и неиспользуемые объекты (т.е. объекты, которые не имеют никаких ссылок) будут удалены из документа. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Если этот флаг установлен в true, каждый ресурс проверяется на его использование. Если ресурс никогда не использовался, то он удаляется. Это может уменьшить размер документа, например, когда страницы были извлечены из документа. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Шрифты будут преобразованы в подсеты, если установлено значение true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Сделать шрифты не встроенными, если установлено значение true. |

## Методы

| Имя | Описание |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Создает стратегию оптимизации с активированными всеми параметрами. Обратите внимание, что активированы только параметры, которые не изменяют функциональность документа. Т.е. сжатие изображений и извлечение шрифтов не будет включено (и может быть встроено вручную). |

### См. также

* пространство имен [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* сборка [Aspose.PDF](../../)