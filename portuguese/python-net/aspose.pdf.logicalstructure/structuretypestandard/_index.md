---
title: "StructureTypeStandard"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa os Tipos de Estrutura Padrão."
type: docs
weight: 560
url: /pt/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Representa os Tipos de Estrutura Padrão.

O tipo StructureTypeStandard expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| tag | Obtém o nome da tag de [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| categoria | Obtém a categoria do Tipo de Estrutura Padrão. |
| DOCUMENT | (Document) Um documento completo. Este é o elemento raiz de qualquer árvore de estrutura que contenha múltiplas partes ou múltiplos artigos. |
| PART | (Part) Uma divisão de grande escala de um documento. Este tipo de elemento é adequado para agrupar artigos ou seções. |
| ART | (Article) Um corpo de texto relativamente autocontido que constitui uma única narrativa ou exposição. Os artigos devem ser disjuntos; isto é, não devem conter outros artigos como elementos constituintes. |
| SECT | (Section) Um contêiner para agrupar elementos de conteúdo relacionados. |
| DIV | (Division) Um elemento genérico de nível de bloco ou um grupo de elementos. |
| BLOCK_QUOTE | (Block quotation) Uma porção de texto composta por um ou mais parágrafos atribuída a alguém que não seja o autor do texto circundante. |
| CAPTION | (Caption) Uma breve porção de texto descrevendo uma tabela ou figura. |
| TOC | (Table of contents) Uma lista composta por entradas de itens de índice (tipo de estrutura TOCI) e/ou outras entradas de índice aninhadas (TOC). |
| TOCI | (Table of contents item) Um membro individual de um índice. Os filhos desta entrada podem ser qualquer um dos seguintes tipos de estrutura: |
| INDEX | (Index) Uma sequência de entradas contendo texto identificador acompanhado por elementos de referência que apontam ocorrências do texto especificado no corpo principal de um documento. |
| NON_STRUCT | (Nonstructural element) Um elemento de agrupamento que não possui significado estrutural inerente; serve exclusivamente para fins de agrupamento. Este tipo de elemento difere de uma divisão (tipo de estrutura Div) pois não deve ser interpretado ou exportado para outros formatos de documento; entretanto, seus descendentes devem ser processados normalmente. |
| PRIVATE | (Private element) Um elemento de agrupamento contendo conteúdo privado pertencente ao aplicativo que o produz. O significado estrutural deste tipo de elemento não é especificado e deve ser determinado inteiramente pelo escritor conforme. Nem o elemento Private nem quaisquer de seus descendentes devem ser interpretados ou exportados para outros formatos de documento. |
| P | (Paragraph) Uma divisão de baixo nível de texto. |
| H | (Heading) Um rótulo para uma subdivisão do conteúdo de um documento. Deve ser o primeiro filho da divisão que ele intitula. |
| H1 | Título de Nível 1, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| H2 | Título de Nível 2, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| H3 | Título de Nível 3, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| H4 | Título de Nível 4, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| H5 | Título de Nível 5, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| H6 | Título de Nível 6, para uso em escritores conformes que não podem aninhar hierarquicamente suas seções e, portanto, não podem determinar o nível de um título a partir do seu nível de aninhamento. |
| L | (List) Uma sequência de itens de significado e importância semelhantes. Seus filhos imediatos devem ser uma legenda opcional (tipo de estrutura Caption) seguida por um ou mais itens de lista (tipo de estrutura LI). |
| LI | (List item) Um membro individual de uma lista. Seus filhos podem ser um ou mais rótulos, corpos de lista ou ambos (tipos de estrutura Lbl ou LBody). |
| LBL | (Label) Um nome ou número que distingue um determinado item dos outros na mesma lista ou em outro grupo de itens semelhantes. |
| L_BODY | (List body) O conteúdo descritivo de um item de lista. Em uma lista de dicionário, por exemplo, contém a definição do termo. Pode conter o conteúdo diretamente ou ter outros BLSEs, talvez incluindo listas aninhadas, como filhos. |
| TABLE | (Table) Um layout bidimensional de células de dados retangulares, possivelmente com uma subestrutura complexa. Contém uma ou mais linhas de tabela (tipo de estrutura TR) como filhos; ou um cabeçalho de tabela opcional (tipo de estrutura THead) seguido por um ou mais elementos de corpo de tabela (tipo de estrutura TBody) e um rodapé de tabela opcional (tipo de estrutura TFoot). Além disso, uma tabela pode ter uma legenda (tipo de estrutura Caption) como seu primeiro ou último filho. |
| T_HEAD | (Table header row group; PDF 1.5) Um grupo de linhas que constituem o cabeçalho de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas no topo de cada fragmento da tabela (embora haja apenas um elemento THead). |
| T_BODY | (Table body row group; PDF 1.5) Um grupo de linhas que constitui a parte principal do corpo de uma tabela. Se a tabela for dividida em várias páginas, a área do corpo pode ser separada em um limite de linha. Uma tabela pode ter múltiplos elementos TBody para permitir o desenho de uma borda ou fundo para um conjunto de linhas. |
| T_FOOT | (Table footer row group; PDF 1.5) Um grupo de linhas que constitui o rodapé de uma tabela. Se a tabela for dividida em várias páginas, essas linhas podem ser redesenhadas na parte inferior de cada fragmento da tabela (embora exista apenas um elemento TFoot.) |
| TR | (Table row) Uma linha de cabeçalhos ou dados em uma tabela. Pode conter células de cabeçalho de tabela e células de dados de tabela (tipos de estrutura TH e TD). |
| TH | (Table header cell) Uma célula de tabela contendo texto de cabeçalho que descreve uma ou mais linhas ou colunas da tabela. |
| TD | (Table data cell) Uma célula de tabela contendo dados que fazem parte do conteúdo da tabela. |
| SPAN | (Span) Uma porção genérica de texto em linha sem características inerentes específicas. Pode ser usada, por exemplo, para delimitar um intervalo de texto com um determinado conjunto de atributos de estilo. |
| QUOTE | (Quotation) Uma porção de texto em linha atribuída a alguém que não o autor do texto circundante. |
| NOTA | (Note) Um item de texto explicativo, como uma nota de rodapé ou uma nota final, que é referenciado a partir do corpo do documento. Pode ter um rótulo (structure type Lbl) como filho. A nota pode ser incluída como filho do elemento de estrutura no texto do corpo que a referencia, ou pode ser incluída em outro local (como em uma seção de notas finais) e acessada por meio de uma referência (structure type Reference). |
| REFERENCE | (Reference) Uma citação a conteúdo em outra parte do documento. |
| BIB_ENTRY | (Bibliography entry) Uma referência que identifica a fonte externa de algum conteúdo citado. Pode conter um rótulo (structure type Lbl) como filho. |
| CODE | (Code) Um fragmento de texto de programa de computador. |
| LINK | (Link) Uma associação entre uma porção do conteúdo do ILSE e uma anotação de link correspondente ou anotações de link. Seus filhos devem ser um ou mais itens de conteúdo ou ILSEs filhos e um ou mais referências de objeto que identificam as anotações de link associadas. |
| ANNOT | (Annotation; PDF 1.5) Uma associação entre uma porção do conteúdo do ILSE e uma anotação PDF correspondente. Annot deve ser usado para todas as anotações PDF, exceto anotações de link e anotações de widget. |
| RUBY | (Ruby; PDF 1.5) Uma nota marginal (anotação) escrita em tamanho de texto menor e colocada adjacente ao texto base ao qual se refere. Um elemento Ruby também pode conter os elementos RB, RT e RP. |
| RB | (Ruby base text) O texto de tamanho completo ao qual a anotação ruby é aplicada. RB pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter o RubyAlignattribute. |
| RT | (Ruby annotation text) O texto de tamanho menor que deve ser colocado adjacente ao texto base ruby. Pode conter texto, outros elementos inline ou uma mistura de ambos. Pode ter os atributos RubyAlign e RubyPosition. |
| RP | (Ruby punctuation) Pontuação que envolve o texto da anotação ruby. É usada apenas quando uma anotação ruby não pode ser formatada adequadamente em estilo ruby e, em vez disso, é formatada como um comentário normal, ou quando é formatada como warichu. Contém texto (geralmente um único LEFT ou RIGHT PARENTHESIS ou caractere de delimitação similar). |
| WARICHU | (Warichu; PDF 1.5) Um comentário ou anotação em tamanho de texto menor e formatado em duas linhas menores dentro da altura da linha de texto contendo e colocado após (inline) o texto base ao qual se refere. Um elemento Warichu também pode conter os elementos WT e WP. |
| WT | (Warichu text) O texto de tamanho menor de um comentário warichu que é formatado em duas linhas e colocado entre os elementos WP circundantes. |
| WP | (Warichu punctuation) A pontuação que envolve o texto WT. Contém texto (geralmente um único LEFT ou RIGHT PARENTHESIS ou caractere de delimitação similar). De acordo com JIS X 4051-1995, os parênteses que cercam um warichu podem ser convertidos em um ESPAÇO (nominalmente 1/4 EM de largura) a critério do formatador. |
| FIGURE | (Figure) Um item de conteúdo gráfico. Seu posicionamento pode ser especificado com o atributo de layout Placement. |
| FORMULA | (Formula) Uma fórmula matemática. |
| FORM | (Form) Uma anotação de widget que representa um campo de formulário interativo. |

### Veja Também

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

