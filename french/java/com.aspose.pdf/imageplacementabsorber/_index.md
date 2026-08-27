---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un objet absorbeur d'objets de placement d'image. Effectue la recherche des utilisations d'images et fournit l'accès aux résultats de recherche via {@code."
type: docs
weight: 2340
url: /fr/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Représente un objet absorbeur d'objets de placement d'image. Effectue la recherche des utilisations d'images et fournit l'accès aux résultats de recherche via {@code ImagePlacementAbsorber.ImagePlacements} collection. </p> <hr> <pre> L'exemple montre comment trouver les images sur la première page du document PDF et obtenir les propriétés de placement d'image. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> L'objet {@code ImagePlacementAbsorber} est essentiellement utilisé dans le scénario de recherche d'images. Lorsque la recherche est terminée, les occurrences sont représentées par des objets {@code ImagePlacement} que la collection {@code ImagePlacementAbsorber.ImagePlacements} contient. L'objet {@code ImagePlacement} fournit l'accès aux propriétés de placement d'image : dimensions, résolution, etc. </p> La rotation positive de l'image est dans le sens antihoraire, pour la page, elle est dans le sens horaire. Ici, nous devons représenter l'angle de rotation de l'image, donc nous soustrayons l'angle de la page de l'angle de l'image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Initialise une nouvelle instance de l'objet {@code ImagePlacementAbsorber}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Obtient la collection des occurrences de placement d'image qui sont présentées avec des objets {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | Obtient/definit le mode lecture seule pour la collection des opérations d'analyse. Cela peut aider à éviter les exceptions de dépassement de mémoire. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Obtient/definit le mode lecture seule pour la collection des opérations d'analyse. Cela peut aider à éviter les exceptions de dépassement de mémoire. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Effectue une recherche sur le document spécifié. |
| [visit](#visit-com.aspose.pdf.Page-) | Effectue la recherche sur la page spécifiée. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Initialise une nouvelle instance de l'objet {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Obtient la collection des occurrences de placement d'image qui sont présentées avec des objets {@code ImagePlacement}.

**Returns:**
Objet ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Obtient/definit le mode lecture seule pour la collection des opérations d'analyse. Cela peut aider à éviter les exceptions de dépassement de mémoire.

**Returns:**
valeur booléenne

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Obtient/definit le mode lecture seule pour la collection des opérations d'analyse. Cela peut aider à éviter les exceptions de dépassement de mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### visit {#visit-com.aspose.pdf.IDocument-}
Effectue une recherche sur le document spécifié.

### visit {#visit-com.aspose.pdf.Page-}
Effectue la recherche sur la page spécifiée.
