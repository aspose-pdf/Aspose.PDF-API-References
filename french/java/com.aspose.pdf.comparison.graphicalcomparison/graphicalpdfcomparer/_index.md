---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de comparer graphiquement des documents PDF. Elle doit être utilisée pour rechercher de petites modifications, principalement de nature graphique. Pour comparer les changements de contenu texte, utilisez une autre classe."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Représente une classe permettant de comparer graphiquement des documents PDF. Elle doit être utilisée pour rechercher de petites modifications, principalement de nature graphique. Pour comparer les changements de contenu texte, utilisez d'autres classes de comparaison PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Crée une instance de la classe {@link GraphicalPdfComparer}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Compare les documents graphiquement. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Compare les documents graphiquement. Le résultat de la comparaison est placé dans un document PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans une image. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans un document PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compare les pages graphiquement. Le résultat de la comparaison est placé dans un document PDF. |
| [getColor](#getColor--) | Obtient et définit la couleur du drapeau de changement. La couleur par défaut est rouge. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Obtient les différences entre les images des pages. Le résultat contient une image de la première page comparée et un tableau de différences. |
| [getResolution](#getResolution--) | Obtient et définit la résolution des images résultantes. La valeur par défaut est de 150 dpi. |
| [getThreshold](#getThreshold--) | Obtient et définit la valeur du seuil en pourcentage. Cette valeur vous permet d'ignorer les petites modifications si elles ne sont pas significatives pour vous. La valeur par défaut est de 0 %. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Obtient et définit la couleur du drapeau de changement. La couleur par défaut est rouge. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Obtient et définit la résolution des images résultantes. La valeur par défaut est de 150 dpi. |
| [setThreshold](#setThreshold-double-) | Obtient et définit la valeur du seuil en pourcentage. Cette valeur vous permet d'ignorer les petites modifications si elles ne sont pas significatives pour vous. La valeur par défaut est de 0 %. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Crée une instance de la classe {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Compare les documents graphiquement.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Compare les documents graphiquement. Le résultat de la comparaison est placé dans un document PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compare les pages graphiquement. Le résultat de la comparaison est placé dans une image.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Compare les pages graphiquement. Le résultat de la comparaison est placé dans un document PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compare les pages graphiquement. Le résultat de la comparaison est placé dans un document PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

Obtient et définit la couleur du drapeau de changement. La couleur par défaut est rouge.

**Returns:**
Instance de Couleur

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Obtient les différences entre les images des pages. Le résultat contient une image de la première page comparée et un tableau de différences.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Obtient et définit la résolution des images résultantes. La valeur par défaut est de 150 dpi.

**Returns:**
Instance de résolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Obtient et définit la valeur du seuil en pourcentage. Cette valeur vous permet d'ignorer les petites modifications si elles ne sont pas significatives pour vous. La valeur par défaut est de 0 %.

**Returns:**
valeur double

### setColor {#setColor-com.aspose.pdf.Color-}
Obtient et définit la couleur du drapeau de changement. La couleur par défaut est rouge.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Obtient et définit la résolution des images résultantes. La valeur par défaut est de 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Obtient et définit la valeur du seuil en pourcentage. Cette valeur vous permet d'ignorer les petites modifications si elles ne sont pas significatives pour vous. La valeur par défaut est de 0 %.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
