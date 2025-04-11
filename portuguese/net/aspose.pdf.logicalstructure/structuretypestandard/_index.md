---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.StructureTypeStandard. Representa Tipos de Estrutura Padrão
type: docs
weight: 6730
url: /pt/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## Classe StructureTypeStandard

Representa Tipos de Estrutura Padrão.

```csharp
public sealed class StructureTypeStandard
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Obtém a categoria do Tipo de Estrutura Padrão. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Obtém o nome da tag do [`StructureElement`](../structureelement/). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Retorna uma string que representa o objeto atual. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Realiza uma conversão explícita de String para `StructureTypeStandard`. |

## Campos

| Nome | Descrição |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Anotação; PDF 1.5) Uma associação entre uma parte do conteúdo do ILSE e uma anotação PDF correspondente. Annot deve ser usado para todas as anotações PDF, exceto anotações de link e anotações de widget. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Artigo) Um corpo de texto relativamente autônomo que constitui uma única narrativa ou exposição. Os artigos devem ser disjuntos; ou seja, não devem conter outros artigos como elementos constituintes. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Entrada de bibliografia) Uma referência que identifica a fonte externa de algum conteúdo citado. Pode conter um rótulo (tipo de estrutura Lbl) como filho. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Citação em bloco) Uma porção de texto consistindo em um ou mais parágrafos atribuídos a alguém que não seja o autor do texto circundante. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Legenda) Uma breve porção de texto descrevendo uma tabela ou figura. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Código) Um fragmento de texto de programa de computador. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Divisão) Um elemento de bloco genérico ou grupo de elementos. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Documento) Um documento completo. Este é o elemento raiz de qualquer árvore de estrutura contendo várias partes ou vários artigos. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figura) Um item de conteúdo gráfico. Sua colocação pode ser especificada com o atributo de layout de Colocação. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Formulário) Uma anotação de widget representando um campo de formulário interativo. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Fórmula) Uma fórmula matemática. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Cabeçalho) Um rótulo para uma subdivisão do conteúdo de um documento. Deve ser o primeiro filho da divisão que lidera. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Cabeçalho de Nível 1, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Cabeçalho de Nível 2, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Cabeçalho de Nível 3, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Cabeçalho de Nível 4, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Cabeçalho de Nível 5, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Cabeçalho de Nível 6, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um cabeçalho a partir de seu nível de aninhamento. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Índice) Uma sequência de entradas contendo texto identificador acompanhado por elementos de referência que apontam ocorrências do texto especificado no corpo principal de um documento. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Lista) Uma sequência de itens de significado e importância semelhantes. Seus filhos imediatos devem ser uma legenda opcional (tipo de estrutura Caption) seguida por um ou mais itens de lista (tipo de estrutura LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Rótulo) Um nome ou número que distingue um determinado item de outros na mesma lista ou outro grupo de itens semelhantes. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Corpo da lista) O conteúdo descritivo de um item de lista. Em uma lista de dicionário, por exemplo, contém a definição do termo. Pode conter o conteúdo diretamente ou ter outros BLSEs, talvez incluindo listas aninhadas, como filhos. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Item de lista) Um membro individual de uma lista. Seus filhos podem ser um ou mais rótulos, corpos de lista, ou ambos (tipos de estrutura Lbl ou LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) Uma associação entre uma parte do conteúdo do ILSE e uma anotação ou anotações de link correspondentes. Seus filhos devem ser um ou mais itens de conteúdo ou ILSEs filhos e uma ou mais referências de objeto identificando as anotações de link associadas. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Elemento não estrutural) Um elemento de agrupamento que não possui significado estrutural inerente; serve apenas para fins de agrupamento. Este tipo de elemento difere de uma divisão (tipo de estrutura Div) na medida em que não deve ser interpretado ou exportado para outros formatos de documento; no entanto, seus descendentes devem ser processados normalmente. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Nota) Um item de texto explicativo, como uma nota de rodapé ou uma nota de fim, que é referenciado a partir do corpo do documento. Pode ter um rótulo (tipo de estrutura Lbl) como filho. A nota pode ser incluída como um filho do elemento de estrutura no texto do corpo que se refere a ela, ou pode ser incluída em outro lugar (como em uma seção de notas de fim) e acessada por meio de uma referência (tipo de estrutura Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Parágrafo) Uma divisão de texto de baixo nível. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Parte) Uma divisão em larga escala de um documento. Este tipo de elemento é apropriado para agrupar artigos ou seções. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Elemento privado) Um elemento de agrupamento contendo conteúdo privado pertencente à aplicação que o produz. O significado estrutural deste tipo de elemento é não especificado e deve ser determinado inteiramente pelo escritor conforme. Nem o elemento Private nem qualquer um de seus descendentes devem ser interpretados ou exportados para outros formatos de documento. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Citação) Uma porção de texto em linha atribuída a alguém que não seja o autor do texto circundante. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Texto base Ruby) O texto em tamanho completo ao qual a anotação ruby é aplicada. RB pode conter texto, outros elementos em linha, ou uma mistura de ambos. Pode ter o atributo RubyAlign. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Referência) Uma citação a conteúdo em outro lugar no documento. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Pontuação Ruby) Pontuação que envolve o texto da anotação ruby. É usada apenas quando uma anotação ruby não pode ser formatada corretamente em um estilo ruby e, em vez disso, é formatada como um comentário normal, ou quando é formatada como um warichu. Contém texto (geralmente um único PARENTESE ESQUERDO ou DIREITO ou caractere de delimitação semelhante). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Texto da anotação Ruby) O texto de tamanho menor que deve ser colocado adjacente ao texto base ruby. Pode conter texto, outros elementos em linha, ou uma mistura de ambos. Pode ter os atributos RubyAlign e RubyPosition. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Uma nota lateral (anotação) escrita em um tamanho de texto menor e colocada adjacente ao texto base ao qual se refere. Um elemento Ruby também pode conter os elementos RB, RT e RP. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Seção) Um contêiner para agrupar elementos de conteúdo relacionados. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Uma porção de texto em linha genérica que não possui características inerentes particulares. Pode ser usada, por exemplo, para delimitar um intervalo de texto com um determinado conjunto de atributos de estilo. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Tabela) Um layout bidimensional de células de dados retangulares, possivelmente com uma subestrutura complexa. Contém uma ou mais linhas de tabela (tipo de estrutura TR) como filhos; ou um cabeçalho de tabela opcional (tipo de estrutura THead) seguido por um ou mais elementos de corpo de tabela (tipo de estrutura TBody) e um rodapé de tabela opcional (tipo de estrutura TFoot). Além disso, uma tabela pode ter uma legenda (tipo de estrutura Caption) como seu primeiro ou último filho. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Grupo de linhas do corpo da tabela; PDF 1.5) Um grupo de linhas que constituem a parte principal do corpo de uma tabela. Se a tabela for dividida em várias páginas, a área do corpo pode ser quebrada em uma borda de linha. Uma tabela pode ter múltiplos elementos TBody para permitir o desenho de uma borda ou fundo para um conjunto de linhas. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Célula de dados da tabela) Uma célula de tabela contendo dados que fazem parte do conteúdo da tabela. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Grupo de linhas do rodapé da tabela; PDF 1.5) Um grupo de linhas que constituem o rodapé de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte inferior de cada fragmento da tabela (embora haja apenas um elemento TFoot). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Célula de cabeçalho da tabela) Uma célula de tabela contendo texto de cabeçalho descrevendo uma ou mais linhas ou colunas da tabela. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Grupo de linhas do cabeçalho da tabela; PDF 1.5) Um grupo de linhas que constituem o cabeçalho de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte superior de cada fragmento da tabela (embora haja apenas um elemento THead). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Tabela de conteúdos) Uma lista composta por entradas de itens da tabela de conteúdos (tipo de estrutura TOCI) e/ou outras entradas de tabela de conteúdos aninhadas (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Item da tabela de conteúdos) Um membro individual de uma tabela de conteúdos. Os filhos desta entrada podem ser qualquer um dos seguintes tipos de estrutura: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Linha da tabela) Uma linha de cabeçalhos ou dados em uma tabela. Pode conter células de cabeçalho de tabela e células de dados de tabela (tipos de estrutura TH e TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Um comentário ou anotação em um tamanho de texto menor e formatado em duas linhas menores dentro da altura da linha de texto que contém e colocado após (inline) o texto base ao qual se refere. Um elemento Warichu também pode conter os elementos WT e WP. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Pontuação Warichu) A pontuação que envolve o texto WT. Contém texto (geralmente um único PARENTESE ESQUERDO ou DIREITO ou caractere de delimitação semelhante). De acordo com JIS X 4051-1995, os parênteses que cercam um warichu podem ser convertidos em um ESPAÇO (nominalmente 1/4 EM de largura) a critério do formatador. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Texto Warichu) O texto de tamanho menor de um comentário warichu que é formatado em duas linhas e colocado entre os elementos WP circundantes. |

### Veja Também

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)