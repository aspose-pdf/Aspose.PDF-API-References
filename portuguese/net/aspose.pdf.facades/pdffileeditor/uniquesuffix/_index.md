---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfFileEditor. Formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. Esta string deve conter a substring NUM que será substituída por números. Por exemplo, se UniqueSuffix = ABCNUM, então para o campo fieldName os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Propriedade PdfFileEditor.UniqueSuffix

Formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = "ABC%NUM%", então para o campo "fieldName" os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Exemplos

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)