---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une action d'aller à distante similaire à une action d'aller à ordinaire mais qui saute vers une destination dans un autre fichier PDF au lieu du fichier actuel."
type: docs
weight: 1820
url: /fr/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

Représente une action d'aller à distante similaire à une action d'aller à ordinaire mais qui saute vers une destination dans un autre fichier PDF au lieu du fichier actuel.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Initialise l'objet GoToRemoteAction. |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | Initialise l'objet GoToRemoteAction. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFile](#getFile--) | Obtient la spécification du fichier dans lequel la destination se trouve. |
| [getNewWindow](#getNewWindow--) | Obtient un drapeau indiquant s'il faut ouvrir le document de destination dans une nouvelle fenêtre. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * Obtient la destination vers laquelle sauter. / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Définit la spécification du fichier dans lequel la destination se trouve. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Définit un drapeau indiquant s'il faut ouvrir le document de destination dans une nouvelle fenêtre. |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
Initialise l'objet GoToRemoteAction.

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
Initialise l'objet GoToRemoteAction.

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtient la spécification du fichier dans lequel la destination se trouve.

**Returns:**
Objet FileSpecification

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Obtient un drapeau indiquant s'il faut ouvrir le document de destination dans une nouvelle fenêtre.

**Returns:**
Élément ExtendedBoolean @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * Obtient la destination vers laquelle sauter. / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Définit la spécification du fichier dans lequel la destination se trouve.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Définit un drapeau indiquant s'il faut ouvrir le document de destination dans une nouvelle fenêtre.
