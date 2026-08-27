---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une action de rendu qui contrôle la lecture de contenu multimédia."
type: docs
weight: 4180
url: /fr/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Une action de rendu qui contrôle la lecture de contenu multimédia.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Crée l'action de rendu. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Obtient ou définit le code JavaScript associé à l'action. |
| [getRendition](#getRendition--) | Obtient ou définit le rendu associé à l'action. |
| [getRenditionOperation](#getRenditionOperation--) | L'opération à effectuer lorsque l'action est déclenchée. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Obtient ou définit le code JavaScript associé à l'action. |
| [setRenditionOperation](#setRenditionOperation-int-) | L'opération à effectuer lorsque l'action est déclenchée. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Crée l'action de rendu.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Obtient ou définit le code JavaScript associé à l'action.

**Returns:**
valeur String

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Obtient ou définit le rendu associé à l'action.

**Returns:**
Instance de rendu

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

L'opération à effectuer lorsque l'action est déclenchée.

**Returns:**
Élément RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
Obtient ou définit le code JavaScript associé à l'action.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

L'opération à effectuer lorsque l'action est déclenchée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément RenditionOperation |
