---
title: KeySize
second_title: Référence de l'API Aspose.PDF pour .NET
description: Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf.
type: docs
weight: 2400
url: /fr/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf.

```csharp
public enum KeySize
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| x40 | `0` | clé 40 bits. Une telle taille de clé est utilisée avec l'algorithme RC4 et offre un faible niveau de sécurité. Néanmoins, les anciennes versions de documents pdf ne peuvent être cryptées qu'avec de telles clés (v. 1.3 et inférieure); |
| x128 | `1` | clé 128 bits. Les algorithmes RC4 et AES peuvent utiliser une telle taille de clé. |
| x256 | `2` | clé 256 bits. Cette taille de clé ne peut être utilisée qu'avec AES et est reconnue avec les dernières versions d'Adobe Reader (à partir de la v.9). |

### Voir également

* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->