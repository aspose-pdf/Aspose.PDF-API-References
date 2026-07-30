---
title: "Énum ValidationMethod"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énum Aspose.Pdf.Security.ValidationMethod. Représente un énum définissant la méthode utilisée pour la validation de certificat."
type: docs
weight: 10230
url: /fr/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

Représente une énumération définissant la méthode utilisée pour la validation des certificats.

```csharp
public enum ValidationMethod
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Détermine automatiquement la meilleure méthode pour la validation de certificat. |
| Ocsp | `1` | Utilise le protocole Online Certificate Status Protocol (OCSP) pour la validation de certificat. OCSP est un protocole qui fournit le statut de validation d'un certificat en interrogeant directement l'autorité de certification (CA) émettrice. |
| Crl | `2` | Valide les certificats en utilisant la méthode Certificate Revocation List (CRL). |
| All | `3` | Utilise toutes les méthodes disponibles (OCSP et CRL) pour la validation de certificat. |

### Voir aussi

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


