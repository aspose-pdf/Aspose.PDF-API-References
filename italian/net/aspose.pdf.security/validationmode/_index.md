---
title: "Enum ValidationMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Security.ValidationMode enum. Specifica la modalità di convalida per i processi di convalida della firma PDF"
type: docs
weight: 10240
url: /it/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

Specifica la modalità di convalida per i processi di validazione delle firme PDF.

```csharp
public enum ValidationMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Rappresenta una modalità in cui la convalida non viene eseguita. |
| OnlyCheck | `1` | Rappresenta la modalità in cui la convalida viene effettuata, ma il suo risultato non influisce sulla convalida della firma digitale. È possibile verificare autonomamente il risultato della convalida. |
| Strict | `2` | Rappresenta la modalità in cui la convalida viene effettuata e il suo risultato influisce sulla convalida della firma digitale. Se il certificato non può essere verificato, la firma digitale sarà considerata non valida. È possibile verificare autonomamente il risultato della convalida. |

### Vedi anche

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


