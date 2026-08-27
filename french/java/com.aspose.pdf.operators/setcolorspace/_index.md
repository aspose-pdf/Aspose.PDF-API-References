---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur cs (définit l'espace colorimétrique pour les opérations non tracées)."
type: docs
weight: 580
url: /fr/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Classe représentant l'opérateur cs (définit l'espace colorimétrique pour les opérations non tracées).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Constructeur de la classe opérateur. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Initialise l'opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getCommandName](#getCommandName--) | Obtient le nom de la commande. |
| [getName](#getName--) | Obtient le nom de l'espace couleur. |
| [setName](#setName-java.lang.String-) | Définit le nom de l'espace couleur. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Constructeur de la classe opérateur.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Initialise l'opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtient le nom de la commande.

**Returns:**
valeur String

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
