---
title: "RunThreadCreateRequest.ToolChoice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété RunThreadCreateRequest. Obtient ou définit quel outil, le cas échéant, est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme type file_search ou type function avec le nom de fonction my_function oblige le modèle à appeler cet outil."
type: docs
weight: 120
url: /fr/net/aspose.pdf.ai/runthreadcreaterequest/toolchoice/
---
## RunThreadCreateRequest.ToolChoice property

Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {\"type\": \"file_search\"} ou {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} oblige le modèle à appeler cet outil.

```csharp
public string ToolChoice { get; set; }
```

### Voir aussi

* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


