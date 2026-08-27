---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfFileEditor. Format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous‑chaîne NUM qui sera remplacée par des nombres. Par exemple, si UniqueSuffix vaut ABCNUM, alors pour le champ fieldName les noms seront fieldNameABC1 fieldNameABC2 fieldNameABC3, etc."
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Format du suffixe ajouté au nom du champ pour le rendre unique lors de la concaténation des formulaires. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = \"ABC%NUM%\", alors pour le champ \"fieldName\" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.

```csharp
public string UniqueSuffix { get; set; }
```

## Exemples

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


