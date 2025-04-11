---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.Form. Classe que representa o objeto do formulário Acro
type: docs
weight: 4290
url: /pt/net/aspose.pdf.facades/form/
---
## Classe Form

Classe que representa o objeto do formulário Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Form](form/#constructor)() | Construtor de Form sem parâmetros. |
| [Form](form/#constructor_1)(Document) | Inicializa um novo objeto `Form` com base no *documento*. |
| [Form](form/#constructor_4)(Stream) | Construtor para o formulário. |
| [Form](form/#constructor_7)(string) | Construtor de Form. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Obtém a lista de nomes de campos no formulário. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Obtém todos os nomes dos botões de envio do formulário. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Resultado da última operação de importação. Array de objetos que descrevem o resultado da importação para cada campo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Fecha arquivos abertos sem quaisquer alterações. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exporta o conteúdo dos campos do pdf para o fluxo fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exporta o conteúdo de todos os campos no documento para um fluxo JSON. Os valores dos campos de botão não são exportados. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extrai o pacote de dados XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Preenche um campo de código de barras de acordo com seu nome de campo totalmente qualificado. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Preenche o campo da caixa de seleção com um valor booleano. Aviso: Apenas aplicável a Caixa de Seleção. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.CheckBoxField", você deve especificar o nome completo e não "CheckBoxField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Preenche o campo da caixa de seleção com um valor de índice válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, apenas o nome do campo deve ser conhecido. Enquanto o valor pode ser especificado pelo seu índice. Aviso: Apenas aplicável a Caixa de Seleção, Caixa de Combinação e Caixa de Lista. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.ListBoxField", você deve especificar o nome completo e não "ListBoxField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado. Antes de preencher os campos, todos os nomes dos campos e seus valores válidos correspondentes devem ser conhecidos. Tanto os nomes dos campos quanto os valores são sensíveis a maiúsculas e minúsculas. Observe que Aspose.Pdf.Facades suporta apenas nomes de campos completos e não funciona com nomes de campos parciais, ao contrário do Aspose.Pdf.Kit; Por exemplo, se o campo tiver o nome completo "Form.Subform.TextField", você deve especificar o nome completo e não "TextField". Você pode usar a propriedade FieldNames para explorar os nomes de campos existentes e pesquisar o campo necessário pelo seu nome parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Preenche um campo com múltiplas seleções. Nota: apenas para o Campo de Caixa de Lista AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Preenche o campo com o valor especificado. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Preenche os campos de caixa de texto com valores de texto e salva o documento. Relevante para documentos assinados. Aviso: Apenas aplicável a Caixa de Texto. Tanto os nomes dos campos quanto os valores são sensíveis a maiúsculas e minúsculas. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Sobrecarga a função de FillImageField. A entrada é um fluxo de imagem. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Cola uma imagem no campo de botão existente como sua aparência de acordo com seu nome de campo totalmente qualificado. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Achata todos os campos. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Achata um campo especificado com o nome de campo totalmente qualificado. Qualquer outro campo permanecerá inalterado. Se o fieldName for inválido, todos os campos permanecerão inalterados. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Retorna o valor atual para campos de opção de botão de rádio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Obtém os campos de opção de botão de rádio e os valores relacionados com base no nome do campo. Este método tem significado para grupos de botões de rádio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Obtém o valor do campo de acordo com seu nome de campo. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Retorna o objeto FrofmFieldFacade contendo todos os atributos de aparência. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Retorna as flags do campo. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Obtém a limitação do campo de texto. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Retorna o tipo de campo. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Obtém o nome completo do campo de acordo com seu nome de campo curto. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Obtém o valor de um campo de Texto Rico, incluindo as informações de formatação de cada caractere. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Retorna as flags de submissão do botão de envio |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importa todos os dados dos campos de um fluxo JSON para os campos do documento, correspondendo os campos pelos seus nomes completos. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importa o conteúdo dos campos do arquivo xml e os coloca no novo pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Determina se o campo é obrigatório ou não. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Renomeia um campo. Tanto o campo AcroForm quanto o campo XFA são aceitos. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Salva o documento no fluxo especificado. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Salva o documento no arquivo especificado. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Substitui os dados XFA pelo pacote de dados especificado. O pacote de dados pode ser extraído usando ExtractXfaData. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Classe que descreve o resultado da importação de campo. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status do campo importado |

### Veja Também

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)