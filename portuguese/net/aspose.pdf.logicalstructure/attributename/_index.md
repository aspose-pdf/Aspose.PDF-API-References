---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.AttributeName. Representa a classe para Valores de Nome de Atributo
type: docs
weight: 6220
url: /pt/net/aspose.pdf.logicalstructure/attributename/
---
## Classe AttributeName

Representa a classe para Valores de Nome de Atributo.

```csharp
public sealed class AttributeName
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Obtém a chave do atributo. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Obtém o valor do nome do atributo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Obtém o nome do atributo para a chave do atributo. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Retorna uma string que representa o objeto atual. |

## Campos

| Nome | Descrição |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Atributo BlockAlign: After - Borda após o retângulo de alocação do último filho alinhada com a do retângulo de conteúdo da célula da tabela. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Atributo BlockAlign: Before - Borda antes do retângulo de alocação do primeiro filho alinhada com a do retângulo de conteúdo da célula da tabela. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Atributo BlockAlign: Justify - Filhos alinhados com as bordas antes e depois do retângulo de conteúdo da célula da tabela. O primeiro filho deve ser colocado conforme descrito para Before e o último filho conforme descrito para After, com espaçamento igual entre os filhos. Se houver apenas um filho, ele deve ser alinhado apenas com a borda antes, como para Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Atributo BlockAlign: Middle - Filhos centralizados dentro da célula da tabela. A distância entre a borda antes do retângulo de alocação do primeiro filho e a do retângulo de conteúdo da célula da tabela deve ser a mesma que a distância entre a borda depois do retângulo de alocação do último filho e a do retângulo de conteúdo da célula da tabela. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Atributo BorderStyle: Dashed - A borda é uma série de segmentos de linha curtos. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Atributo BorderStyle: Dotted - A borda é uma série de pontos. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Atributo BorderStyle: Double - A borda é duas linhas sólidas. A soma das duas linhas e o espaço entre elas é igual ao valor de BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Atributo BorderStyle: Groove - A borda parece estar esculpida na tela. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Atributo BorderStyle: Hidden - Igual a None, exceto em termos de resolução de conflitos de borda para elementos de tabela. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Atributo BorderStyle: Inset - A borda faz com que toda a caixa pareça estar embutida na tela. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Atributo BorderStyle: None - Sem borda. Força o valor computado de BorderThickness a ser 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Atributo BorderStyle: Outset - A borda faz com que toda a caixa pareça estar saindo da tela (o oposto de Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Atributo BorderStyle: Ridge - A borda parece estar saindo da tela (o oposto de Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Atributo BorderStyle: Solid - A borda é um único segmento de linha. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Atributo checked: Neutral - O estado de um campo de botão de opção ou caixa de seleção. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Atributo checked: Off - O estado de um campo de botão de opção ou caixa de seleção. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Atributo checked: On - O estado de um campo de botão de opção ou caixa de seleção. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Atributo GlyphOrientationVertical: Auto - Especifica uma orientação padrão para o texto, dependendo de ser de largura total (tão largo quanto alto). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Atributo Height: Auto - A altura do elemento será determinada pela altura intrínseca de seu conteúdo. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Atributo InlineAlign: Center - Cada filho centralizado dentro da célula da tabela. A distância entre as bordas iniciais do retângulo de alocação do filho e o retângulo de conteúdo da célula da tabela deve ser a mesma que a distância entre suas bordas finais. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Atributo InlineAlign: End - Borda final de cada retângulo de alocação do filho alinhada com a do retângulo de conteúdo da célula da tabela. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Atributo InlineAlign: Start - Borda inicial de cada retângulo de alocação do filho alinhada com a do retângulo de conteúdo da célula da tabela. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Atributo LineHeight: Auto - Ajuste para o valor de BaselineShift não será feito. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Atributo LineHeight: Normal - Ajusta a altura da linha para incluir qualquer valor diferente de zero especificado para BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Atributo ListNumbering: Circle - Marcador circular aberto. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Atributo ListNumbering: Decimal - Números arábicos decimais (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Atributo ListNumbering: Disc - Marcador circular sólido. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Atributo ListNumbering: LowerRoman - Números romanos minúsculos (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Atributo ListNumbering: None - Sem numeração automática; elementos Lbl (se presentes) contêm texto arbitrário não sujeito a nenhum esquema de numeração. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Atributo ListNumbering: Square - Marcador quadrado sólido. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Atributo ListNumbering: UpperAlpha - Letras maiúsculas (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Atributo ListNumbering: UpperRoman - Números romanos maiúsculos (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Atributo Placement: Before - Colocado de forma que a borda antes do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Atributo Placement: Block - Empilhado na direção de progressão do bloco dentro de uma área de referência ou BLSE pai. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Atributo Placement: End - Colocado de forma que a borda final do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Atributo Placement: Inline - Compactado na direção de progressão inline dentro de um BLSE envolvente. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Atributo Placement: Start - Colocado de forma que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Atributo Role: cb - Caixa de seleção. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Atributo Role: pb - Botão de pressão. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Atributo Role: rb - Botão de opção. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Atributo Role: tv - Campo de texto-valor. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Atributo RubyAlign: Center - O conteúdo deve ser centralizado na direção de progressão inline. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Atributo RubyAlign: Distribute - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline. No entanto, espaço também deve ser inserido na borda inicial e na borda final do texto. O espaçamento deve ser distribuído usando uma proporção de 1:2:1 (início:infix:fim). Deve ser alterado para uma proporção de 0:1:1 se o ruby aparecer no início de uma linha de texto ou para uma proporção de 1:1:0 se o ruby aparecer no final da linha de texto. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Atributo RubyAlign: End - O conteúdo deve ser alinhado na borda final na direção de progressão inline. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Atributo RubyAlign: Justify - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Atributo RubyAlign: Start - O conteúdo deve ser alinhado na borda inicial na direção de progressão inline. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Atributo RubyPosition: After - O conteúdo RT deve ser alinhado ao longo da borda após do elemento. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Atributo RubyPosition: Before - O conteúdo RT deve ser alinhado ao longo da borda antes do elemento. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Atributo RubyPosition: Inline - Os elementos RT e RP associados devem ser formatados como um comentário entre parênteses, seguindo o elemento RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Atributo RubyPosition: Warichu - Os elementos RT e RP associados devem ser formatados como um warichu, seguindo o elemento RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Atributo Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Atributo Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Atributo Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Atributo TextAlign: Center - Centralizado entre as bordas inicial e final. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Atributo TextAlign: End - Alinhado com a borda final. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Atributo TextAlign: Justify - Alinhado com as bordas inicial e final, com espaçamento interno dentro de cada linha expandido, se necessário, para alcançar tal alinhamento. A última (ou única) linha deve ser alinhada apenas com a borda inicial. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Atributo TextAlign: Start - Alinhado com a borda inicial. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Atributo TextDecorationType: LineThrough - Uma linha através do meio do texto. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Atributo TextDecorationType: None - Sem decoração de texto. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Atributo TextDecorationType: Overline - Uma linha acima do texto. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Atributo TextDecorationType: Underline - Uma linha abaixo do texto. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Atributo Width: Auto - A largura do elemento será determinada pela largura intrínseca de seu conteúdo. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Atributo WritingMode: LrTb - Progressão inline da esquerda para a direita; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita ocidentais. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Atributo WritingMode: RlTb - Progressão inline da direita para a esquerda; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita árabe e hebraico. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Atributo WritingMode: TbRl - Progressão inline de cima para baixo; progressão de bloco da direita para a esquerda. Este é o modo de escrita típico para sistemas de escrita chinesa e japonesa. |

### Veja Também

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)