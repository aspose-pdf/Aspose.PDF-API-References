---
title: "AttributeName"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa a classe para valores de nomes de atributos."
type: docs
weight: 50
url: /pt/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Representa a classe para valores de nomes de atributos.

O tipo AttributeName expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| nome | Obtém o valor do nome do atributo. |
| attribute_key | Obtém a chave do atributo. |
| PLACEMENT_BLOCK | Posicionamento do Atributo: Block - Empilhado na direção de progressão de bloco dentro de uma área de referência envolvente ou BLSE pai. |
| PLACEMENT_INLINE | Posicionamento do Atributo: Inline - Compactado na direção de progressão em linha dentro de um BLSE envolvente. |
| PLACEMENT_BEFORE | Posicionamento do Atributo: Before - Posicionado de modo que a borda anterior do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| PLACEMENT_START | Posicionamento do Atributo: Start - Posicionado de modo que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| PLACEMENT_END | Posicionamento do Atributo: End - Posicionado de modo que a borda final do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| WRITING_MODE_LR_TB | Modo de Escrita do Atributo: LrTb - Progressão em linha da esquerda para a direita; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita ocidentais. |
| WRITING_MODE_RL_TB | Modo de Escrita do Atributo: RlTb - Progressão em linha da direita para a esquerda; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita árabe e hebraico. |
| WRITING_MODE_TB_RL | Modo de Escrita do Atributo: TbRl - Progressão em linha de cima para baixo; progressão de bloco da direita para a esquerda. Este é o modo de escrita típico para sistemas de escrita chineses e japoneses. |
| BORDER_STYLE_NONE | Estilo de Borda do Atributo: None - Sem borda. Força o valor calculado de BorderThicknessto a ser 0. |
| BORDER_STYLE_HIDDEN | Estilo de Borda do Atributo: Hidden - Igual a None, exceto em termos de resolução de conflitos de borda para elementos de tabela. |
| BORDER_STYLE_DOTTED | Estilo de Borda do Atributo: Dotted - A borda é uma série de pontos. |
| BORDER_STYLE_DASHED | Atributo BorderStyle: Tracejado - A borda é uma série de pequenos segmentos de linha. |
| BORDER_STYLE_SOLID | Atributo BorderStyle: Sólido - A borda é um único segmento de linha. |
| BORDER_STYLE_DOUBLE | Atributo BorderStyle: Duplo - A borda é composta por duas linhas sólidas. A soma das duas linhas e o espaço entre elas equivale ao valor de BorderThickness. |
| BORDER_STYLE_GROOVE | Atributo BorderStyle: Ranhura - A borda parece estar esculpida na tela. |
| BORDER_STYLE_RIDGE | Atributo BorderStyle: Elevação - A borda parece estar saindo da tela (o oposto de Ranhura). |
| BORDER_STYLE_INSET | Atributo BorderStyle: Inserido - A borda faz com que toda a caixa pareça estar embutida na tela. |
| BORDER_STYLE_OUTSET | Atributo BorderStyle: Proeminente - A borda faz com que toda a caixa pareça estar saindo da tela (o oposto de Inserido). |
| TEXT_ALIGN_START | Atributo TextAlign: Início - Alinhado com a borda inicial. |
| TEXT_ALIGN_CENTER | Atributo TextAlign: Centro - Centralizado entre as bordas inicial e final. |
| TEXT_ALIGN_END | Atributo TextAlign: Fim - Alinhado com a borda final. |
| TEXT_ALIGN_JUSTIFY | Atributo TextAlign: Justificar - Alinhado com as bordas inicial e final, com o espaçamento interno dentro de cada linha expandido, se necessário, para alcançar tal alinhamento. A última (ou única) linha deve ser alinhada apenas com a borda inicial. |
| WIDTH_AUTO | Atributo Width: Auto - a largura do elemento será determinada pela largura intrínseca de seu conteúdo. |
| HEIGHT_AUTO | Atributo Height: Auto - a altura do elemento será determinada pela altura intrínseca de seu conteúdo. |
| BLOCK_ALIGN_BEFORE | Atributo BlockAlign: Antes - A borda anterior do retângulo de alocação do primeiro filho alinhada com a do retângulo de conteúdo da célula da tabela. |
| BLOCK_ALIGN_MIDDLE | Atributo BlockAlign: Meio - Filhos centralizados dentro da célula da tabela. A distância entre a borda inicial do retângulo de alocação do primeiro filho e a da caixa de conteúdo da célula da tabela deve ser a mesma que a distância entre a borda final do retângulo de alocação do último filho e a da caixa de conteúdo da célula da tabela. |
| BLOCK_ALIGN_AFTER | Atributo BlockAlign: Depois - A borda final do retângulo de alocação do último filho alinhada com a da caixa de conteúdo da célula da tabela. |
| BLOCK_ALIGN_JUSTIFY | Atributo BlockAlign: Justificar - Filhos alinhados com as bordas inicial e final da caixa de conteúdo da célula da tabela. O primeiro filho deve ser posicionado como descrito para Antes e o último filho como descrito para Depois, com espaçamento igual entre os filhos. Se houver apenas um filho, ele deve ser alinhado apenas com a borda inicial, como em Antes. |
| INLINE_ALIGN_START | Atributo InlineAlign: Início - A borda inicial de cada retângulo de alocação do filho alinhada com a da caixa de conteúdo da célula da tabela. |
| INLINE_ALIGN_CENTER | Atributo InlineAlign: Centro - Cada filho centralizado dentro da célula da tabela. A distância entre as bordas iniciais do retângulo de alocação do filho e da caixa de conteúdo da célula da tabela deve ser a mesma que a distância entre suas bordas finais. |
| INLINE_ALIGN_END | Atributo InlineAlign: Fim - A borda final de cada retângulo de alocação do filho alinhada com a da caixa de conteúdo da célula da tabela. |
| LINE_HEIGHT_NORMAL | Atributo LineHeight: Normal - Ajustar a altura da linha para incluir qualquer valor diferente de zero especificado para BaselineShift. |
| LINE_HEIGHT_AUTO | Atributo LineHeight: Auto - Não será feita ajuste para o valor de BaselineShift. |
| TEXT_DECORATION_TYPE_NONE | Atributo TextDecorationType: Nenhum - Nenhuma decoração de texto. |
| TEXT_DECORATION_TYPE_UNDERLINE | Atributo TextDecorationType: Sublinhado - Uma linha abaixo do texto. |
| TEXT_DECORATION_TYPE_OVERLINE | Atributo TextDecorationType: Sobrelinha - Uma linha acima do texto. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Atributo TextDecorationType: Riscado - Uma linha atravessando o meio do texto. |
| RUBY_ALIGN_START | Atributo RubyAlign: Start - O conteúdo deve ser alinhado na borda inicial na direção de progressão em linha. |
| RUBY_ALIGN_CENTER | Atributo RubyAlign: Center - O conteúdo deve ser centralizado na direção de progressão em linha. |
| RUBY_ALIGN_END | Atributo RubyAlign: End - O conteúdo deve ser alinhado na borda final na direção de progressão em linha. |
| RUBY_ALIGN_JUSTIFY | Atributo RubyAlign: Justify - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão em linha. |
| RUBY_ALIGN_DISTRIBUTE | Atributo RubyAlign: Distribute - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão em linha. No entanto, espaço também deve ser inserido na borda inicial e na borda final do texto. O espaçamento deve ser distribuído usando uma proporção 1:2:1 (início:infixo:fim). Ela será alterada para uma proporção 0:1:1 se o ruby aparecer no início de uma linha de texto ou para 1:1:0 se o ruby aparecer no final da linha de texto. |
| RUBY_POSITION_BEFORE | Atributo RubyPosition: Before - O conteúdo RT deve ser alinhado ao longo da borda anterior do elemento. |
| RUBY_POSITION_AFTER | Atributo RubyPosition: After - O conteúdo RT deve ser alinhado ao longo da borda posterior do elemento. |
| RUBY_POSITION_WARICHU | Atributo RubyPosition: Warichu - Os elementos RT e RP associados devem ser formatados como um warichu, seguindo o elemento RB. |
| RUBY_POSITION_INLINE | Atributo RubyPosition: Inline - Os elementos RT e RP associados devem ser formatados como um comentário entre parênteses, seguindo o elemento RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Atributo GlyphOrientationVertical: Auto - Especifica uma orientação padrão para o texto, dependendo se ele é de largura total (tão largo quanto alto). |
| LIST_NUMBERING_NONE | Atributo ListNumbering: None - Sem numeração automática; elementos Lbl (se presentes) contêm texto arbitrário que não está sujeito a nenhum esquema de numeração. |
| LIST_NUMBERING_DISC | Atributo ListNumbering: Disc - Marcador circular sólido. |
| LIST_NUMBERING_CIRCLE | Atributo ListNumbering: Circle - Marcador circular aberto. |
| LIST_NUMBERING_SQUARE | Atributo ListNumbering: Square - Marcador quadrado sólido. |
| LIST_NUMBERING_DECIMAL | Atributo ListNumbering: Decimal - Numerais arábicos decimais (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Atributo ListNumbering: UpperRoman - Numerais romanos maiúsculos (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Atributo ListNumbering: LowerRoman - Numerais romanos minúsculos (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Atributo ListNumbering: UpperAlpha - Letras maiúsculas (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| ROLE_RB | Atributo Role: rb - Botão de opção. |
| ROLE_CB | Atributo Role: cb - Caixa de seleção. |
| ROLE_PB | Atributo Role: pb - Botão de pressão. |
| ROLE_TV | Atributo Role: tv - Campo de valor de texto. |
| CHECKED_ON | Atributo checked: On - O estado de um botão de opção ou caixa de seleção. |
| CHECKED_OFF | Atributo checked: Off - O estado de um botão de opção ou caixa de seleção. |
| CHECKED_NEUTRAL | Atributo verificado: Neutro - O estado de um botão de opção ou caixa de seleção. |
| SCOPE_ROW | Escopo do Atributo: Linha. |
| SCOPE_COLUMN | Escopo do Atributo: Coluna. |
| SCOPE_BOTH | Escopo do Atributo: Ambos. |
## Métodos
| Nome | Descrição |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Obtém o nome do atributo para a chave do atributo. |

### Veja Também

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

