---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfXmpMetadata. Classe para manipulação de metadados XMP
type: docs
weight: 4640
url: /pt/net/aspose.pdf.facades/pdfxmpmetadata/
---
## Classe PdfXmpMetadata

Classe para manipulação de metadados XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Construtor para PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Inicializa um novo objeto `PdfXmpMetadata` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Obtém a contagem de itens na coleção. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Obtém o dicionário de campos de extensão. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Retorna verdadeiro se a coleção tiver tamanho fixo. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Retorna verdadeiro se a coleção for somente leitura. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Retorna verdadeiro se a coleção estiver sincronizada. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Obtém ou define o valor pela chave. (2 indexadores) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Obtém as chaves do dicionário. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Obtém o objeto de sincronização da coleção. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Obtém a coleção de valores no dicionário. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Adiciona um par com chave e valor ao dicionário. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Adiciona valor aos metadados XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Adiciona um novo elemento ao objeto dicionário. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Adiciona um novo elemento ao objeto dicionário. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Adiciona campo de extensão aos metadados. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Remove todos os elementos do objeto. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Desfaz o Aspose.Pdf.Document vinculado a uma fachada. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Verifica se o dicionário contém a propriedade especificada. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica se o par chave-valor especificado está contido no dicionário. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Verifica se o dicionário contém a chave especificada. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Determina se este dicionário contém a chave especificada. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Obtém o objeto enumerador do dicionário. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Obtém o URI do namespace pelo prefixo. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Obtém o prefixo pelo URI do namespace. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Obtém os metadados XmpMetadata do PDF de entrada em formato XML. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Obtém uma parte dos metadados XmpMetadata do PDF de entrada de acordo com um nome de meta. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registra o URI do namespace. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Remove o elemento com a chave especificada. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Remove o par chave/valor da coleção. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Remove a chave do dicionário. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Salva o documento PDF no fluxo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Salva o documento PDF no arquivo especificado. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* classe [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)