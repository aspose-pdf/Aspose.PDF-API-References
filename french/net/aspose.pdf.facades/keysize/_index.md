---
title: "Énumération KeySize"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Facades.KeySize. Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf"
type: docs
weight: 4510
url: /fr/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf.

```csharp
public enum KeySize
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| x40 | `0` | Clé de 40 bits. Cette taille de clé est utilisée avec l'algorithme RC4 et offre un faible niveau de sécurité. Néanmoins, les anciennes versions de documents pdf ne peuvent être chiffrées qu'avec de telles clés (v. 1.3 et antérieures) ; |
| x128 | `1` | Clé de 128 bits. Les algorithmes RC4 et AES peuvent tous deux utiliser cette taille de clé. |
| x256 | `2` | Clé de 256 bits. Cette taille de clé ne peut être utilisée qu'avec AES et est reconnue par les dernières versions d'Adobe Reader (à partir de la v.9). |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


