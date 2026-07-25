---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie le mode de validation pour les processus de validation de signature PDF."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Spécifie le mode de validation pour les processus de validation de signature PDF.

## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Représente un mode où la validation n'est pas effectuée. |
| [OnlyCheck](#OnlyCheck) | Représente le mode dans lequel la validation est effectuée, mais son résultat n'affecte pas la validation de la signature numérique. Vous pouvez vérifier le résultat de la validation vous-même. |
| [Strict](#Strict) | Représente le mode dans lequel la validation est effectuée et son résultat affecte la validation de la signature numérique. Si le certificat n'a pas pu être vérifié, alors la signature numérique sera considérée comme invalide. Vous pouvez vérifier le résultat de la validation vous-même. |

### None {#None}
```
public static final int None
```

Représente un mode où la validation n'est pas effectuée.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Représente le mode dans lequel la validation est effectuée, mais son résultat n'affecte pas la validation de la signature numérique. Vous pouvez vérifier le résultat de la validation vous-même.

### Strict {#Strict}
```
public static final int Strict
```

Représente le mode dans lequel la validation est effectuée et son résultat affecte la validation de la signature numérique. Si le certificat n'a pas pu être vérifié, alors la signature numérique sera considérée comme invalide. Vous pouvez vérifier le résultat de la validation vous-même.
