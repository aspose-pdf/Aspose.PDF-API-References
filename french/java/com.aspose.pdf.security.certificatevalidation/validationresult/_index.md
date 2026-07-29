---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le résultat d'un processus de validation pour un certificat. La classe ValidationResult fournit des informations sur le résultat de la validation d'un certificat, y compris le sien."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Représente le résultat d'un processus de validation d'un certificat. La classe ValidationResult fournit des informations sur le résultat de la validation d'un certificat, y compris son statut et un message décrivant les problèmes rencontrés lors de la validation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Crée une instance de la classe {@link ValidationResult}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getMessage](#getMessage--) | Représente le message associé au résultat de la validation. La propriété Message fournit un contexte supplémentaire ou des informations sur l'état du résultat de la validation. |
| [getStatus](#getStatus--) | Obtient le statut du processus de validation d'un certificat. La propriété Status indique le résultat de la validation du certificat. Les valeurs possibles sont définies dans l'énumération {@link ValidationStatus}, telles que Valid, Invalid ou Undefined. Elle fournit un aperçu de la réussite ou non des contrôles de validation du certificat. |
| [setMessage](#setMessage-java.lang.String-) | Représente le message associé au résultat de la validation. La propriété Message fournit un contexte supplémentaire ou des informations sur l'état du résultat de la validation. |
| [setStatus](#setStatus-int-) | Obtient le statut du processus de validation d'un certificat. La propriété Status indique le résultat de la validation du certificat. Les valeurs possibles sont définies dans l'énumération {@link ValidationStatus}, telles que Valid, Invalid ou Undefined. Elle fournit un aperçu de la réussite ou non des contrôles de validation du certificat. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Crée une instance de la classe {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Représente le message associé au résultat de la validation. La propriété Message fournit un contexte supplémentaire ou des informations sur l'état du résultat de la validation.

**Returns:**
valeur String

### getStatus {#getStatus--}
```
public final int getStatus()
```

Obtient le statut du processus de validation d'un certificat. La propriété Status indique le résultat de la validation du certificat. Les valeurs possibles sont définies dans l'énumération {@link ValidationStatus}, telles que Valid, Invalid ou Undefined. Elle fournit un aperçu de la réussite ou non des contrôles de validation du certificat.

**Returns:**
Élément ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Représente le message associé au résultat de la validation. La propriété Message fournit un contexte supplémentaire ou des informations sur l'état du résultat de la validation.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Obtient le statut du processus de validation d'un certificat. La propriété Status indique le résultat de la validation du certificat. Les valeurs possibles sont définies dans l'énumération {@link ValidationStatus}, telles que Valid, Invalid ou Undefined. Elle fournit un aperçu de la réussite ou non des contrôles de validation du certificat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ValidationStatus |
