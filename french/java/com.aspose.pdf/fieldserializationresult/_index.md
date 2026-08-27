---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le résultat d'un processus de sérialisation de champ de formulaire."
type: docs
weight: 1390
url: /fr/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Représente le résultat d'un processus de sérialisation de champ de formulaire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Initialise une nouvelle instance de la classe {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Initialise une nouvelle instance de la classe {@link FieldSerializationResult}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Obtient les messages d'erreur associés au processus de sérialisation. Valeur : un ensemble de messages d'erreur. |
| [getFieldFullName](#getFieldFullName--) | Obtient le nom complet du champ. Valeur : le nom complet du champ. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Obtient le statut de la sérialisation du champ de formulaire. Valeur : le statut de sérialisation du champ de formulaire. |
| [getWarningMessages](#getWarningMessages--) | Obtient les messages d'avertissement associés au processus de sérialisation. Valeur : un ensemble de messages d'avertissement. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Met à jour le statut de la sérialisation et ajoute un message à l'ensemble approprié. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Initialise une nouvelle instance de la classe {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Initialise une nouvelle instance de la classe {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Obtient les messages d'erreur associés au processus de sérialisation. Valeur : un ensemble de messages d'erreur.

**Returns:**
HashSet d'instances String

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Obtient le nom complet du champ. Valeur : le nom complet du champ.

**Returns:**
valeur String

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Obtient le statut de la sérialisation du champ de formulaire. Valeur : le statut de sérialisation du champ de formulaire.

**Returns:**
Élément FieldSerializationStatus

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Obtient les messages d'avertissement associés au processus de sérialisation. Valeur : un ensemble de messages d'avertissement.

**Returns:**
HashSet d'instances String

### updateStatus {#updateStatus-int-java.lang.String-}
Met à jour le statut de la sérialisation et ajoute un message à l'ensemble approprié.
