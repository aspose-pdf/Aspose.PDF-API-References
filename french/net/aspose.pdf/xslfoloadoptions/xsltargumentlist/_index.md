---
title: XslFoLoadOptions.XsltArgumentList
second_title: Aspose.PDF for .NET API Reference
description: Propriété XslFoLoadOptions. XsltArgumentList pour insérer des valeurs dans des paramètres xls existants. Le fichier XLS a un paramètre 'animal' sans valeur. maintenant le convertisseur suppose qu'il y a un paramètre 'animal' avec la valeur 'cat' dans le fichier XLS.
type: docs
weight: 30
url: /fr/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/
---
## Propriété XslFoLoadOptions.XsltArgumentList

XslArgumentList pour insérer des valeurs dans des paramètres xls existants. Le fichier XLS a un paramètre 'animal' sans valeur : XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); maintenant le convertisseur suppose qu'il y a un paramètre 'animal' avec la valeur 'cat' dans le fichier XLS.

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

### Voir aussi

* classe [XslFoLoadOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)