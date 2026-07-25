---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une énumération définissant la méthode utilisée pour la validation de certificat."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Représente une énumération définissant la méthode utilisée pour la validation de certificat.

## Champs

| Champ | Description |
| --- | --- |
| [All](#All) | Utilise toutes les méthodes disponibles (OCSP et CRL) pour la validation des certificats. |
| [Auto](#Auto) | Détermine automatiquement la meilleure méthode pour la validation des certificats. |
| [Crl](#Crl) | Valide les certificats en utilisant la méthode de liste de révocation de certificats (CRL). |
| [Ocsp](#Ocsp) | Utilise le protocole Online Certificate Status Protocol (OCSP) pour la validation des certificats. OCSP est un protocole qui fournit le statut de validation d'un certificat en interrogeant directement l'autorité de certification (CA) émettrice. |

### All {#All}
```
public static final int All
```

Utilise toutes les méthodes disponibles (OCSP et CRL) pour la validation des certificats.

### Auto {#Auto}
```
public static final int Auto
```

Détermine automatiquement la meilleure méthode pour la validation des certificats.

### Crl {#Crl}
```
public static final int Crl
```

Valide les certificats en utilisant la méthode de liste de révocation de certificats (CRL).

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Utilise le protocole Online Certificate Status Protocol (OCSP) pour la validation des certificats. OCSP est un protocole qui fournit le statut de validation d'un certificat en interrogeant directement l'autorité de certification (CA) émettrice.
