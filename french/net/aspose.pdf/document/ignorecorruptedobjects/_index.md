---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: Propriété du document. Obtient ou définit le drapeau d'ignorance des erreurs dans les fichiers source. Lorsque des pages du document source sont copiées dans le document de destination, le processus de copie est arrêté avec une exception si certains objets dans les fichiers source sont corrompus lorsque ce drapeau est faux. Si ce drapeau est défini sur vrai, alors les objets corrompus seront remplacés par des valeurs vides. Par défaut  vrai
type: docs
weight: 270
url: /fr/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Propriété Document.IgnoreCorruptedObjects

Obtient ou définit le drapeau d'ignorance des erreurs dans les fichiers source. Lorsque des pages du document source sont copiées dans le document de destination, le processus de copie est arrêté avec une exception si certains objets dans les fichiers source sont corrompus lorsque ce drapeau est faux. exemple : dest.Pages.Add(src.Pages); Si ce drapeau est défini sur vrai, alors les objets corrompus seront remplacés par des valeurs vides. Par défaut : vrai.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Voir aussi

* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)