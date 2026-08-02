---
title: "Класс SvgSaveOptions.SvgImageSavingInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo класс. Этот класс представляет набор данных, связанных с сохранением файлов изображений внешних ресурсов во время преобразования PDF в HTML."
type: docs
weight: 10440
url: /ru/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Этот класс представляет набор данных, связанных с сохранением файлов изображений внешних ресурсов во время преобразования PDF в HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Устанавливается конвертером. Предполагаемое имя файла, которое передаётся от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать файл или где его сохранять. |

## Поля

| Имя | Описание |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Устанавливается конвертером. Представляет бинарное содержимое сохранённого файла. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Этот флаг должен быть установлен в \"true\" в пользовательском коде, если по каким‑то причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным способом для конвертера. Таким образом, установка значения true означает, что пользовательский код не обработал указанный файл, и конвертер должен обработать его самостоятельно (и при сохранении, и при указании имени в ссылочном файле). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Представляет тип сохранённого изображения, используемого в HTML. Устанавливается конвертером и может использоваться в пользовательском коде для решения, что следует сделать. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передаётся от конвертера в код пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать файл или где его сохранять. |

### См. также

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


