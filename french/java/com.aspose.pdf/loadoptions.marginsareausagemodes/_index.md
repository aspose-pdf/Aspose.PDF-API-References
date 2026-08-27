---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le mode d'utilisation de la zone des marges lors de la conversion (comme HTML, EPUB, etc.), définit le traitement des instructions du format importé liées à l'utilisation des marges."
type: docs
weight: 2800
url: /fr/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Représente le mode d'utilisation de la zone des marges lors de la conversion (comme HTML, EPUB, etc.), définit le traitement des instructions du format importé liées à l'utilisation des marges.

## Champs

| Champ | Description |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Ce mode interdit strictement l'utilisation de la zone des marges, ainsi le convertisseur n'utilisera jamais la zone des marges pour le rendu, même si le CSS ou le format du document source le permet ou l'exige. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | Dans ce mode, le convertisseur respecte le format du document importé (par ex. le CSS du HTML importé) dans l'utilisation de la zone des marges. Ainsi, si le format du document importé nécessite l'utilisation de la zone des marges pour le rendu, le convertisseur le permettra. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Ce mode interdit strictement l'utilisation de la zone des marges, ainsi le convertisseur n'utilisera jamais la zone des marges pour le rendu, même si le CSS ou le format du document source le permet ou l'exige.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

Dans ce mode, le convertisseur respecte le format du document importé (par ex. le CSS du HTML importé) dans l'utilisation de la zone des marges. Ainsi, si le format du document importé nécessite l'utilisation de la zone des marges pour le rendu, le convertisseur le permettra.
