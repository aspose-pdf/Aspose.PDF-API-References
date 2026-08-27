---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Champ SvgSaveOptions. Cette option définit si un répertoire cible sera créé, le cas échéant, avec le même nom que le fichier de sortie demandé, au lieu du fichier de sortie lui‑-même. Ainsi, le répertoire contiendra toutes les images SVG de sortie des pages comme décrit ci‑dessous. Si aucun fichier de sortie de pages, autre que le premier, n’est créé exactement dans le répertoire demandé en tant que fichier de sortie principal, il contiendra dans son nom le suffixe _2...n qui est défini par le numéro de page, par ex. si vous définissez le fichier de sortie CAsposeTestsoutput.svg et que la sortie contient plusieurs fichiers svg des pages, alors les fichiers des pages seront également créés dans le répertoire CAsposeTests et auront les noms output.svg output_2.svg output_3.svg etc."
type: docs
weight: 50
url: /fr/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

Cette option définit si un répertoire cible (s'il n'existe pas encore) sera créé avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, le répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si l'option est désactivée, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contient plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg', etc.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Voir aussi

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


