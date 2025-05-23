---
title: RunResponse.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Propriété RunResponse. Obtient ou définit quel outil, le cas échéant, est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme "type" "file_search" ou "type" "function", "function" "name" "my_function" force le modèle à appeler cet outil.
type: docs
weight: 230
url: /fr/net/aspose.pdf.ai/runresponse/toolchoice/
---
## Propriété RunResponse.ToolChoice

Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} force le modèle à appeler cet outil.

```csharp
public string ToolChoice { get; set; }
```

### Voir aussi

* classe [RunResponse](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)