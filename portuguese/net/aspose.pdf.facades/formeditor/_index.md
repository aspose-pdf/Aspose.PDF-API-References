---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.FormEditor. Classe para editar formulários, adicionar/remover campos, etc.
type: docs
weight: 4330
url: /pt/net/aspose.pdf.facades/formeditor/
---
## Classe FormEditor

Classe para editar formulários (adicionar/remover campos, etc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Construtor para FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Inicializa um novo objeto `FormEditor` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Define opções para a caixa de combinação com valores de exportação. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Define os atributos visuais do campo. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Define os itens que serão adicionados à nova lista ou caixa de combinação criada. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | O membro para registrar o espaço entre dois botões de opção vizinhos em pixels, o padrão é 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | O sinalizador para indicar se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Define os sinais de submissão do botão de envio |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Adiciona um campo do tipo especificado ao formulário. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Adiciona um campo do tipo especificado ao formulário. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Adiciona JavaScript para um campo PushButton. Se um evento antigo existir, um novo evento é adicionado após ele. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Adiciona um novo item à caixa de lista. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Adiciona um novo item com valor de exportação ao campo da caixa de lista existente, apenas para o campo de caixa de combinação AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Adiciona um botão de envio ao formulário. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Fecha a fachada. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Copia um campo existente para a mesma posição no número da página especificada. Um novo documento será produzido, que contém tudo o que o documento de origem possui, exceto pelo campo copiado recentemente. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas ordenadas. Um novo documento será produzido, que contém tudo o que o documento de origem possui, exceto pelo campo copiado recentemente. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Copia um campo existente de um documento PDF para outro documento com o número da página original e ordenadas. Aviso: Apenas para campos AcroForm (excluindo caixa de opção). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Copia um campo existente de um documento PDF para outro documento com o número da página especificada e ordenadas originais. Aviso: Apenas para campos AcroForm (excluindo caixa de opção). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Copia um campo existente de um documento PDF para outro documento com o número da página especificada e ordenadas. Aviso: Apenas para campos AcroForm (excluindo caixa de opção). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Altera os atributos visuais de todos os campos no documento PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Altera os atributos visuais de todos os campos com o tipo de campo especificado. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Altera os atributos visuais do campo especificado. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Deleta item do campo da lista. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Obtém os sinais do campo. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Define a nova posição do campo. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Remove o campo do formulário. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Remove a ação de envio do campo. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Altera o nome do campo. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Redefine todos os atributos visuais para valor vazio. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Redefine todos os atributos visuais da fachada interna para valor vazio. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva o documento PDF no fluxo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva o documento PDF no arquivo especificado. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Define o estilo de alinhamento de um campo de texto. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Define o estilo de alinhamento vertical de um campo de texto. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Define os sinais do campo |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Define os atributos do campo. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Define o número de combinações para um campo de texto regular de linha única (o campo é automaticamente dividido em tantas posições igualmente espaçadas, ou combinações, quanto o valor do parâmetro combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Define o número máximo de caracteres do campo de texto. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Define JavaScript para um campo PushButton. Se um JavaScript antigo existir, ele será substituído pelo novo. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Define o sinalizador de envio do botão de envio. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Define a URL do botão. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Altera um campo de texto de linha única para um de múltiplas linhas. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)