---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Facades.KeySize. Définit différentes tailles de clé qui peuvent être utilisées pour chiffrer des documents pdf
type: docs
weight: 4390
url: /fr/net/aspose.pdf.facades/keysize/
---
## Énumération KeySize

Définit différentes tailles de clé qui peuvent être utilisées pour chiffrer des documents pdf.

```csharp
public enum KeySize
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| x40 | `0` | Clé de 40 bits. Une telle taille de clé est utilisée avec l'algorithme RC4 et fournit un faible niveau de sécurité. Néanmoins, les anciennes versions des documents pdf peuvent être chiffrées uniquement avec de telles clés (v. 1.3 et inférieures); |
| x128 | `1` | Clé de 128 bits. Les algorithmes RC4 et AES peuvent utiliser une telle taille de clé. |
| x256 | `2` | Clé de 256 bits. Une telle taille de clé ne peut être utilisée qu'avec AES et est reconnue par les dernières versions d'Adobe Reader (à partir de la v.9). |

### Voir aussi

* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)