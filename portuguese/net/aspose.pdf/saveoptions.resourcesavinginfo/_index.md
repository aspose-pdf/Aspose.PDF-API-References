---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SaveOptionsResourceSavingInfo. Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de recursos externos que ocorre durante a conversão de PDF para algum outro formato, por exemplo, HTML
type: docs
weight: 9940
url: /pt/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## Classe SaveOptions.ResourceSavingInfo

Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de recursos externos que ocorre durante a conversão de PDF para algum outro formato (por exemplo, HTML)

```csharp
public class ResourceSavingInfo
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo |

## Campos

| Nome | Descrição |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Definido pelo conversor. Representa o conteúdo binário do arquivo salvo. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não com código personalizado, mas com o código do conversor em si, de forma padrão para o conversor. Assim, definir como verdadeiro significa que o código personalizado não processou o arquivo referenciado e o conversor deve lidar com isso por conta própria (em ambos os sentidos - para salvar em algum lugar e para nomear no arquivo referenciado). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo |

### Veja Também

* classe [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)