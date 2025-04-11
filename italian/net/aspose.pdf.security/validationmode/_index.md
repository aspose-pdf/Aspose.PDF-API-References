---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode enum. Specifies the validation mode for PDF signature validation processes
type: docs
weight: 10060
url: /it/net/aspose.pdf.security/validationmode/
---
## Enumerazione ValidationMode

Specifica la modalità di validazione per i processi di validazione della firma PDF.

```csharp
public enum ValidationMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Rappresenta una modalità in cui la validazione non viene eseguita. |
| OnlyCheck | `1` | Rappresenta la modalità in cui viene effettuata la validazione, ma il suo risultato non influisce sulla validazione della firma digitale. Puoi controllare tu stesso il risultato della validazione. |
| Strict | `2` | Rappresenta la modalità in cui viene effettuata la validazione e il suo risultato influisce sulla validazione della firma digitale. Se il certificato non può essere verificato, allora la firma digitale sarà considerata non valida. Puoi controllare tu stesso il risultato della validazione. |

### Vedi Anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)