---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa tipos de estrutura padrão."
type: docs
weight: 130
url: /pt/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Representa tipos de estrutura padrão.

## Campos

| Campo | Descrição |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) Uma associação entre uma parte do conteúdo do ILSE e uma anotação PDF correspondente. Annot deve ser usado para todas as anotações PDF, exceto anotações de link e anotações de widget. |
| [Art](#Art) | (Article) Um corpo de texto relativamente autocontido que constitui uma única narrativa ou exposição. Os artigos devem ser disjuntos; isto é, não devem conter outros artigos como elementos constituintes. |
| [BibEntry](#BibEntry) | (Bibliography entry) Uma referência que identifica a fonte externa de algum conteúdo citado. Pode conter um rótulo (tipo de estrutura Lbl) como filho. Embora uma entrada de bibliografia provavelmente inclua partes componentes que identificam o autor, obra, editora, etc., do conteúdo citado, nenhum tipo de estrutura padrão é definido neste nível de detalhe. |
| [BlockQuote](#BlockQuote) | (Block quotation) Uma porção de texto composta por um ou mais parágrafos atribuídos a alguém que não o autor do texto circundante. |
| [Caption](#Caption) | (Caption) Uma breve porção de texto que descreve uma tabela ou figura. |
| [Code](#Code) | (Code) Um fragmento de texto de programa de computador. |
| [Div](#Div) | (Division) Um elemento genérico de nível de bloco ou um grupo de elementos. |
| [Document](#Document) | (Document) Um documento completo. Este é o elemento raiz de qualquer árvore de estrutura que contenha múltiplas partes ou múltiplos artigos. |
| [Figure](#Figure) | (Figure) Um item de conteúdo gráfico. Seu posicionamento pode ser especificado com o atributo de layout Placement. |
| [Form](#Form) | (Form) Uma anotação de widget que representa um campo de formulário interativo. |
| [Formula](#Formula) | (Formula) Uma fórmula matemática. Este tipo de estrutura é útil apenas para identificar um elemento de conteúdo inteiro como uma fórmula. Nenhum tipo de estrutura padrão é definido para identificar componentes individuais dentro da fórmula. Do ponto de vista de formatação, a fórmula deve ser tratada de forma semelhante a uma figura (tipo de estrutura Figure). |
| [H](#H) | (Heading) Um rótulo para uma subdivisão do conteúdo de um documento. Deve ser o primeiro filho da divisão que ele cabeça. |
| [H1](#H1) | Título de Nível 1, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento. |
| [H2](#H2) | Título de Nível 2, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento. |
| [H3](#H3) | Título de Nível 3, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento. |
| [H4](#H4) | Título de Nível 4, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento. |
| [H5](#H5) | Título de Nível 5, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento. |
| [H6](#H6) | Título de Nível 6, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| [Index](#Index) | (Índice) Uma sequência de entradas contendo texto identificador acompanhado por elementos de referência que apontam ocorrências do texto especificado no corpo principal de um documento. |
| [L](#L) | (Lista) Uma sequência de itens de significado e importância semelhantes. Seus filhos imediatos devem ser uma legenda opcional (tipo de estrutura Caption) seguida por um ou mais itens de lista (tipo de estrutura LI). |
| [Lbl](#Lbl) | (Rótulo) Um nome ou número que distingue um determinado item dos demais na mesma lista ou em outro grupo de itens semelhantes. |
| [LBody](#LBody) | (Corpo da lista) O conteúdo descritivo de um item de lista. Em uma lista de dicionário, por exemplo, contém a definição do termo. Pode conter o conteúdo diretamente ou ter outros BLSEs, talvez incluindo listas aninhadas, como filhos. |
| [LI](#LI) | (Item de lista) Um membro individual de uma lista. Seus filhos podem ser um ou mais rótulos, corpos de lista ou ambos (tipos de estrutura Lbl ou LBody). |
| [Link](#Link) | (Link) Uma associação entre uma parte do conteúdo do ILSE e uma anotação de link correspondente ou anotações. Seus filhos devem ser um ou mais itens de conteúdo ou ILSEs filhos e um ou mais referências de objeto que identificam as anotações de link associadas. |
| [NonStruct](#NonStruct) | (Elemento não estrutural) Um elemento de agrupamento que não possui significado estrutural inerente; serve apenas para fins de agrupamento. Este tipo de elemento difere de uma divisão (tipo de estrutura Div) pois não deve ser interpretado ou exportado para outros formatos de documento; porém, seus descendentes devem ser processados normalmente. |
| [Note](#Note) | (Nota) Um item de texto explicativo, como uma nota de rodapé ou uma nota final, que é referenciado a partir do corpo do documento. Pode ter um rótulo (tipo de estrutura Lbl) como filho. A nota pode ser incluída como filho do elemento estrutural no texto do corpo que a referencia, ou pode ser incluída em outro lugar (como em uma seção de notas finais) e acessada por meio de uma referência (tipo de estrutura Reference). O PDF marcado não prescreve a colocação das notas de rodapé na ordem de conteúdo da página. Elas podem estar inline ou ao final da página, a critério do escritor conforme. |
| [P](#P) | (Parágrafo) Uma divisão de texto de baixo nível. |
| [Part](#Part) | (Parte) Uma divisão de grande escala de um documento. Este tipo de elemento é adequado para agrupar artigos ou seções. |
| [Private](#Private) | (Elemento privado) Um elemento de agrupamento que contém conteúdo privado pertencente ao aplicativo que o produz. O significado estrutural deste tipo de elemento não está especificado e deve ser determinado inteiramente pelo escritor conforme. Nem o elemento Privado nem quaisquer de seus descendentes devem ser interpretados ou exportados para outros formatos de documento. |
| [Quote](#Quote) | (Citação) Uma porção de texto inline atribuída a alguém que não seja o autor do texto circundante. O texto citado deve estar contido inline dentro de um único parágrafo. Isso difere do elemento de nível de bloco BlockQuote, que consiste em um ou mais parágrafos completos (ou outros elementos apresentados como se fossem parágrafos completos). |
| [RB](#RB) | (Texto base Ruby) O texto em tamanho completo ao qual a anotação ruby é aplicada. RB pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter o atributo RubyAlign. |
| [Reference](#Reference) | (Referência) Uma citação a conteúdo em outra parte do documento. |
| [RP](#RP) | (Pontuação Ruby) Pontuação que envolve o texto da anotação ruby. É usada apenas quando uma anotação ruby não pode ser formatada adequadamente em estilo ruby e, em vez disso, é formatada como um comentário normal, ou quando é formatada como warichu. Contém texto (geralmente um único PARÊNTESE ESQUERDO ou DIREITO ou caractere de delimitação similar). |
| [RT](#RT) | (Texto da anotação Ruby) O texto em tamanho menor que deve ser colocado adjacente ao texto base Ruby. Pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter os atributos RubyAlign e RubyPosition. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Uma nota lateral (anotação) escrita em tamanho de texto menor e colocada adjacente ao texto base ao qual se refere. Um elemento Ruby também pode conter os elementos RB, RT e RP. (Ruby) O contêiner ao redor de toda a montagem ruby. Deve conter um elemento RB seguido por um elemento RT ou um grupo de três elementos consistindo em RP, RT e RP. Os elementos Ruby e seus elementos de conteúdo não devem ser quebrados em várias linhas. |
| [Sect](#Sect) | (Section) Um contêiner para agrupar elementos de conteúdo relacionados. |
| [Span](#Span) | (Span) Uma porção genérica inline de texto sem características inerentes específicas. Pode ser usada, por exemplo, para delimitar um intervalo de texto com um determinado conjunto de atributos de estilo. |
| [Table](#Table) | (Table) Um layout bidimensional de células de dados retangulares, possivelmente com uma subestrutura complexa. Contém uma ou mais linhas de tabela (tipo de estrutura TR) como filhos; ou um cabeçalho de tabela opcional (tipo de estrutura THead) seguido por uma ou mais elementos de corpo de tabela (tipo de estrutura TBody) e um rodapé de tabela opcional (tipo de estrutura TFoot). Além disso, uma tabela pode ter uma legenda (tipo de estrutura Caption) como seu primeiro ou último filho. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Um grupo de linhas que constituem a parte principal do corpo de uma tabela. Se a tabela for dividida em várias páginas, a área do corpo pode ser separada em um limite de linha. Uma tabela pode ter múltiplos elementos TBody para permitir o desenho de uma borda ou plano de fundo para um conjunto de linhas. |
| [TD](#TD) | (Table data cell) Uma célula de tabela contendo dados que fazem parte do conteúdo da tabela. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Um grupo de linhas que constituem o rodapé de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte inferior de cada fragmento da tabela (embora exista apenas um elemento TFoot.) |
| [TH](#TH) | (Table header cell) Uma célula de tabela contendo texto de cabeçalho que descreve uma ou mais linhas ou colunas da tabela. |
| [THead](#THead) | (Table header row group; PDF 1.5) Um grupo de linhas que constituem o cabeçalho de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte superior de cada fragmento da tabela (embora exista apenas um elemento THead). |
| [TOC](#TOC) | (Table of contents) Uma lista composta por entradas de itens de índice (tipo de estrutura TOCI) e/ou outras entradas de índice aninhadas (TOC). Uma entrada de TOC que inclui apenas entradas TOCI representa uma hierarquia plana. Uma entrada de TOC que inclui outras entradas TOC aninhadas (e possivelmente entradas TOCI) representa uma hierarquia mais complexa. Idealmente, a hierarquia de uma entrada TOC de nível superior reflete a estrutura do corpo principal do documento. |
| [TOCI](#TOCI) | (Table of contents item) Um membro individual de um índice. Os filhos desta entrada podem ser quaisquer dos seguintes tipos de estrutura: Lbl - Um rótulo Reference - Uma referência ao título e ao número da página NonStruct - Elementos não estruturados para envolver um artefato líder P - Texto descritivo TOC - Elementos de índice para índices hierárquicos, conforme descrito para a entrada TOC |
| [TR](#TR) | (Table row) Uma linha de cabeçalhos ou dados em uma tabela. Pode conter células de cabeçalho de tabela e células de dados de tabela (tipos de estrutura TH e TD). |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Um comentário ou anotação em tamanho de texto menor e formatado em duas linhas menores dentro da altura da linha de texto contendo e colocado após (inline) o texto base ao qual se refere. Um elemento Warichu também pode conter os elementos WT e WP. (Warichu) O contêiner ao redor de toda a montagem warichu. Pode conter um grupo de três elementos consistindo em WP, WT e WP. Os elementos Warichu (e seus elementos de conteúdo) podem envolver várias linhas, de acordo com as regras de quebra de warichu descritas na Norma Industrial Japonesa (JIS) X 4051-1995. |
| [WP](#WP) | (Warichu punctuation) A pontuação que envolve o texto WT. Contém texto (geralmente um único PARÊNTESE ESQUERDO ou DIREITO ou caractere de delimitação similar). De acordo com JIS X 4051-1995, os parênteses que cercam um warichu podem ser convertidos em um ESPAÇO (nominalmente 1/4 EM de largura) a critério do formatador. |
| [WT](#WT) | (Warichu text) O texto de tamanho menor de um comentário warichu que é formatado em duas linhas e colocado entre os elementos WP circundantes. |

## Métodos

| Método | Descrição |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Obtém a categoria do Tipo de Estrutura Padrão. |
| [getTag](#getTag--) | Obtém o nome da tag de {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Realiza uma conversão explícita de {@link String} para {@link StructureTypeStandard}. |
| [toString](#toString--) | Retorna uma string que representa o objeto atual. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) Uma associação entre uma parte do conteúdo do ILSE e uma anotação PDF correspondente. Annot deve ser usado para todas as anotações PDF, exceto anotações de link e anotações de widget.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) Um corpo de texto relativamente autocontido que constitui uma única narrativa ou exposição. Os artigos devem ser disjuntos; isto é, não devem conter outros artigos como elementos constituintes.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) Uma referência que identifica a fonte externa de algum conteúdo citado. Pode conter um rótulo (tipo de estrutura Lbl) como filho. Embora uma entrada de bibliografia provavelmente inclua partes componentes que identificam o autor, obra, editora, etc., do conteúdo citado, nenhum tipo de estrutura padrão é definido neste nível de detalhe.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) Uma porção de texto composta por um ou mais parágrafos atribuídos a alguém que não o autor do texto circundante.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) Uma breve porção de texto que descreve uma tabela ou figura.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Um fragmento de texto de programa de computador.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Um elemento genérico de nível de bloco ou um grupo de elementos.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Um documento completo. Este é o elemento raiz de qualquer árvore de estrutura que contenha múltiplas partes ou múltiplos artigos.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Um item de conteúdo gráfico. Seu posicionamento pode ser especificado com o atributo de layout Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Uma anotação de widget que representa um campo de formulário interativo.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Uma fórmula matemática. Este tipo de estrutura é útil apenas para identificar um elemento de conteúdo inteiro como uma fórmula. Nenhum tipo de estrutura padrão é definido para identificar componentes individuais dentro da fórmula. Do ponto de vista de formatação, a fórmula deve ser tratada de forma semelhante a uma figura (tipo de estrutura Figure).

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Um rótulo para uma subdivisão do conteúdo de um documento. Deve ser o primeiro filho da divisão que ele cabeça.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Título de Nível 1, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Título de Nível 2, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Título de Nível 3, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Título de Nível 4, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Título de Nível 5, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir de seu nível de aninhamento.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Título de Nível 6, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Índice) Uma sequência de entradas contendo texto identificador acompanhado por elementos de referência que apontam ocorrências do texto especificado no corpo principal de um documento.

### L {#L}
```
public static final StructureTypeStandard L
```

(Lista) Uma sequência de itens de significado e importância semelhantes. Seus filhos imediatos devem ser uma legenda opcional (tipo de estrutura Caption) seguida por um ou mais itens de lista (tipo de estrutura LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Rótulo) Um nome ou número que distingue um determinado item dos demais na mesma lista ou em outro grupo de itens semelhantes.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(Corpo da lista) O conteúdo descritivo de um item de lista. Em uma lista de dicionário, por exemplo, contém a definição do termo. Pode conter o conteúdo diretamente ou ter outros BLSEs, talvez incluindo listas aninhadas, como filhos.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(Item de lista) Um membro individual de uma lista. Seus filhos podem ser um ou mais rótulos, corpos de lista ou ambos (tipos de estrutura Lbl ou LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) Uma associação entre uma parte do conteúdo do ILSE e uma anotação de link correspondente ou anotações. Seus filhos devem ser um ou mais itens de conteúdo ou ILSEs filhos e um ou mais referências de objeto que identificam as anotações de link associadas.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Elemento não estrutural) Um elemento de agrupamento que não possui significado estrutural inerente; serve apenas para fins de agrupamento. Este tipo de elemento difere de uma divisão (tipo de estrutura Div) pois não deve ser interpretado ou exportado para outros formatos de documento; porém, seus descendentes devem ser processados normalmente.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Nota) Um item de texto explicativo, como uma nota de rodapé ou uma nota final, que é referenciado a partir do corpo do documento. Pode ter um rótulo (tipo de estrutura Lbl) como filho. A nota pode ser incluída como filho do elemento estrutural no texto do corpo que a referencia, ou pode ser incluída em outro lugar (como em uma seção de notas finais) e acessada por meio de uma referência (tipo de estrutura Reference). O PDF marcado não prescreve a colocação das notas de rodapé na ordem de conteúdo da página. Elas podem estar inline ou ao final da página, a critério do escritor conforme.

### P {#P}
```
public static final StructureTypeStandard P
```

(Parágrafo) Uma divisão de texto de baixo nível.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Parte) Uma divisão de grande escala de um documento. Este tipo de elemento é adequado para agrupar artigos ou seções.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Elemento privado) Um elemento de agrupamento que contém conteúdo privado pertencente ao aplicativo que o produz. O significado estrutural deste tipo de elemento não está especificado e deve ser determinado inteiramente pelo escritor conforme. Nem o elemento Privado nem quaisquer de seus descendentes devem ser interpretados ou exportados para outros formatos de documento.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Citação) Uma porção de texto inline atribuída a alguém que não seja o autor do texto circundante. O texto citado deve estar contido inline dentro de um único parágrafo. Isso difere do elemento de nível de bloco BlockQuote, que consiste em um ou mais parágrafos completos (ou outros elementos apresentados como se fossem parágrafos completos).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Texto base Ruby) O texto em tamanho completo ao qual a anotação ruby é aplicada. RB pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter o atributo RubyAlign.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Referência) Uma citação a conteúdo em outra parte do documento.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Pontuação Ruby) Pontuação que envolve o texto da anotação ruby. É usada apenas quando uma anotação ruby não pode ser formatada adequadamente em estilo ruby e, em vez disso, é formatada como um comentário normal, ou quando é formatada como warichu. Contém texto (geralmente um único PARÊNTESE ESQUERDO ou DIREITO ou caractere de delimitação similar).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Texto da anotação Ruby) O texto em tamanho menor que deve ser colocado adjacente ao texto base Ruby. Pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter os atributos RubyAlign e RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Uma nota lateral (anotação) escrita em tamanho de texto menor e colocada adjacente ao texto base ao qual se refere. Um elemento Ruby também pode conter os elementos RB, RT e RP. (Ruby) O contêiner ao redor de toda a montagem ruby. Deve conter um elemento RB seguido por um elemento RT ou um grupo de três elementos consistindo em RP, RT e RP. Os elementos Ruby e seus elementos de conteúdo não devem ser quebrados em várias linhas.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Um contêiner para agrupar elementos de conteúdo relacionados.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Uma porção genérica inline de texto sem características inerentes específicas. Pode ser usada, por exemplo, para delimitar um intervalo de texto com um determinado conjunto de atributos de estilo.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Um layout bidimensional de células de dados retangulares, possivelmente com uma subestrutura complexa. Contém uma ou mais linhas de tabela (tipo de estrutura TR) como filhos; ou um cabeçalho de tabela opcional (tipo de estrutura THead) seguido por uma ou mais elementos de corpo de tabela (tipo de estrutura TBody) e um rodapé de tabela opcional (tipo de estrutura TFoot). Além disso, uma tabela pode ter uma legenda (tipo de estrutura Caption) como seu primeiro ou último filho.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Um grupo de linhas que constituem a parte principal do corpo de uma tabela. Se a tabela for dividida em várias páginas, a área do corpo pode ser separada em um limite de linha. Uma tabela pode ter múltiplos elementos TBody para permitir o desenho de uma borda ou plano de fundo para um conjunto de linhas.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Uma célula de tabela contendo dados que fazem parte do conteúdo da tabela.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Um grupo de linhas que constituem o rodapé de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte inferior de cada fragmento da tabela (embora exista apenas um elemento TFoot.)

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Uma célula de tabela contendo texto de cabeçalho que descreve uma ou mais linhas ou colunas da tabela.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Um grupo de linhas que constituem o cabeçalho de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte superior de cada fragmento da tabela (embora exista apenas um elemento THead).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Uma lista composta por entradas de itens de índice (tipo de estrutura TOCI) e/ou outras entradas de índice aninhadas (TOC). Uma entrada de TOC que inclui apenas entradas TOCI representa uma hierarquia plana. Uma entrada de TOC que inclui outras entradas TOC aninhadas (e possivelmente entradas TOCI) representa uma hierarquia mais complexa. Idealmente, a hierarquia de uma entrada TOC de nível superior reflete a estrutura do corpo principal do documento.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Um membro individual de um índice. Os filhos desta entrada podem ser quaisquer dos seguintes tipos de estrutura: Lbl - Um rótulo Reference - Uma referência ao título e ao número da página NonStruct - Elementos não estruturados para envolver um artefato líder P - Texto descritivo TOC - Elementos de índice para índices hierárquicos, conforme descrito para a entrada TOC

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Uma linha de cabeçalhos ou dados em uma tabela. Pode conter células de cabeçalho de tabela e células de dados de tabela (tipos de estrutura TH e TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Um comentário ou anotação em tamanho de texto menor e formatado em duas linhas menores dentro da altura da linha de texto contendo e colocado após (inline) o texto base ao qual se refere. Um elemento Warichu também pode conter os elementos WT e WP. (Warichu) O contêiner ao redor de toda a montagem warichu. Pode conter um grupo de três elementos consistindo em WP, WT e WP. Os elementos Warichu (e seus elementos de conteúdo) podem envolver várias linhas, de acordo com as regras de quebra de warichu descritas na Norma Industrial Japonesa (JIS) X 4051-1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) A pontuação que envolve o texto WT. Contém texto (geralmente um único PARÊNTESE ESQUERDO ou DIREITO ou caractere de delimitação similar). De acordo com JIS X 4051-1995, os parênteses que cercam um warichu podem ser convertidos em um ESPAÇO (nominalmente 1/4 EM de largura) a critério do formatador.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) O texto de tamanho menor de um comentário warichu que é formatado em duas linhas e colocado entre os elementos WP circundantes.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Obtém a categoria do Tipo de Estrutura Padrão.

**Returns:**
Valor: Categoria do Tipo de Estrutura Padrão.

### getTag {#getTag--}
```
public final String getTag()
```

Obtém o nome da tag de {@code StructureElement}.

**Returns:**
Nome da tag de {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Realiza uma conversão explícita de {@link String} para {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Retorna uma string que representa o objeto atual.

**Returns:**
String que representa o objeto atual.
