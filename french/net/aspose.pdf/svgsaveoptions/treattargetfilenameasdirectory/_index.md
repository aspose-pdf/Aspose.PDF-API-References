---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: Champ SvgSaveOptions. Cette option définit si un répertoire cible sera créé s'il n'est pas encore présent avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie demandé lui-même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages comme décrit ci-dessous. Si aucun fichier de sortie des pages autre que le premier n'est créé exactement dans le répertoire demandé comme fichier de sortie principal, mais contiendra dans le nom de fichier le suffixe _2...n qui est défini par le numéro de page, par exemple, si vous définissez le fichier de sortie "C:\AsposeTests\output.svg" et que la sortie contiendra plusieurs fichiers svg des pages, alors les fichiers des pages seront également créés dans le répertoire "C:\AsposeTests\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg', etc.
type: docs
weight: 50
url: /fr/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## Champ SvgSaveOptions.TreatTargetFileNameAsDirectory

Cette option définit si un répertoire cible sera créé (s'il n'est pas encore présent) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie demandé lui-même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci-dessous). Si non, les fichiers de sortie des pages autres que le premier seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais contiendront dans le nom de fichier le suffixe _[2...n], qui est défini par le numéro de page, par exemple, si vous définissez le fichier de sortie "C:\AsposeTests\output.svg" et que la sortie contiendra plusieurs fichiers svg des pages, alors les fichiers des pages seront également créés dans le répertoire "C:\AsposeTests\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg', etc.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Voir aussi

* classe [SvgSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)