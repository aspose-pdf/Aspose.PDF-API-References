---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Id. Representa a estrutura do identificador do arquivo
type: docs
weight: 5850
url: /pt/net/aspose.pdf/id/
---
## Classe Id

Representa a estrutura do identificador do arquivo.

```csharp
public class Id
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Modificado](../../aspose.pdf/id/modified/) { get; } | Identificador que muda com base no conteúdo do documento no momento em que foi atualizado pela última vez. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identificador permanente baseado no conteúdo do documento no momento em que foi criado originalmente. |

## Exemplos

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)