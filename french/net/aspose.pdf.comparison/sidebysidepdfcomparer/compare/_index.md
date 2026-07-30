---
title: "SideBySidePdfComparer.Compare"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode SideBySidePdfComparer. Compare deux pages. Le résultat est enregistré dans un document PDF dans lequel la première page est écrite en premier puis la seconde. Vous pouvez l'ouvrir dans Adobe Acrobat en mode vue double page pour voir les changements côte à côte. Les suppressions sont indiquées sur la page de gauche et les insertions sur la page de droite."
type: docs
weight: 10
url: /fr/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Compare deux pages. Le résultat est enregistré dans un document PDF où la première page est écrite en premier, puis la seconde. Vous pouvez l'ouvrir dans Adobe Acrobat en mode affichage deux pages pour voir les modifications côte à côte. Les suppressions sont indiquées sur la page de gauche, et les insertions sur la page de droite.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page1 | Page | La première page à comparer. |
| page2 | Page | La première page à comparer. |
| targetPdfPath | String | Le chemin vers le fichier PDF pour enregistrer le résultat de la comparaison. |
| options | SideBySideComparisonOptions | Les options de comparaison. |

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Compare deux documents. Les pages sont comparées une par une. Les pages des documents comparés sont copiées les unes après les autres dans le document résultant. D'abord la première page du premier document, puis la première page du deuxième document. Ensuite la deuxième page du premier document, puis la deuxième page du deuxième document, etc. Vous pouvez l'ouvrir dans Adobe Acrobat en mode affichage deux pages pour voir les modifications côte à côte. Les suppressions sont indiquées sur la page de gauche, et les insertions sur la page de droite.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document1 | Document | Le premier document à comparer. |
| document2 | Document | Le deuxième document à comparer. |
| targetPdfPath | String | Le chemin vers le fichier PDF pour enregistrer le résultat de la comparaison. |
| options | SideBySideComparisonOptions | Les options de comparaison. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


