---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de vérifier la compromission des signatures numériques du document."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Représente une classe permettant de vérifier la compromission des signatures numériques du document.

## Champs

| Champ | Description |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Obtient une collection de signatures numériques qui ont été identifiées comme compromises. Cette propriété contient la liste de toutes les signatures compromises détectées dans le document. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Obtient l'état de couverture des signatures numériques dans un document. S'il est égal à {@code SignaturesCoverage#Undefined}, alors l'une des signatures est compromise. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Indique s'il existe des signatures numériques compromises dans le document. Renvoie true si au moins une signature est compromise ; sinon, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Obtient une collection de signatures numériques qui ont été identifiées comme compromises. Cette propriété contient la liste de toutes les signatures compromises détectées dans le document.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Obtient l'état de couverture des signatures numériques dans un document. S'il est égal à {@code SignaturesCoverage#Undefined}, alors l'une des signatures est compromise.

**Returns:**
Élément SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Indique s'il existe des signatures numériques compromises dans le document. Renvoie true si au moins une signature est compromise ; sinon, false.

**Returns:**
valeur booléenne
