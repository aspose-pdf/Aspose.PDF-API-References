---
title: "PdfConverter.BindPdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfConverter. Lie un fichier Pdf pour la conversion"
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdfconverter/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Lie un fichier Pdf pour la conversion.

```csharp
public override void BindPdf(string inputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Le fichier pdf. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Lie un flux Pdf pour la conversion.

```csharp
public override void BindPdf(Stream inputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Le flux pdf. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Document) {#bindpdf}

Lie un document PDF à l'instance [`PdfConverter`](../) pour un traitement ultérieur.

```csharp
public override void BindPdf(Document srcDoc)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcDoc | Document | L'objet [`Document`](../../../aspose.pdf/document/) représentant le PDF source à lier. |

## Remarques

Cette méthode initialise le [`PdfConverter`](../) avec le document PDF spécifié. Elle traite également les formulaires XFA dynamiques dans le document, le cas échéant.

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


