---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode GraphicalPdfComparer. Compare les pages graphiquement. Le résultat de la comparaison est placé dans un document PDF"
type: docs
weight: 80
url: /fr/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Compare les pages graphiquement. Le résultat de la comparaison est placé dans un Document PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page1 | Page | La première page. |
| page2 | Page | La deuxième page. |
| resultPdfPath | String | Le chemin du fichier PDF cible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Si les pages comparées ont des tailles différentes. Si resultPdfPath est nul ou une chaîne vide. |

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Compare les pages graphiquement. Le résultat de la comparaison est placé dans un Document PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page1 | Page | La première page. |
| page2 | Page | La deuxième page. |
| pdfDocument | Document | L'instance du document PDF. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Si les pages comparées ont des tailles différentes. |

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


