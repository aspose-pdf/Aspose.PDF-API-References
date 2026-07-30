---
title: "RunCreateRequest.ResponseFormat"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété RunCreateRequest. Obtient ou définit le format de réponse. Spécifie le format que le modèle doit produire. Compatible avec GPT4o, GPT4 Turbo et tous les modèles GPT3.5 Turbo depuis gpt3.5turbo1106. Le définir sur type json_object active le mode JSON qui garantit que le message généré par le modèle est un JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux infini d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, entraînant une requête longue et apparemment bloquée. Notez également que le contenu du message peut être partiellement tronqué si finish_reasonlength indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte."
type: docs
weight: 100
url: /fr/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat property

Obtient ou définit le format de réponse. Spécifie le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Le définir sur { \"type\": \"json_object\" } active le mode JSON, qui garantit que le message généré par le modèle est du JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous‑même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux infini d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, entraînant une requête longue et apparemment « stuck ». Notez également que le contenu du message peut être partiellement tronqué si finish_reason=\"length\", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Voir aussi

* class [ResponseFormat](../../responseformat/)
* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


