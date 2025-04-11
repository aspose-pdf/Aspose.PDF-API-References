---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.Form. Classe que representa o objeto formulário
type: docs
weight: 5070
url: /pt/net/aspose.pdf.forms/form/
---
## Classe Formulário

Classe que representa o objeto formulário.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é verdadeiro. Defina como falso para aumentar o desempenho ao preencher o formulário com uma grande quantidade de campos calculados. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Se definido, campos ausentes do formulário serão criados automaticamente se estiverem presentes nas anotações. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Permite definir a ordem de cálculo dos campos. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Obtém o número de campos neste formulário. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Obtém ou define a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos do formulário). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Obtém os recursos padrão colocados neste formulário. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Se esta propriedade for verdadeira, retângulos de contorno vermelho adicionais serão desenhados para os elementos de contêiner exclGroup Xfa obrigatórios. Esta propriedade foi introduzida devido à ausência de análogos para o exclGroup durante a conversão da representação Xfa de formulários para o padrão. É falso por padrão. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Obtém a lista de todos os campos no nível mais baixo do formulário hierárquico. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão do formulário XFA para o formulário padrão. É falso por padrão. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Retorna verdadeiro se o objeto for thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Obtém o campo do formulário pelo nome do campo. Lança exceção se o campo não for encontrado. (2 indexadores) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Se esta propriedade for verdadeira, o dicionário "Perms" será removido do documento pdf após a conversão de documentos dinâmicos para o padrão. O dicionário "Perms" pode conter regras que perturbam a exibição da seleção de campos obrigatórios no Adobe Acrobat Reader. É falso por padrão. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (escrito) de uma maneira que altera seu conteúdo anterior, ao contrário de uma atualização incremental. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Se definido, o documento contém pelo menos um campo de assinatura. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Retorna o objeto de sincronização. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Obtém o tipo do formulário. Os valores possíveis são: Padrão, Estático, Dinâmico. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Obtém os dados XFA do formulário (se presentes). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Adiciona campo ao formulário. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Adiciona campo ao formulário. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Adiciona um novo campo ao formulário; se este campo já estiver colocado em outro ou neste formulário, uma cópia do campo é criada. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Adiciona uma aparência adicional do campo à página especificada do documento na localização especificada. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Define o XFA do formulário para o valor especificado. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Copia os campos colocados no formulário para um array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Remove o campo do formulário. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Remove o campo do formulário pelo seu nome. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exporta os campos do formulário PDF para o formato JSON e escreve o resultado no stream fornecido. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exporta os campos do formulário PDF para o formato JSON e escreve o resultado no arquivo especificado. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Remove todos os campos do formulário e coloca seus valores diretamente na página. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Obtém a enumeração dos campos do formulário. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Retorna os campos dentro do retângulo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Verifica se o formulário já possui o campo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Determina se o campo com o nome especificado já foi adicionado ao Formulário. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Determina se o campo com o nome especificado já foi adicionado ao Formulário, com a capacidade de olhar na hierarquia de filhos dos campos. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importa os campos do formulário PDF do formato JSON fornecido no stream. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importa os campos do formulário PDF do formato JSON fornecido no arquivo especificado. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Torna as anotações dos campos do formulário independentes. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Remove a aparência do campo no índice especificado. Se apenas uma aparência de filho permanecer, o método a incorpora no campo. |

## Campos

| Nome | Descrição |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Os formulários podem conter informações de assinatura, ou seja, podem ser assinados ou não assinados. E a visualização do formulário às vezes deve depender de se o formulário está assinado ou não. Esta propriedade informa ao conversor do formulário (por exemplo, durante a conversão do formulário XFA para o formulário padrão) se o formulário resultante deve ser renderizado como assinado ou não assinado. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Classe que descreve as configurações para o procedimento de achatamento do Formulário. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Os formulários podem conter informações de assinatura e podem ser assinados ou não assinados. Às vezes, a visualização dos formulários no visualizador deve depender de se o formulário está assinado ou não. Este enum enumera os possíveis modos de renderização durante a conversão do tipo de formulário em relação à assinatura. |

### Veja Também

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)