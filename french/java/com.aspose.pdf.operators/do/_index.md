---
title: "Do"
linktitle: "Do"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur Do (Invoker le XObject)."
type: docs
weight: 180
url: /fr/java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Classe représentant l'opérateur Do (Invoker le XObject).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Do](#Do--) | Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument. |
| [Do](#Do-java.lang.String-) | Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getCommandName](#getCommandName--) | Obtient le nom de la commande |
| [getName](#getName--) | Obtenir le nom de l'argument XObject de l'opérateur. |
| [setName](#setName-java.lang.String-) | Définir le nom de l'argument XObject de l'opérateur. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### Do {#Do--}
```
public Do()
```

Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument.

### Do {#Do-java.lang.String-}
Construit un nouvel opérateur Do. Utilisé pour récupérer tous les opérateurs Do, c’est‑à‑dire sans vérifier leurs noms d’argument.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtient le nom de la commande

**Returns:**
valeur String

### getName {#getName--}
```
public String getName()
```

Obtenir le nom de l'argument XObject de l'opérateur.

**Returns:**
valeur String

### setName {#setName-java.lang.String-}
Définir le nom de l'argument XObject de l'opérateur.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
