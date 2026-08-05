---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Opções de salvamento para exportação para o formato Excel"
type: docs
weight: 330
url: /pt/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Opções de salvamento para exportação para o formato Excel

O tipo ExcelSaveOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ExcelSaveOptions() | Inicializa uma nova instância da classe ExcelSaveOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação Save continua, porém o usuário também pode retornar Abort, caso em que a operação Save deve ser interrompida. |
| save_format | Formato de salvamento de dados. |
| close_response | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| extract_ocr_sublayer_only | Este atributo habilita a funcionalidade de extração de imagem ou texto <br/>            para documentos PDF com subcamada OCR. |
| try_merge_adjacent_same_background_images | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela)<br/>              construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.<br/>              Nesses casos, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram<br/>              limites visíveis entre partes das imagens de fundo,<br/>              pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes das do Acrobat Reader.<br/>               Se parecer que o documento exportado contém tais limites visíveis entre <br/>              partes das mesmas imagens de fundo, por favor, tente usar esta configuração para se livrar <br/>              desse efeito indesejado. <br/>                ATENÇÃO! Esta otimização de qualidade geralmente desacelera significativamente a conversão,<br/>              portanto, por favor, use esta opção somente quando for realmente necessária. |
| minimize_the_number_of_worksheets | Defina como true se precisar minimizar o número de planilhas no workbook resultante.<br/>            O valor padrão é false; isso significa salvar cada página PDF como uma planilha separada. |
| insert_blank_column_at_first | Defina como true se precisar inserir uma coluna em branco como a primeira coluna da planilha.<br/>            O valor padrão é false; isso significa que a coluna em branco não será inserida. |
| uniform_worksheets | Defina como true para usar divisão uniforme de colunas ao longo do documento. <br/>            O valor padrão é false; isso significa que a divisão de colunas será independente para cada página. |
| format | Formato de saída |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

