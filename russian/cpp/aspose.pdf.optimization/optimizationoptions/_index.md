---
title: "Aspose::Pdf::Optimization::OptimizationOptions класс"
linktitle: "OptimizationOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Optimization::OptimizationOptions класс. Класс, который описывает алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources() в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class


Класс, описывающий алгоритм оптимизации документа. Экземпляр этого класса может использоваться в качестве параметра метода OptimizeResources().

```cpp
class OptimizationOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [All](./all/)() | Создаёт стратегию оптимизации со всеми активированными параметрами. Обратите внимание, что активируются только те параметры, которые не изменяют функциональность документа. Например, сжатие изображений и отключение встраивания шрифтов не будет включено (и может быть выполнено вручную). |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() const | Если true, содержимое страниц будет переиспользовано, когда документ оптимизируется для одинаковых страниц. |
|  | [get_CompressAllContentStreams](./get_compressallcontentstreams/)() const | Если установлено в **true** |

, все несжатые потоки содержимого страниц будут сжаты с использованием фильтра FlateDecode во время [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). По умолчанию **false**

для сохранения обратной совместимости. |
| [get_CompressImages](./get_compressimages/)() | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия задаётся свойством ImageQuality. |
|  | [get_CompressObjects](./get_compressobjects/)() const | Если этот флаг установлен в **true** |

, объекты [Pdf](../../aspose.pdf/) будут упакованы в потоки Objest и сжаты для уменьшения размера PDF‑файла. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Набор параметров, описывающих, будут ли изображения в документе сжаты и параметры сжатия. |
| [get_ImageEncoding](./get_imageencoding/)() const | [Image](../../aspose.pdf/image/) кодировка, которая будет использоваться. |
| [get_ImageQuality](./get_imagequality/)() | Указывает уровень сжатия изображения, когда используется флаг CompressIamges. |
| [get_LinkDuplicateStreams](./get_linkduplicatestreams/)() const | Если этот флаг установлен в true, потоки ресурсов будут проанализированы. Если найдены дублирующие потоки (т.е. содержимое потоков одинаково), то эти потоки будут сохранены как один объект. Это позволяет уменьшить размер документа в некоторых случаях (например, когда один и тот же документ был объединён несколько раз). |
| [get_MaxResoultion](./get_maxresoultion/)() | Указывает максимальное разрешение изображений. Если разрешение изображения выше, оно будет масштабировано. |
| [get_RemovePrivateInfo](./get_removeprivateinfo/)() const | Удалить личную информацию (информация о частях страниц). |
| [get_RemoveUnusedObjects](./get_removeunusedobjects/)() const | Если этот флаг установлен в true, все объекты документа будут проверены, и неиспользуемые объекты (т.е. объекты, не имеющие ссылок) будут удалены из документа. |
| [get_RemoveUnusedStreams](./get_removeunusedstreams/)() const | Если этот флаг установлен в true, каждый ресурс проверяется на использование. Если ресурс никогда не используется, он удаляется. Это может уменьшить размер документа, например, когда страницы извлекаются из документа. |
| [get_ResizeImages](./get_resizeimages/)() | Если этот флаг установлен в true и CompressImages также true, изображения будут изменять размер, если их разрешение превышает указанный параметр MaxResolution. |
| [get_SubsetFonts](./get_subsetfonts/)() const | Шрифты будут преобразованы в подмножества, если установлено значение true. |
| [get_UnembedFonts](./get_unembedfonts/)() const | Не встраивать шрифты, если установлено значение true. |
| [OptimizationOptions](./optimizationoptions/)() |  |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Если true, содержимое страниц будет переиспользовано, когда документ оптимизируется для одинаковых страниц. |
|  | [set_CompressAllContentStreams](./set_compressallcontentstreams/)(bool) | Если установлено в **true** |

, все несжатые потоки содержимого страниц будут сжаты с использованием фильтра FlateDecode во время [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). По умолчанию **false**

для сохранения обратной совместимости. |
| [set_CompressImages](./set_compressimages/)(bool) | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия задаётся свойством ImageQuality. |
|  | [set_CompressObjects](./set_compressobjects/)(bool) | Если этот флаг установлен в **true** |

, объекты [Pdf](../../aspose.pdf/) будут упакованы в потоки Objest и сжаты для уменьшения размера PDF‑файла. |
| [set_ImageEncoding](./set_imageencoding/)(Aspose::Pdf::Optimization::ImageEncoding) | [Image](../../aspose.pdf/image/) кодировка, которая будет использоваться. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Указывает уровень сжатия изображения, когда используется флаг CompressIamges. |
| [set_LinkDuplicateStreams](./set_linkduplicatestreams/)(bool) | Если этот флаг установлен в true, потоки ресурсов будут проанализированы. Если найдены дублирующие потоки (т.е. содержимое потоков одинаково), то эти потоки будут сохранены как один объект. Это позволяет уменьшить размер документа в некоторых случаях (например, когда один и тот же документ был объединён несколько раз). |
| [set_MaxResoultion](./set_maxresoultion/)(int32_t) | Указывает максимальное разрешение изображений. Если разрешение изображения выше, оно будет масштабировано. |
| [set_RemovePrivateInfo](./set_removeprivateinfo/)(bool) | Удалить личную информацию (информация о частях страниц). |
| [set_RemoveUnusedObjects](./set_removeunusedobjects/)(bool) | Если этот флаг установлен в true, все объекты документа будут проверены, и неиспользуемые объекты (т.е. объекты, не имеющие ссылок) будут удалены из документа. |
| [set_RemoveUnusedStreams](./set_removeunusedstreams/)(bool) | Если этот флаг установлен в true, каждый ресурс проверяется на использование. Если ресурс никогда не используется, он удаляется. Это может уменьшить размер документа, например, когда страницы извлекаются из документа. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Если этот флаг установлен в true и CompressImages также true, изображения будут изменять размер, если их разрешение превышает указанный параметр MaxResolution. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Шрифты будут преобразованы в подмножества, если установлено значение true. |
| [set_UnembedFonts](./set_unembedfonts/)(bool) | Не встраивать шрифты, если установлено значение true. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
