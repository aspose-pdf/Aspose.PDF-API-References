---
title: "Document.IgnoreCorruptedObjects"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Document. Obtient ou définit le drapeau d'ignorance des erreurs dans les fichiers source. Lorsque les pages du document source sont copiées dans le document de destination, le processus de copie s'arrête avec une exception si certains objets des fichiers source sont corrompus lorsque ce drapeau est faux. exemple dest.Pages.Addsrc.Pages Si ce drapeau est vrai, les objets corrompus seront remplacés par des valeurs vides. Vrai par défaut"
type: docs
weight: 290
url: /fr/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

Obtient ou définit le drapeau d'ignorance des erreurs dans les fichiers source. Lorsque des pages du document source sont copiées dans le document de destination, le processus de copie s'arrête avec une exception si certains objets des fichiers source sont corrompus lorsque ce drapeau est à false. Exemple : dest.Pages.Add(src.Pages); Si ce drapeau est réglé sur true, les objets corrompus seront remplacés par des valeurs vides. Par défaut : true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Voir aussi

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


