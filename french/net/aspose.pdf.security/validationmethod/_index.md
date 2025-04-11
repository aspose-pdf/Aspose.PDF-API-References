---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMethod d'Aspose.Pdf.Security. Représente une énumération définissant la méthode utilisée pour la validation des certificats
type: docs
weight: 10050
url: /fr/net/aspose.pdf.security/validationmethod/
---
## Énumération ValidationMethod

Représente une énumération définissant la méthode utilisée pour la validation des certificats.

```csharp
public enum ValidationMethod
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Détermine automatiquement la meilleure méthode pour la validation des certificats. |
| Ocsp | `1` | Utilise le protocole de statut de certificat en ligne (OCSP) pour la validation des certificats. OCSP est un protocole qui fournit le statut de validation d'un certificat en interrogeant directement l'autorité de certification (CA) émettrice. |
| Crl | `2` | Valide les certificats en utilisant la méthode de liste de révocation de certificats (CRL). |
| All | `3` | Utilise toutes les méthodes disponibles (OCSP et CRL) pour la validation des certificats. |

### Voir aussi

* espace de noms [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)