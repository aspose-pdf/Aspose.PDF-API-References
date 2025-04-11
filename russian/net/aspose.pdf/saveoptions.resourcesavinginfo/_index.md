---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.SaveOptionsResourceSavingInfo. Этот класс представляет собой набор данных, связанных с сохранением внешних файлов ресурсов, которые происходят во время конвертации PDF в другой формат, например, HTML
type: docs
weight: 9940
url: /ru/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

Этот класс представляет собой набор данных, связанных с сохранением внешних файлов ресурсов, которые происходят во время конвертации PDF в другой формат (например, HTML)

```csharp
public class ResourceSavingInfo
```

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или где сохранить этот файл |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Устанавливается конвертером. Представляет собой двоичный контент сохраненного файла. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а кодом самого конвертера стандартным для конвертера способом. Таким образом, установка этого флага в true означает, что пользовательский код не обработал ссылочный файл, и конвертер должен обработать его самостоятельно (в обоих смыслах - для сохранения где-то и для именования в ссылочном файле). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Устанавливается конвертером. Предполагаемое имя файла, которое передается от конвертера к коду пользовательского метода. Может использоваться в пользовательском коде для решения, как обрабатывать или где сохранить этот файл |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)