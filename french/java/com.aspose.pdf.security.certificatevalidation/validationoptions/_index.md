---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de validation d'une signature numérique dans un document PDF."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Représente les options de validation d'une signature numérique dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Crée une instance de la classe {@link ValidationOptions}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation. Lorsque la propriété est définie, l'existence d'une chaîne de certificats sera vérifiée ; si elle est absente, le résultat de la vérification sera {@link ValidationStatus#Undefined}, ce qui correspond au comportement d'Adobe Acrobat. Si vous souhaitez uniquement vérifier le statut de révocation en ligne, définissez le champ sur {@code false}. La valeur par défaut est {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Obtient ou définit la durée du délai d'attente, en millisecondes, pour les opérations réseau pendant le processus de validation. La propriété RequestTimeout définit le temps maximal que le système doit attendre pour une réponse réseau lors de l'accès à des ressources en ligne, telles que le statut de révocation ou les serveurs OCSP. |
| [getValidationMethod](#getValidationMethod--) | Obtient ou définit la méthode utilisée pour valider un certificat. |
| [getValidationMode](#getValidationMode--) | Obtient ou définit le mode de validation des signatures numériques dans un document PDF. La propriété ValidationMode détermine le niveau de rigueur du processus de validation. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation. Lorsque la propriété est définie, l'existence d'une chaîne de certificats sera vérifiée ; si elle est absente, le résultat de la vérification sera {@link ValidationStatus#Undefined}, ce qui correspond au comportement d'Adobe Acrobat. Si vous souhaitez uniquement vérifier le statut de révocation en ligne, définissez le champ sur {@code false}. La valeur par défaut est {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Obtient ou définit la durée du délai d'attente, en millisecondes, pour les opérations réseau pendant le processus de validation. La propriété RequestTimeout définit le temps maximal que le système doit attendre pour une réponse réseau lors de l'accès à des ressources en ligne, telles que le statut de révocation ou les serveurs OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Obtient ou définit la méthode utilisée pour valider un certificat. |
| [setValidationMode](#setValidationMode-int-) | Obtient ou définit le mode de validation des signatures numériques dans un document PDF. La propriété ValidationMode détermine le niveau de rigueur du processus de validation. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Crée une instance de la classe {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation. Lorsque la propriété est définie, l'existence d'une chaîne de certificats sera vérifiée ; si elle est absente, le résultat de la vérification sera {@link ValidationStatus#Undefined}, ce qui correspond au comportement d'Adobe Acrobat. Si vous souhaitez uniquement vérifier le statut de révocation en ligne, définissez le champ sur {@code false}. La valeur par défaut est {@code false}.

**Returns:**
valeur booléenne

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Obtient ou définit la durée du délai d'attente, en millisecondes, pour les opérations réseau pendant le processus de validation. La propriété RequestTimeout définit le temps maximal que le système doit attendre pour une réponse réseau lors de l'accès à des ressources en ligne, telles que le statut de révocation ou les serveurs OCSP.

**Returns:**
valeur int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Obtient ou définit la méthode utilisée pour valider un certificat.

**Returns:**
Élément ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Obtient ou définit le mode de validation des signatures numériques dans un document PDF. La propriété ValidationMode détermine le niveau de rigueur du processus de validation.

**Returns:**
Élément ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Obtient ou définit une valeur indiquant si la chaîne de certificats doit être vérifiée pendant le processus de validation. Lorsque la propriété est définie, l'existence d'une chaîne de certificats sera vérifiée ; si elle est absente, le résultat de la vérification sera {@link ValidationStatus#Undefined}, ce qui correspond au comportement d'Adobe Acrobat. Si vous souhaitez uniquement vérifier le statut de révocation en ligne, définissez le champ sur {@code false}. La valeur par défaut est {@code false}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Obtient ou définit la durée du délai d'attente, en millisecondes, pour les opérations réseau pendant le processus de validation. La propriété RequestTimeout définit le temps maximal que le système doit attendre pour une réponse réseau lors de l'accès à des ressources en ligne, telles que le statut de révocation ou les serveurs OCSP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Obtient ou définit la méthode utilisée pour valider un certificat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Obtient ou définit le mode de validation des signatures numériques dans un document PDF. La propriété ValidationMode détermine le niveau de rigueur du processus de validation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ValidationMode |
