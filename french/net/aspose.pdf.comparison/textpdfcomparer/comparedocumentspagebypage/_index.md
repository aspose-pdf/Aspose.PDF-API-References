---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Méthode TextPdfComparer. Compare deux documents page par page
type: docs
weight: 40
url: /fr/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Compare deux documents page par page.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Premier document.. |
| document2 | Document | Deuxième document. |
| options | ComparisonOptions | Options de comparaison. |

### Valeur de retour

Liste des changements par page.

### Voir aussi

* classe [DiffOperation](../../diffoperation/)
* classe [Document](../../../aspose.pdf/document/)
* classe [ComparisonOptions](../../comparisonoptions/)
* classe [TextPdfComparer](../)
* espace de noms [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Compare deux documents page par page. Le résultat est enregistré dans un fichier PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Premier document.. |
| document2 | Document | Deuxième document. |
| options | ComparisonOptions | Options de comparaison. |
| resultPdfDocumentPath | String | Chemin vers le fichier pdf pour enregistrer les résultats de la comparaison. |

### Valeur de retour

Liste des changements par page.

### Voir aussi

* classe [DiffOperation](../../diffoperation/)
* classe [Document](../../../aspose.pdf/document/)
* classe [ComparisonOptions](../../comparisonoptions/)
* classe [TextPdfComparer](../)
* espace de noms [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)