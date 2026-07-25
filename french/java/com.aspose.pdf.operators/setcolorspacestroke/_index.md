---
title: "SetColorSpaceStroke"
linktitle: "SetColorSpaceStroke"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur CS (définit la couleur pour les opérations tracées)."
type: docs
weight: 590
url: /fr/java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

Classe représentant l'opérateur CS (définit la couleur pour les opérations tracées).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | Constructeur de la classe opérateur. |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | Initialise l'opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte un objet visiteur pour traiter l'opérateur. |
| [getName](#getName--) | Obtient le nom de l'espace couleur. |
| [setName](#setName-java.lang.String-) | Définit le nom de l'espace couleur. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
Constructeur de la classe opérateur.

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
Initialise l'opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte un objet visiteur pour traiter l'opérateur.

### getName {#getName--}
```
public String getName()
```

Obtient le nom de l'espace couleur.

**Returns:**
valeur String

### setName {#setName-java.lang.String-}
Définit le nom de l'espace couleur.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand
