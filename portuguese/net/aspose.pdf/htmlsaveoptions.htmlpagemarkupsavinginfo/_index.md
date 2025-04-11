---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Se a propriedade SplitToPages de HtmlSaveOptions estiver ativada, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão de PDF para HTML. Esta classe representa um conjunto de dados relacionado ao salvamento personalizado da marcação de uma página HTML durante a conversão de PDF para HTML.
type: docs
weight: 5670
url: /pt/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Classe HtmlSaveOptions.HtmlPageMarkupSavingInfo

Se a propriedade SplitToPages de HtmlSaveOptions estiver ativada, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão de PDF para HTML. Esta classe representa um conjunto de dados relacionado ao salvamento personalizado da marcação de uma página HTML durante a conversão de PDF para HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Campos

| Nome | Descrição |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Definido pelo conversor. Representa o HTML salvo como um fluxo |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Deve ser definido no código personalizado quando necessário. Esta flag deve ser definida como "true" no código personalizado se, por algum motivo, a marcação HTML fornecida deve ser processada não com o código personalizado, mas com o código do conversor em um padrão para o conversor. Portanto, definir essa flag no código personalizado significa que o código personalizado não processou o arquivo referenciado e o conversor deve lidar com isso por conta própria |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade contém o número ordinal do arquivo da página HTML salva. A propriedade pode ser usada na lógica do código personalizado para decidir como processar ou onde salvar a página HTML e, se a divisão em páginas estiver desativada, esse valor sempre contém '1', uma vez que, nesse caso, apenas uma grande página HTML é gerada para todo o documento de origem. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Definido pelo conversor. Se a propriedade SplitToPages estiver definida, vários arquivos HTML (um arquivo HTML por página convertida) são criados durante a conversão. Esta propriedade informa ao código personalizado de qual página do PDF original foi criada a marcação HTML salva. Se o número da página original por algum motivo for desconhecido ou SplitOnPages=false, então esta propriedade sempre contém '0', o que sinaliza que o conversor não pode fornecer o número exato da página original do PDF para o arquivo de marcação HTML fornecido. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Definido pelo conversor. Nome de arquivo suposto que vai do conversor para o código do método personalizado. Pode ser usado no código personalizado para decidir como processar ou onde salvar o conteúdo |

### Veja Também

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)