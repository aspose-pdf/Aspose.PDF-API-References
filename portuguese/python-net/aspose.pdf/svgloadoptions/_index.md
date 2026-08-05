---
title: "SvgLoadOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa opções para carregar/importar arquivo SVG em documento pdf."
type: docs
weight: 1450
url: /pt/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Representa opções para carregar/importar arquivo SVG em documento pdf.

O tipo SvgLoadOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| SvgLoadOptions() | Inicializa uma nova instância da classe SvgLoadOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação de Load continua, porém o usuário também pode retornar Abort, caso em que a operação de Load deve ser interrompida. |
| load_format | Representa o formato de arquivo que [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descreve. |
| page_info | Obtém ou define informações da página que devem ser aplicadas durante o carregamento do documento.<br/>            NOTA que este parâmetro funciona somente quando ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Ajusta o tamanho da página pdf ao tamanho do svg |
| conversion_engine | Permite selecionar o mecanismo de conversão que será usado durante a conversão.<br/>            Atualmente o novo mecanismo está em fase de B-testing, portanto este valor por padrão é definido como <br/>            ConversionEngines.LegacyEngine |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

