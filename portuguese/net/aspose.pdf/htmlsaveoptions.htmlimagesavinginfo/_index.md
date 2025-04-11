---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML
type: docs
weight: 5640
url: /pt/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## Classe HtmlSaveOptions.HtmlImageSavingInfo

Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo. |

## Campos

| Nome | Descrição |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Definido pelo conversor. Representa o conteúdo binário do arquivo salvo. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, o arquivo proposto deve ser processado não com código personalizado, mas com o código do conversor em seu modo padrão. Assim, definir como verdadeiro significa que o código personalizado não processou o arquivo referenciado e o conversor deve lidar com isso (em ambos os sentidos - para salvar em algum lugar e para nomear no arquivo referenciado). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Informa ao código personalizado a que página do conjunto gerado de arquivos de página HTML a imagem salva pertence. Se a divisão em páginas estiver desativada, este valor sempre contém '1', uma vez que, nesse caso, apenas uma página HTML é gerada. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Representa o tipo de imagem salva referenciada no HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | A imagem salva pode pertencer ao HTML em si ou pode ser extraída de SVG incorporado ao HTML. Esta propriedade pode informar ao código personalizado qual é o tipo de pai da imagem processada. É definida pelo conversor e pode ser usada no código personalizado para decidir o que deve ser feito com essa imagem (por exemplo, o código personalizado pode decidir onde salvar a imagem ou como ela deve ser referenciada no conteúdo do pai). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Informa ao código personalizado a que página do documento PDF original a imagem salva pertence. Como é possível que nem todas as páginas do documento original sejam salvas, este valor nos informa sobre o número da página hospedeira no PDF original. Se o número da página original, por algum motivo, for desconhecido, ele sempre retorna '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar esse arquivo. |

### Veja Também

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)