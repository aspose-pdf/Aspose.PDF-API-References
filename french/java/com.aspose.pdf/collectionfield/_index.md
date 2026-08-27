---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de champ de schéma de collection de documents."
type: docs
weight: 620
url: /fr/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Représente une classe de champ de schéma de collection de documents.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getE](#getE--) | Obtient un indicateur indiquant si le processeur PDF interactif doit fournir la prise en charge de la modification de la valeur du champ. Valeur par défaut : false |
| [getFiledType](#getFiledType--) | Obtient le type d’une valeur de champ dans une collection de schéma. Ce champ décrit le type de valeur correspondant à {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Obtient le nom de champ textuel qui doit être présenté à l’utilisateur par le processeur PDF interactif |
| [getO](#getO--) | Obtient l’ordre relatif du nom de champ dans l’interface utilisateur. Les champs doivent être triés par le processeur PDF interactif par ordre croissant. |
| [getSubtype](#getSubtype--) | Obtient le sous‑type d’une valeur de champ dans une collection de schéma. Le sous‑type du champ de collection ou du champ lié à un fichier que ce dictionnaire décrit. Cette entrée identifie le type de données qui doit être stocké dans le champ. |
| [getV](#getV--) | Obtient la visibilité initiale du champ dans l’interface utilisateur. Valeur par défaut : true. |

### getE {#getE--}
```
public final boolean getE()
```

Obtient un indicateur indiquant si le processeur PDF interactif doit fournir la prise en charge de la modification de la valeur du champ. Valeur par défaut : false

**Returns:**
valeur booléenne

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Obtient le type d’une valeur de champ dans une collection de schéma. Ce champ décrit le type de valeur correspondant à {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
Élément FieldValueType

### getN {#getN--}
```
public final String getN()
```

Obtient le nom de champ textuel qui doit être présenté à l’utilisateur par le processeur PDF interactif

**Returns:**
valeur String

### getO {#getO--}
```
public final Integer [] getO()
```

Obtient l’ordre relatif du nom de champ dans l’interface utilisateur. Les champs doivent être triés par le processeur PDF interactif par ordre croissant.

**Returns:**
tableau d’Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Obtient le sous‑type d’une valeur de champ dans une collection de schéma. Le sous‑type du champ de collection ou du champ lié à un fichier que ce dictionnaire décrit. Cette entrée identifie le type de données qui doit être stocké dans le champ.

**Returns:**
Élément CollectionFieldSubtype

### getV {#getV--}
```
public final boolean getV()
```

Obtient la visibilité initiale du champ dans l’interface utilisateur. Valeur par défaut : true.

**Returns:**
valeur booléenne
