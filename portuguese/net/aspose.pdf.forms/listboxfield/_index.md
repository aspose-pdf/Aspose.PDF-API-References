---
title: Class ListBoxField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.ListBoxField. Classe representa o campo ListBox
type: docs
weight: 5130
url: /pt/net/aspose.pdf.forms/listboxfield/
---
## Classe ListBoxField

Classe representa o campo ListBox.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | Construtor para ListBoxField a ser usado no Gerador. |
| [ListBoxField](listboxfield/#constructor_1)(Document, Rectangle) | Construtor para o campo ListBox. |
| [ListBoxField](listboxfield/#constructor_2)(Page, Rectangle) | Cria um novo campo ListBox. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Obtém as ações da anotação. (2 propriedades) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtém ou define o estado de aparência atual da anotação. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Obtém ou define o nome alternativo do campo (Um nome de campo alternativo que deve ser usado no lugar do nome real do campo sempre que o campo for identificado na interface do usuário). O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Obtém ou define o índice desta anotação na página. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Obtém o tipo de anotação. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtém o dicionário de aparência da anotação. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtém ou define as características da borda da anotação. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtém as características da anotação. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtém ou define a cor da anotação. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Obtém ou define a flag de compromisso na mudança de seleção. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtém ou define o texto da anotação. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Obtém o número de subcampos neste campo. (Por exemplo, número de itens no campo de botão de rádio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Obtém ou define a aparência padrão do campo. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Obtém ou define a flag exportável do campo. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags da anotação. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtém o nome totalmente qualificado da anotação. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtém ou define a altura da anotação. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Modo de destaque da anotação. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtém ou define o hyperlink do fragmento (para gerador de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtém ou define um valor bool que indica se este parágrafo estará na próxima coluna. O padrão é falso. (para geração de pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Obtém ou define um valor booleano que indica se este campo é um campo não-terminal, ou seja, um grupo de campos. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtém ou define se um parágrafo é inline. O padrão é falso. (para geração de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página. O padrão é falso. (para geração de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo. O padrão é falso. (para geração de pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Propriedade para suporte ao Gerador. Usado quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Retorna verdadeiro se o dicionário estiver sincronizado. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Obtém o subcampo contido neste campo pelo nome do subcampo. (2 indexadores) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Obtém ou define o nome de mapeamento do campo que deve ser usado ao exportar dados do campo de formulário interativo do documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtém ou define a data e hora em que a anotação foi recentemente modificada. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Obtém ou define a flag de multisseleção. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtém ou define o nome da anotação na página. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Uma ação que deve ser realizada quando a anotação é ativada. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Obtém a coleção de opções de escolha. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Obtém o índice da página que contém este campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Obtém o pai da anotação. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Obtém ou define o nome parcial do campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Obtém ou define o status de somente leitura do campo. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Obtém ou define o retângulo do campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Obtém ou define o status de obrigatório do campo. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | Obtém ou define o índice do item selecionado. Os itens são numerados a partir de 1. |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | Obtém ou define o array dos itens selecionados na lista de multisseleção. Para lista de seleção única, retorna um array com um único item. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtém o dicionário de aparência da anotação. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objeto de sincronização. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Obtém ou define a ordem de tabulação do campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtém ou define o alinhamento do texto para a anotação. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | Obtém ou define o índice do elemento visível superior da lista. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Obtém ou define o valor do campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtém ou define a largura da anotação. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo será colocado atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Aceita o visitante. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Adiciona uma nova opção com o nome especificado. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Adiciona uma nova opção com o valor de exportação e nome especificados. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copia subcampos deste campo para um array começando a partir do índice especificado. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Exclui a opção pelo seu nome. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Executa uma ação JavaScript especificada para o campo. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporta o campo de formulário PDF especificado para o formato JSON e escreve o resultado no stream fornecido. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporta o campo de formulário PDF especificado para o formato JSON e escreve o resultado no arquivo especificado. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporta o conteúdo do campo especificado para um stream JSON. O valor do campo do botão não é exportado. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Remove este campo e coloca seu valor diretamente na página. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Retorna o nome do estado "checado" de acordo com os nomes de estado existentes. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Retorna o enumerador dos campos contidos. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importa dados para os campos especificados a partir de um stream JSON, com base em uma correspondência exata dos nomes completos dos campos. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importa dados para o campo especificado a partir de um stream JSON, usando o nome completo especificado na variável 'fieldFullNameInJSON' para correspondência. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recalcula todos os campos calculados no formulário. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Define a posição do campo. |

### Veja Também

* classe [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)