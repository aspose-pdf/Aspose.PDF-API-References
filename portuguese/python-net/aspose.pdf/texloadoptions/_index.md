---
title: "TeXLoadOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa opções para carregar/importar arquivo TeX em documento PDF."
type: docs
weight: 1520
url: /pt/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

Representa opções para carregar/importar arquivo TeX em documento PDF.

O tipo TeXLoadOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TeXLoadOptions() | Inicializa uma nova instância da classe TeXLoadOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação de Load continua, porém o usuário também pode retornar Abort, caso em que a operação de Load deve ser interrompida. |
| load_format | Representa o formato de arquivo que [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) descreve. |
| job_name | Obtém/define o nome do trabalho. |
| input_directory | Obtém/define o diretório de entrada do TeX. |
| output_directory | Obtém/define o diretório de saída do TeX. |
| repeat | Obtém/define o sinalizador que indica se é necessário executar o trabalho TeX duas vezes, caso,<br/>            por exemplo, existam referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando<br/>            o motor coleta alguns dados durante o processo de composição e os armazena em um arquivo auxiliar,<br/>            tudo na primeira execução. E na segunda execução, o motor de alguma forma utiliza esses dados. |
| subset_fonts | Obtém/define o sinalizador que indica se deve subdefinir fontes no arquivo de saída ou não. |
| show_terminal_output | Obtém/define o sinalizador que indica se deve mostrar a saída do terminal no console. |
| date_time | Obtém/define um determinado valor para primitivas de data/hora como \year, \month, \day e \time. |
| no_ligatures | Obtém/define um sinalizador que cancela ligaduras em todas as fontes. |
| rasterize_formulas | Obtém/define um sinalizador que permite rasterizar fórmulas matemáticas. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

