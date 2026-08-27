---
title: "Operator"
linktitle: "Operator"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe abstraite représentant un opérateur."
type: docs
weight: 3180
url: /fr/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Classe abstraite représentant un opérateur.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | À usage interne uniquement ! |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte le visiteur IOperatorSelector qui fournit le traitement des opérateurs. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Crée un opérateur à partir du nom d’une instance com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand. |
| [equals](#equals-com.aspose.pdf.Operator-) | Compare cette instance avec l’objet fourni. |
| [getCommand](#getCommand--) | Obtient la commande |
| [getCommandName](#getCommandName--) | Obtient le nom de l’opérateur. |
| [getIndex](#getIndex--) | Obtient l’index de l’opérateur dans la liste des opérateurs de la page. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Détermine si l’opérateur est celui qui est responsable de la sortie du texte (Tj, TJ, etc). |
| [setIndex](#setIndex-int-) | Définir l'index de l'opérateur dans la liste des opérateurs de page. |
| [toString](#toString--) | Traduit la commande et les paramètres en représentation sous forme de chaîne. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Compare cette instance avec l’objet fourni. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
À usage interne uniquement !

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte le visiteur IOperatorSelector qui fournit le traitement des opérateurs.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Crée un opérateur à partir du nom d’une instance com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand.

### equals {#equals-com.aspose.pdf.Operator-}
Compare cette instance avec l’objet fourni.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Obtient la commande

**Returns:**
Objet ICommand

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Obtient le nom de l’opérateur.

**Returns:**
valeur String

### getIndex {#getIndex--}
```
public int getIndex()
```

Obtient l’index de l’opérateur dans la liste des opérateurs de la page.

**Returns:**
valeur int

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Détermine si l’opérateur est celui qui est responsable de la sortie du texte (Tj, TJ, etc).

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Définir l'index de l'opérateur dans la liste des opérateurs de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### toString {#toString--}
```
public String toString()
```

Traduit la commande et les paramètres en représentation sous forme de chaîne.

**Returns:**
Texte de l'opérateur

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Compare cette instance avec l’objet fourni.
