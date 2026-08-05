---
title: "XslFoLoadOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa opções para carregar/importar arquivo XSL-FO em documento PDF."
type: docs
weight: 1820
url: /pt/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

Representa opções para carregar/importar arquivo XSL-FO em documento PDF.

O tipo XslFoLoadOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| XslFoLoadOptions() | Cria o objeto [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) sem dados xsl. |
| XslFoLoadOptions(xsl_file) | Inicializa uma nova instância da classe XslFoLoadOptions |
| XslFoLoadOptions(xsl_stream) | Inicializa uma nova instância da classe XslFoLoadOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação de Load continua, porém o usuário também pode retornar Abort, caso em que a operação de Load deve ser interrompida. |
| load_format | Representa o formato de arquivo que [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descreve. |
| xsl_stream | Obtém os dados xsl para converter xml em documento pdf. |
| base_path | O caminho/base URL a partir do qual são pesquisados caminhos relativos para recursos externos (se houver) referenciados no arquivo SVG carregado. |
| parsing_errors_handling_type | O documento XSLFO de origem pode conter erros de formatação. Este enum enumera possíveis estratégias de tratamento desses erros |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

