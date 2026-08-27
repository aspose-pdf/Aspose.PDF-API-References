---
title: "UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "UnifiedSaveOptions field. Parfois, les PDF contiennent des images d'arrière‑plan de pages ou de cellules de tableau construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles, par ex. MsWord pour le format DOCS, génèrent parfois des bordures visibles entre les parties des images d'arrière‑plan parce que leurs techniques de lissage des bords d'image et d'anticrénelage diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d'arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION Cette optimisation de la qualité ralentit généralement considérablement la conversion, veuillez donc n’utiliser cette option que lorsqu’elle est réellement nécessaire."
type: docs
weight: 40
url: /fr/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### Voir aussi

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


