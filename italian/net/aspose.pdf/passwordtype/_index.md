---
title: "Enum PasswordType"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.PasswordType. Questa enum rappresenta i tipi di password noti utilizzati per i documenti PDF protetti da password."
type: docs
weight: 8430
url: /it/net/aspose.pdf/passwordtype/
---
## PasswordType enumeration

Questa enumerazione rappresenta i tipi di password noti utilizzati per documenti PDF protetti da password.

```csharp
public enum PasswordType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Il documento PDF non è protetto da password. |
| User | `1` | Il documento PDF è stato aperto usando la password di apertura del documento (accesso limitato). |
| Owner | `2` | Il documento PDF è stato aperto usando la password per modificare i permessi (accesso completo). |
| Inaccessible | `3` | Il documento PDF è protetto da password, ma sia la password utente sia quella del proprietario non sono vuote e nessuna delle password è stata definita o la password fornita era errata. Pertanto è impossibile dedurre il tipo di password. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


