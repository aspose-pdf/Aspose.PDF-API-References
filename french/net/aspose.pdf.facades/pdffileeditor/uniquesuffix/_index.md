---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfFileEditor. Format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous-chaîne NUM qui sera remplacée par des chiffres. Par exemple, si UniqueSuffix = ABCNUM alors pour le champ fieldName, les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Propriété PdfFileEditor.UniqueSuffix

Format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous-chaîne %NUM% qui sera remplacée par des chiffres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName", les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Exemples

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)