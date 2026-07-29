---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe para valores de nomes de atributos."
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Representa a classe para valores de nomes de atributos.

## Campos

| Campo | Descrição |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Atributo BlockAlign: After - Borda after do retângulo de alocação do último filho alinhada com a da caixa de conteúdo da célula da tabela. |
| [BlockAlign_Before](#BlockAlign_Before) | Atributo BlockAlign: Before - Borda before do retângulo de alocação do primeiro filho alinhada com a da caixa de conteúdo da célula da tabela. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Atributo BlockAlign: Justify - Filhos alinhados com ambas as bordas before e after da caixa de conteúdo da célula da tabela. O primeiro filho deve ser colocado conforme descrito para Before e o último filho conforme descrito para After, com espaçamento igual entre os filhos. Se houver apenas um filho, ele deve ser alinhado somente com a borda before, como em Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Atributo BlockAlign: Middle- Filhos centralizados dentro da célula da tabela. A distância entre a borda before do retângulo de alocação do primeiro filho e a da caixa de conteúdo da célula da tabela deve ser a mesma que a distância entre a borda after do retângulo de alocação do último filho e a da caixa de conteúdo da célula da tabela. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Atributo BorderStyle: Dashed - A borda é uma série de pequenos segmentos de linha. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Atributo BorderStyle: Dotted - A borda é uma série de pontos. |
| [BorderStyle_Double](#BorderStyle_Double) | Atributo BorderStyle: Double - A borda consiste em duas linhas sólidas. A soma das duas linhas e o espaço entre elas equivale ao valor de BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Atributo BorderStyle: Groove - A borda parece estar esculpida na tela. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Atributo BorderStyle: Hidden - Igual a None, exceto em termos de resolução de conflitos de borda para elementos de tabela. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Atributo BorderStyle: Inset - A borda faz toda a caixa parecer embutida na tela. |
| [BorderStyle_None](#BorderStyle_None) | Atributo BorderStyle: None - Sem borda. Força o valor computado de BorderThickness a ser 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Atributo BorderStyle: Outset - A borda faz toda a caixa parecer sair da tela (o oposto de Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Atributo BorderStyle: Ridge - A borda parece estar saindo da tela (o oposto de Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Atributo BorderStyle: Solid - A borda é um único segmento de linha. |
| [Checked_neutral](#Checked_neutral) | Atributo checked: Neutral - O estado de um campo de botão de opção ou caixa de seleção. |
| [Checked_off](#Checked_off) | Atributo checked: Off - O estado de um campo de botão de opção ou caixa de seleção. |
| [Checked_on](#Checked_on) | Atributo checked: On - O estado de um campo de botão de opção ou caixa de seleção. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Atributo GlyphOrientationVertical: Auto - Especifica uma orientação padrão para o texto, dependendo de ele ser fullwidth (tão largo quanto alto). |
| [Height_Auto](#Height_Auto) | Atributo Height: Auto - A altura do elemento será determinada pela altura intrínseca de seu conteúdo. |
| [InlineAlign_Center](#InlineAlign_Center) | Atributo InlineAlign: Center - Cada filho centralizado dentro da célula da tabela. A distância entre as bordas iniciais do retângulo de alocação do filho e o retângulo de conteúdo da célula da tabela deve ser a mesma que a distância entre suas bordas finais. |
| [InlineAlign_End](#InlineAlign_End) | Atributo InlineAlign: End - A borda final do retângulo de alocação de cada filho alinhada com a da célula da tabela. |
| [InlineAlign_Start](#InlineAlign_Start) | Atributo InlineAlign: Start - A borda inicial do retângulo de alocação de cada filho alinhada com a da célula da tabela. |
| [LineHeight_Auto](#LineHeight_Auto) | Atributo LineHeight: Auto - Não será feita ajuste para o valor de BaselineShift. |
| [LineHeight_Normal](#LineHeight_Normal) | Atributo LineHeight: Normal - Ajusta a altura da linha para incluir qualquer valor diferente de zero especificado para BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Atributo ListNumbering: Circle - Marcador circular aberto. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Atributo ListNumbering: Decimal - Numerais arábicos decimais (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Atributo ListNumbering: Disc - Marcador circular sólido. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Atributo ListNumbering: LowerRoman - Numerais romanos minúsculos (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Atributo ListNumbering: None - Sem numeração automática; elementos Lbl (se presentes) contêm texto arbitrário que não está sujeito a nenhum esquema de numeração. |
| [ListNumbering_Square](#ListNumbering_Square) | Atributo ListNumbering: Square - Marcador quadrado sólido. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Atributo ListNumbering: UpperAlpha - Letras maiúsculas (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Atributo ListNumbering: UpperRoman - Numerais romanos maiúsculos (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Atributo Placement: Before - Posicionado de modo que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| [Placement_Block](#Placement_Block) | Atributo Placement: Block - Empilhado na direção de progressão de bloco dentro de uma área de referência que o contém ou BLSE pai. |
| [Placement_End](#Placement_End) | Atributo Placement: End - Posicionado de modo que a borda final do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| [Placement_Inline](#Placement_Inline) | Atributo Placement: Inline - Compactado na direção de progressão em linha dentro de um BLSE que o contém. |
| [Placement_Start](#Placement_Start) | Atributo Placement: Start - Posicionado de modo que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima. |
| [Role_cb](#Role_cb) | Atributo Role: cb - Caixa de seleção. |
| [Role_pb](#Role_pb) | Atributo Role: pb - Botão de pressão. |
| [Role_rb](#Role_rb) | Atributo Role: rb - Botão de opção. |
| [Role_tv](#Role_tv) | Atributo Role: tv - Campo de texto-valor. |
| [RubyAlign_Center](#RubyAlign_Center) | Atributo RubyAlign: Center - O conteúdo deve ser centralizado na direção de progressão inline. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Atributo RubyAlign: Distribute - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline. No entanto, espaço também deve ser inserido na borda inicial e na borda final do texto. O espaçamento deve ser distribuído usando uma proporção 1:2:1 (início:infixo:fim). Deve ser alterado para uma proporção 0:1:1 se o ruby aparecer no início de uma linha de texto ou para 1:1:0 se o ruby aparecer no final da linha de texto. |
| [RubyAlign_End](#RubyAlign_End) | Atributo RubyAlign: End - O conteúdo deve ser alinhado na borda final na direção de progressão inline. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Atributo RubyAlign: Justify - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline. |
| [RubyAlign_Start](#RubyAlign_Start) | Atributo RubyAlign: Start - O conteúdo deve ser alinhado na borda inicial na direção de progressão inline. |
| [RubyPosition_After](#RubyPosition_After) | Atributo RubyPosition: After - O conteúdo RT deve ser alinhado ao longo da borda posterior do elemento. |
| [RubyPosition_Before](#RubyPosition_Before) | Atributo RubyPosition: Before - O conteúdo RT deve ser alinhado ao longo da borda anterior do elemento. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Atributo RubyPosition: Inline - Os elementos RT e RP associados devem ser formatados como um comentário entre parênteses, seguindo o elemento RB. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Atributo RubyPosition: Warichu - Os elementos RT e RP associados devem ser formatados como um warichu, seguindo o elemento RB. |
| [Scope_Both](#Scope_Both) | Atributo Scope: Ambos. |
| [Scope_Column](#Scope_Column) | Atributo Scope: Coluna. |
| [Scope_Row](#Scope_Row) | Atributo Scope: Linha. |
| [TextAlign_Center](#TextAlign_Center) | Atributo TextAlign: Center - Centralizado entre as bordas inicial e final. |
| [TextAlign_End](#TextAlign_End) | Atributo TextAlign: End - Alinhado com a borda final. |
| [TextAlign_Justify](#TextAlign_Justify) | Atributo TextAlign: Justify - Alinhado com as bordas inicial e final, com o espaçamento interno dentro de cada linha expandido, se necessário, para alcançar esse alinhamento. A última linha (ou única) deve ser alinhada apenas com a borda inicial. |
| [TextAlign_Start](#TextAlign_Start) | Atributo TextAlign: Start - Alinhado com a borda inicial. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Atributo TextDecorationType: LineThrough - Uma linha atravessando o meio do texto. |
| [TextDecorationType_None](#TextDecorationType_None) | Atributo TextDecorationType: None - Nenhuma decoração de texto. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Atributo TextDecorationType: Overline - Uma linha acima do texto. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Atributo TextDecorationType: Underline - Uma linha abaixo do texto. |
| [Width_Auto](#Width_Auto) | Atributo Width: Auto - a largura do elemento deve ser determinada pela largura intrínseca do seu conteúdo. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Atributo WritingMode: LrTb - Progressão inline da esquerda para a direita; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita ocidentais. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Atributo WritingMode: RlTb - Progressão inline da direita para a esquerda; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita árabe e hebraico. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Atributo WritingMode: TbRl - Progresso em linha de cima para baixo; progresso de bloco da direita para a esquerda. Este é o modo de escrita típico para os sistemas de escrita chineses e japoneses. |

## Métodos

| Método | Descrição |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Obtém o nome do atributo para a chave do atributo. |
| [getAttributeKey](#getAttributeKey--) | Obtém a chave do atributo. |
| [getName](#getName--) | Obtém o valor do nome do atributo. |
| [toString](#toString--) | Retorna uma string que representa o objeto atual. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Atributo BlockAlign: After - Borda after do retângulo de alocação do último filho alinhada com a da caixa de conteúdo da célula da tabela.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Atributo BlockAlign: Before - Borda before do retângulo de alocação do primeiro filho alinhada com a da caixa de conteúdo da célula da tabela.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Atributo BlockAlign: Justify - Filhos alinhados com ambas as bordas before e after da caixa de conteúdo da célula da tabela. O primeiro filho deve ser colocado conforme descrito para Before e o último filho conforme descrito para After, com espaçamento igual entre os filhos. Se houver apenas um filho, ele deve ser alinhado somente com a borda before, como em Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Atributo BlockAlign: Middle- Filhos centralizados dentro da célula da tabela. A distância entre a borda before do retângulo de alocação do primeiro filho e a da caixa de conteúdo da célula da tabela deve ser a mesma que a distância entre a borda after do retângulo de alocação do último filho e a da caixa de conteúdo da célula da tabela.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Atributo BorderStyle: Dashed - A borda é uma série de pequenos segmentos de linha.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Atributo BorderStyle: Dotted - A borda é uma série de pontos.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Atributo BorderStyle: Double - A borda consiste em duas linhas sólidas. A soma das duas linhas e o espaço entre elas equivale ao valor de BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Atributo BorderStyle: Groove - A borda parece estar esculpida na tela.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Atributo BorderStyle: Hidden - Igual a None, exceto em termos de resolução de conflitos de borda para elementos de tabela.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Atributo BorderStyle: Inset - A borda faz toda a caixa parecer embutida na tela.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Atributo BorderStyle: None - Sem borda. Força o valor computado de BorderThickness a ser 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Atributo BorderStyle: Outset - A borda faz toda a caixa parecer sair da tela (o oposto de Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Atributo BorderStyle: Ridge - A borda parece estar saindo da tela (o oposto de Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Atributo BorderStyle: Solid - A borda é um único segmento de linha.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Atributo checked: Neutral - O estado de um campo de botão de opção ou caixa de seleção.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Atributo checked: Off - O estado de um campo de botão de opção ou caixa de seleção.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Atributo checked: On - O estado de um campo de botão de opção ou caixa de seleção.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Atributo GlyphOrientationVertical: Auto - Especifica uma orientação padrão para o texto, dependendo de ele ser fullwidth (tão largo quanto alto).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Atributo Height: Auto - A altura do elemento será determinada pela altura intrínseca de seu conteúdo.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Atributo InlineAlign: Center - Cada filho centralizado dentro da célula da tabela. A distância entre as bordas iniciais do retângulo de alocação do filho e o retângulo de conteúdo da célula da tabela deve ser a mesma que a distância entre suas bordas finais.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Atributo InlineAlign: End - A borda final do retângulo de alocação de cada filho alinhada com a da célula da tabela.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Atributo InlineAlign: Start - A borda inicial do retângulo de alocação de cada filho alinhada com a da célula da tabela.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Atributo LineHeight: Auto - Não será feita ajuste para o valor de BaselineShift.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Atributo LineHeight: Normal - Ajusta a altura da linha para incluir qualquer valor diferente de zero especificado para BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Atributo ListNumbering: Circle - Marcador circular aberto.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Atributo ListNumbering: Decimal - Numerais arábicos decimais (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Atributo ListNumbering: Disc - Marcador circular sólido.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Atributo ListNumbering: LowerAlpha - Letras minúsculas (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Atributo ListNumbering: LowerRoman - Numerais romanos minúsculos (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Atributo ListNumbering: None - Sem numeração automática; elementos Lbl (se presentes) contêm texto arbitrário que não está sujeito a nenhum esquema de numeração.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Atributo ListNumbering: Square - Marcador quadrado sólido.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Atributo ListNumbering: UpperAlpha - Letras maiúsculas (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Atributo ListNumbering: UpperRoman - Numerais romanos maiúsculos (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Atributo Placement: Before - Posicionado de modo que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Atributo Placement: Block - Empilhado na direção de progressão de bloco dentro de uma área de referência que o contém ou BLSE pai.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Atributo Placement: End - Posicionado de modo que a borda final do retângulo de alocação do elemento coincida com a da área de referência mais próxima.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Atributo Placement: Inline - Compactado na direção de progressão em linha dentro de um BLSE que o contém.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Atributo Placement: Start - Posicionado de modo que a borda inicial do retângulo de alocação do elemento coincida com a da área de referência mais próxima.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Atributo Role: cb - Caixa de seleção.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Atributo Role: pb - Botão de pressão.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Atributo Role: rb - Botão de opção.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Atributo Role: tv - Campo de texto-valor.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Atributo RubyAlign: Center - O conteúdo deve ser centralizado na direção de progressão inline.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Atributo RubyAlign: Distribute - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline. No entanto, espaço também deve ser inserido na borda inicial e na borda final do texto. O espaçamento deve ser distribuído usando uma proporção 1:2:1 (início:infixo:fim). Deve ser alterado para uma proporção 0:1:1 se o ruby aparecer no início de uma linha de texto ou para 1:1:0 se o ruby aparecer no final da linha de texto.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Atributo RubyAlign: End - O conteúdo deve ser alinhado na borda final na direção de progressão inline.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Atributo RubyAlign: Justify - O conteúdo deve ser expandido para preencher a largura disponível na direção de progressão inline.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Atributo RubyAlign: Start - O conteúdo deve ser alinhado na borda inicial na direção de progressão inline.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Atributo RubyPosition: After - O conteúdo RT deve ser alinhado ao longo da borda posterior do elemento.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Atributo RubyPosition: Before - O conteúdo RT deve ser alinhado ao longo da borda anterior do elemento.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Atributo RubyPosition: Inline - Os elementos RT e RP associados devem ser formatados como um comentário entre parênteses, seguindo o elemento RB.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Atributo RubyPosition: Warichu - Os elementos RT e RP associados devem ser formatados como um warichu, seguindo o elemento RB.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Atributo Scope: Ambos.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Atributo Scope: Coluna.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Atributo Scope: Linha.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Atributo TextAlign: Center - Centralizado entre as bordas inicial e final.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Atributo TextAlign: End - Alinhado com a borda final.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Atributo TextAlign: Justify - Alinhado com as bordas inicial e final, com o espaçamento interno dentro de cada linha expandido, se necessário, para alcançar esse alinhamento. A última linha (ou única) deve ser alinhada apenas com a borda inicial.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Atributo TextAlign: Start - Alinhado com a borda inicial.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Atributo TextDecorationType: LineThrough - Uma linha atravessando o meio do texto.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Atributo TextDecorationType: None - Nenhuma decoração de texto.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Atributo TextDecorationType: Overline - Uma linha acima do texto.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Atributo TextDecorationType: Underline - Uma linha abaixo do texto.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Atributo Width: Auto - a largura do elemento deve ser determinada pela largura intrínseca do seu conteúdo.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Atributo WritingMode: LrTb - Progressão inline da esquerda para a direita; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita ocidentais.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Atributo WritingMode: RlTb - Progressão inline da direita para a esquerda; progressão de bloco de cima para baixo. Este é o modo de escrita típico para sistemas de escrita árabe e hebraico.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Atributo WritingMode: TbRl - Progresso em linha de cima para baixo; progresso de bloco da direita para a esquerda. Este é o modo de escrita típico para os sistemas de escrita chineses e japoneses.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Obtém o nome do atributo para a chave do atributo.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Obtém a chave do atributo.

**Returns:**
Instância de AttributeKey

### getName {#getName--}
```
public final String getName()
```

Obtém o valor do nome do atributo.

**Returns:**
valor String

### toString {#toString--}
```
public String toString()
```

Retorna uma string que representa o objeto atual.

**Returns:**
String que representa o objeto atual.
