---
title: "SetGray"
linktitle: "SetGray"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Définit le niveau de gris pour les opérations non tracées."
type: docs
weight: 640
url: /fr/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Définit le niveau de gris pour les opérations non tracées.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetGray](#SetGray-double-) | Constructeur pour le programme d'écriture. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getColor](#getColor--) | Renvoie la couleur spécifiée par l'opérateur. |
| [getGray](#getGray--) | Obtient ou définit le niveau de valeur de gris. |
| [setGray](#setGray-double-) | Obtient ou définit le niveau de valeur de gris. |
| [toString](#toString--) | Renvoie la représentation sous forme de chaîne de l'opérateur. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Constructeur pour le programme d'écriture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gris |  | Le niveau de valeur de gris. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getColor {#getColor--}
```
public Color getColor()
```

Renvoie la couleur spécifiée par l'opérateur.

**Returns:**
Couleur spécifiée par l'opérateur.

### getGray {#getGray--}
```
public final double getGray()
```

Obtient ou définit le niveau de valeur de gris.

**Returns:**
valeur double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Obtient ou définit le niveau de valeur de gris.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation sous forme de chaîne de l'opérateur.

**Returns:**
Représentation sous forme de chaîne de l'opérateur.
