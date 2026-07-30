---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextPdfComparer. Compare deux documents page par page. Les documents sont comparés dans leur ensemble. Avant de comparer le texte, les textes des pages du document sont combinés en un seul texte"
type: docs
weight: 50
url: /fr/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Compare deux documents page par page. Les documents sont comparés dans leur ensemble. Avant de comparer le texte, les textes des pages du document sont combinés en un seul texte.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Premier document. |
| document2 | Document | Deuxième document. |
| options | ComparisonOptions | Options de comparaison. |

### Valeur de retour

Liste des modifications.

### Voir aussi

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Compare deux documents page par page. Le résultat est enregistré dans un fichier PDF. Les documents sont comparés dans leur ensemble. Avant de comparer le texte, les textes des pages du document sont combinés en un seul texte.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Premier document. |
| document2 | Document | Deuxième document. |
| options | ComparisonOptions | Options de comparaison. |
| resultPdfDocumentPath | String | Chemin du fichier pdf où enregistrer les résultats de la comparaison. |

### Valeur de retour

Liste des modifications.

### Voir aussi

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


