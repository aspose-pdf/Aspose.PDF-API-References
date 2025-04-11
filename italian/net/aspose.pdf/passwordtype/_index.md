---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Enum PasswordType di Aspose.Pdf. Questo enum rappresenta i tipi di password noti utilizzati per documenti pdf protetti da password
type: docs
weight: 8290
url: /it/net/aspose.pdf/passwordtype/
---
## Enumerazione PasswordType

Questo enum rappresenta i tipi di password noti utilizzati per documenti pdf protetti da password.

```csharp
public enum PasswordType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nessuno | `0` | Il documento Pdf non è protetto da password. |
| Utente | `1` | Il documento Pdf è stato aperto utilizzando la password di apertura del documento (accesso ristretto). |
| Proprietario | `2` | Il documento Pdf è stato aperto utilizzando la password per modificare i permessi (accesso completo). |
| Inaccessibile | `3` | Il documento Pdf è protetto da password ma sia le password utente che proprietario non sono vuote e nessuna delle password è stata definita o la password fornita era errata. Quindi è impossibile dedurre il tipo di password. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)