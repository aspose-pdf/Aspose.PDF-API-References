---
title: "DP"
linktitle: "DP"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur DP (désigner le point de contenu marqué)."
type: docs
weight: 190
url: /fr/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Classe représentant l'opérateur DP (désigner le point de contenu marqué).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Constructeur de la classe opérateur. |
| [DP](#DP-java.lang.String-) | Initialise l'opérateur. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Obtient le dictionnaire des propriétés |
| [getTag](#getTag--) | Obtient la balise de contenu marqué |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Définit le dictionnaire des propriétés |
| [setTag](#setTag-java.lang.String-) | Définit la balise de contenu marqué |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Constructeur de la classe opérateur.

### DP {#DP-java.lang.String-}
Initialise l'opérateur.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Obtient le dictionnaire des propriétés

**Returns:**
IPdfDictionary valeur

### getTag {#getTag--}
```
public String getTag()
```

Obtient la balise de contenu marqué

**Returns:**
valeur String

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Définit le dictionnaire des propriétés

### setTag {#setTag-java.lang.String-}
Définit la balise de contenu marqué

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
