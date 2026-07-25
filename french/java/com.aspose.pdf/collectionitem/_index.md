---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe d'élément de collection. L'élément de collection contient les données décrites par le schéma de la collection."
type: docs
weight: 640
url: /fr/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Représente une classe d'élément de collection. L'élément de collection contient les données décrites par le schéma de la collection.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAllNames](#getAllNames--) | Obtient une collection de tous les noms des valeurs d'élément de collection. |
| [hasName](#hasName-java.lang.String-) | Vérifie si le nom donné existe dans l'élément de collection. |
| [isEmpty](#isEmpty--) | Obtient une valeur indiquant si l'élément de collection est vide. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tente d'obtenir la valeur de type DateTime de l'élément de collection par le nom spécifié. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tente d'obtenir la valeur double pour le nom spécifié de l'élément de collection. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tente d'obtenir la valeur entière pour un nom spécifié de l'élément de collection. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Tente d'obtenir la valeur texte avec le nom spécifié de l'élément de collection. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Obtient une collection de tous les noms des valeurs d'élément de collection.

**Returns:**
liste de String

### hasName {#hasName-java.lang.String-}
Vérifie si le nom donné existe dans l'élément de collection.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Obtient une valeur indiquant si l'élément de collection est vide.

**Returns:**
true si l'élément de collection est vide ; sinon, false. Cette propriété renvoie true si l'élément de collection ne contient aucune valeur, y compris les valeurs de chaîne, les valeurs double, les valeurs entières et les valeurs de date. Si l'un de ces types de valeurs est présent dans l'élément de collection, cette propriété renvoie false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tente d'obtenir la valeur de type DateTime de l'élément de collection par le nom spécifié.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tente d'obtenir la valeur double pour le nom spécifié de l'élément de collection.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tente d'obtenir la valeur entière pour un nom spécifié de l'élément de collection.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Tente d'obtenir la valeur texte avec le nom spécifié de l'élément de collection.
