---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété CompletionCreateRequest. Obtient ou définit un objet qui contrôle quel outil, le cas échéant, est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils. Spécifier un outil particulier via type function function name my_function force le modèle à appeler cet outil. none est la valeur par défaut lorsqu'aucun outil n'est présent. auto est la valeur par défaut si des outils sont présents."
type: docs
weight: 150
url: /fr/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

Obtient ou définit un objet qui contrôle quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils. Spécifier un outil particulier via {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} force le modèle à appeler cet outil. none est la valeur par défaut lorsqu'aucun outil n'est présent. auto est la valeur par défaut si des outils sont présents.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Voir aussi

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


