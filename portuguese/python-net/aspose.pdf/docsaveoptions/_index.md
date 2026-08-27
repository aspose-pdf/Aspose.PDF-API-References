---
title: "DocSaveOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Opções de salvamento para exportação para o formato Doc"
type: docs
weight: 220
url: /pt/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Opções de salvamento para exportação para o formato Doc

O tipo DocSaveOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| DocSaveOptions() | Inicializa uma nova instância da classe DocSaveOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| warning_handler | Retorno de chamada para lidar com quaisquer avisos gerados. <br/>            O WarningHandler retorna o item enum ReturnAction especificando Continue ou Abort. <br/>            Continue é a ação padrão e a operação Save continua, porém o usuário também pode retornar Abort, caso em que a operação Save deve ser interrompida. |
| save_format | Formato de salvamento de dados. |
| close_response | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| extract_ocr_sublayer_only | Este atributo habilita a funcionalidade de extração de imagem ou texto <br/>            para documentos PDF com subcamada OCR. |
| try_merge_adjacent_same_background_images | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela)<br/>              construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.<br/>              Nesses casos, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram<br/>              limites visíveis entre partes das imagens de fundo,<br/>              pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes das do Acrobat Reader.<br/>               Se parecer que o documento exportado contém tais limites visíveis entre <br/>              partes das mesmas imagens de fundo, por favor, tente usar esta configuração para se livrar <br/>              desse efeito indesejado. <br/>                ATENÇÃO! Esta otimização de qualidade geralmente desacelera significativamente a conversão,<br/>              portanto, por favor, use esta opção somente quando for realmente necessária. |
| mode | Modo de reconhecimento. |
| relative_horizontal_proximity | No PDF, as palavras podem ser representadas internamente com operadores que imprimem palavras<br/>              imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras às vezes precisamos detectar grupos<br/>              de caracteres independentes que na verdade são palavras.<br/>                Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) <br/>              que deve ser tratada como distância entre palavras durante o reconhecimento de palavras no PDF de origem.<br/>              (a presença de espaço vazio com pelo menos essa largura entre letras indica que <br/>               os elementos textuais pertencem a palavras diferentes).<br/>              É normalizada ao tamanho da fonte - 1.0 significa 100% do tamanho de fonte presumido da palavra.<br/>             ATENÇÃO! É usada apenas nos casos em que o PDF de origem contém fontes específicas raramente usadas<br/>             para as quais o valor ideal não pode ser calculado a partir da fonte. <br/>               Assim, na grande maioria dos casos este parâmetro não altera nada no documento resultante. |
| max_distance_between_text_lines | Este parâmetro é usado para agrupar linhas de texto em parágrafos.<br/>            Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de por cento da altura das linhas de texto. |
| recognize_bullets | Ativar o reconhecimento de marcadores |
| add_return_to_line_end | Usar quebras de parágrafo ou de linha |
| image_resolution_x | Resolução X das imagens convertidas. |
| image_resolution_y | Resolução Y das imagens convertidas. |
| format | Formato de saída |
| batch_size | Define o tamanho do lote se a conversão em lote for aplicável<br/>            ao par de formatos de origem e destino. |
| memory_save_mode_path | Define o caminho (nome do arquivo ou nome do diretório) para armazenar<br/>            dados temporários ao converter no modo de salvamento em memória. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

