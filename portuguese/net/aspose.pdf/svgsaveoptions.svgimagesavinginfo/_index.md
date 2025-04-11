---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo class. Esta classe representa um conjunto de dados relacionado ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML
type: docs
weight: 10260
url: /pt/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Esta classe representa um conjunto de dados relacionado ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | O construtor padrão. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Definido pelo conversor. Representa o conteúdo binário do arquivo salvo. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não com código personalizado, mas com o código do próprio conversor de forma padrão para o conversor. Assim, definir como true significa que o código personalizado não processou o arquivo referenciado e o conversor deve lidar com isso (em ambos os sentidos - para salvar em algum lugar e para nomear no arquivo referenciado). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | representa o tipo da imagem salva referenciada no HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)