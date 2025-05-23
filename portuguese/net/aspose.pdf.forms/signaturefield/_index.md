---
title: Class SignatureField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.SignatureField. Representa campo de assinatura
type: docs
weight: 5290
url: /pt/net/aspose.pdf.forms/signaturefield/
---
## Classe SignatureField

Representa campo de assinatura.

```csharp
public sealed class SignatureField : Field
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SignatureField](signaturefield/#constructor)(Document, Rectangle) | Inicializa uma nova instância da classe `SignatureField`. |
| [SignatureField](signaturefield/#constructor_1)(Page, Rectangle) | Inicializa uma nova instância da classe `SignatureField`. |

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
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtém ou define o texto da anotação. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Obtém o número de subcampos neste campo. (Por exemplo, número de itens no campo de botão de opção). |
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
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Obtém ou define o nome de mapeamento do campo que deve ser usado ao exportar dados de campo de formulário interativo do documento. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtém ou define uma margem externa para o parágrafo (para geração de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtém ou define a data e hora em que a anotação foi recentemente modificada. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtém ou define o nome da anotação na página. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Uma ação que deve ser realizada quando a anotação é ativada. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Obtém o índice da página que contém este campo. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Obtém o pai da anotação. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Obtém ou define o nome parcial do campo. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Obtém ou define o status de somente leitura do campo. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Obtém ou define o retângulo do campo. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Obtém ou define o status de obrigatório do campo. |
| [Signature](../../aspose.pdf.forms/signaturefield/signature/) { get; } | Obtém o objeto de assinatura. Este objeto contém dados de assinatura em relação aos padrões criptográficos de chave pública. As classes [`PKCS1`](../pkcs1/), [`PKCS7`](../pkcs7/) e [`PKCS7Detached`](../pkcs7detached/) representam todos os tipos suportados de objetos de assinatura. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtém o dicionário de aparência da anotação. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objeto de sincronização. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Obtém ou define a ordem de tabulação do campo. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtém ou define o alinhamento do texto para a anotação. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Obtém ou define o valor do campo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtém ou define um alinhamento vertical do parágrafo |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtém ou define a largura da anotação. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com um ZIndex maior será colocado sobre o gráfico com um ZIndex menor. O ZIndex pode ser negativo. Gráficos com ZIndex negativo serão colocados atrás do texto na página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Aceita visitante. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clona esta instância. Método virtual. Sempre retorna nulo. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copia subcampos deste campo para um array começando do índice especificado. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Executa uma ação JavaScript especificada para o campo. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporta o campo de formulário PDF especificado para o formato JSON e escreve o resultado no stream fornecido. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporta o campo de formulário PDF especificado para o formato JSON e escreve o resultado no arquivo especificado. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporta o conteúdo do campo especificado para um stream JSON. Valores de campo de botão não são exportados. |
| [ExtractCertificate](../../aspose.pdf.forms/signaturefield/extractcertificate/)() | Extrai o único certificado X.509 em formato DER como um stream. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage)() | Extrai a imagem da assinatura como um stream codificado em jpeg. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage_1)(ImageFormat) | Extrai a imagem da assinatura como um stream codificado. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Remove este campo e coloca seu valor diretamente na página. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Retorna o nome do estado "verificado" de acordo com os nomes de estado existentes. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Retorna o enumerador dos campos contidos. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importa dados para os campos especificados a partir de um stream JSON, com base em uma correspondência exata dos nomes completos dos campos. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importa dados para o campo especificado a partir de um stream JSON, usando o nome completo especificado na variável 'fieldFullNameInJSON' para correspondência. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recalcula todos os campos calculados no formulário. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Define a posição do campo. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign)(Signature) | Assina o documento usando este campo de assinatura. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign_1)(Signature, Stream, string) | Assina o documento usando este campo de assinatura. |

### Veja Também

* classe [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)