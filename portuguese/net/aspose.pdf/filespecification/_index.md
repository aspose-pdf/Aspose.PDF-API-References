---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.FileSpecification. Classe que representa arquivo incorporado
type: docs
weight: 4850
url: /pt/net/aspose.pdf/filespecification/
---
## Classe FileSpecification

Classe que representa arquivo incorporado.

```csharp
public sealed class FileSpecification : IDisposable
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Cria uma nova especificação de arquivo vazia. |
| [FileSpecification](filespecification/#constructor_3)(string) | Construtor para FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Construtor para especificação de arquivo. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Construtor para FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Construtor para FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Construtor para FileSpecification. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Relação de arquivo associado. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Obtém um item de coleção da especificação de arquivo. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Obtém ou define o arquivo de conteúdo. Esta propriedade retorna dados carregados na memória, o que pode causar exceção de falta de memória para grandes dados. Para diminuir o uso de memória, use StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Obtém ou define o texto associado à especificação de arquivo. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Obtém ou define o formato de codificação. Valores possíveis: Zip - arquivo comprimido com ZIP, None - arquivo não comprimido. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Obtém a carga útil criptografada. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Obtém ou define o nome do sistema de arquivos. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Se verdadeiro, o conteúdo do arquivo será incluído na especificação do arquivo. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Obtém o subtipo do arquivo incorporado |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Obtém ou define o nome da especificação do arquivo. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Obtém os parâmetros do arquivo. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Obtém o conteúdo do arquivo como um fluxo. O conteúdo não é carregado na memória, o que permite diminuir o uso de memória. Mas este fluxo não suporta posicionamento e a propriedade Length. Se você precisar desses recursos, use a propriedade Contents em vez disso. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Obtém ou define o nome unicode da especificação do arquivo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Descartar conteúdos. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Obtém parâmetro específico da aplicação. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Define parâmetro específico da aplicação. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)