---
title: "EpubLoadOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Contém opções para carregar/importar arquivo EPUB no documento PDF."
type: docs
weight: 310
url: /pt/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Contém opções para carregar/importar arquivo EPUB no documento PDF.

O tipo EpubLoadOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| EpubLoadOptions() | Cria opções de carregamento padrão para converter arquivo EPUB em documento PDF. <br/>            Tamanho de página PDF padrão - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Inicializa uma nova instância da classe EpubLoadOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação de Load continua, porém o usuário também pode retornar Abort, caso em que a operação de Load deve ser interrompida. |
| load_format | Representa o formato de arquivo que [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descreve. |
| page_size | Obtém ou define o tamanho da página de saída para importação. |
| margem | Obtém referência ao objeto que representa informações de margem. |
| margins_area_usage_mode | Representa o modo de uso da área de margens - define o tratamento <br/>              das instruções (se houver) de CSS do documento importado<br/>              relacionadas ao uso de margens. |
| page_size_adjustment_mode | ATENÇÃO! O recurso foi implementado, mas ainda não foi disponibilizado na API pública devido a um problema bloqueador na <br/>              camada OSHARED revelado para documento de exemplo.<br/>              <br/>             <br/>              Representa o modo de uso do tamanho da página durante a conversão.<br/>             Formatos (como HTML, EPUB etc.) geralmente têm layout fluido, portanto, permitem ajustar o tamanho da página necessário<br/>             . Mas às vezes o conteúdo tem posições horizontais ou tamanho especificados que <br/>             não permitem colocar o conteúdo no tamanho de página requerido.<br/>               Nesse caso podemos definir o que deve ser feito (ou seja, quando o tamanho do conteúdo não cabe <br/>             no tamanho de página inicial requerido do documento PDF resultante). |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

