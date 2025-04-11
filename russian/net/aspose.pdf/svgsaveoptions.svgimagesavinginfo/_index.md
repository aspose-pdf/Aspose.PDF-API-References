---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Этот класс представляет собой набор данных, связанных с сохранением изображений внешних ресурсов во время конвертации PDF в HTML.
type: docs
weight: 10260
url: /ru/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Этот класс представляет собой набор данных, связанных с сохранением изображений внешних ресурсов во время конвертации PDF в HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Конструктор по умолчанию. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для определения того, как обрабатывать или где сохранить этот файл. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Устанавливается конвертером. Представляет бинарное содержимое сохраненного файла. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-то причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а кодом самого конвертера стандартным для конвертера способом. Таким образом, установка этого флага в true означает, что пользовательский код не обработал указанный файл, и конвертер должен обработать его самостоятельно (в обоих смыслах - для сохранения где-то и для именования в ссылочном файле). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Представляет тип сохраненного изображения, на которое ссылаются в HTML. Устанавливается конвертером и может использоваться в пользовательском коде для определения того, что следует сделать. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для определения того, как обрабатывать или где сохранить этот файл. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)