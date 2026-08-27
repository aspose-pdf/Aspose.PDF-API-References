---
title: "SvgSaveOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Opções de salvamento para exportação para o formato SVG"
type: docs
weight: 1460
url: /pt/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Opções de salvamento para exportação para o formato SVG

O tipo SvgSaveOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| SvgSaveOptions() | Inicializa uma nova instância da classe SvgSaveOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação Save continua, porém o usuário também pode retornar Abort, caso em que a operação Save deve ser interrompida. |
| save_format | Formato de salvamento de dados. |
| close_response | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| extract_ocr_sublayer_only | Nenhum |
| try_merge_adjacent_same_background_images | Nenhum |
| treat_target_file_name_as_directory | Esta opção define se será criado o diretório de destino<br/>             (se ainda não existir) com o mesmo nome do arquivo de saída solicitado <br/>             em vez do próprio arquivo de saída.<br/>             Assim, esse diretório conterá todas as imagens SVG de saída das páginas (conforme descrito abaixo).<br/>               Caso contrário, os arquivos de saída das páginas, exceto a primeira, serão criados exatamente no diretório solicitado<br/>            como arquivo de saída principal, mas conterão no nome do arquivo o sufixo _[2...n], que<br/>             é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\\AsposeTests\\output.svg"<br/>             e a saída contiver vários arquivos svg das páginas,<br/>             então os arquivos das páginas também serão criados no diretório "C:\\AsposeTests\\" e terão nomes 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| compress_output_to_zip_archive | Especifica se a saída será criada como um único arquivo zip.<br/>             Consulte o comentário das opções 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura<br/>             dos arquivos svg das páginas para documento de origem multipágina, que também são aplicadas ao conjunto zipado de arquivos de saída. |
| scale_to_pixels | Especifica se o documento de saída deve ser escalado de pontos tipográficos para pixels. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

