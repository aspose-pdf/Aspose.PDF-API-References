---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Enum KeySize di Aspose.Pdf.Facades. Definisce diverse dimensioni delle chiavi che possono essere utilizzate per crittografare documenti pdf
type: docs
weight: 4390
url: /it/net/aspose.pdf.facades/keysize/
---
## Enumerazione KeySize

Definisce diverse dimensioni delle chiavi che possono essere utilizzate per crittografare documenti pdf.

```csharp
public enum KeySize
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| x40 | `0` | Chiave a 40 bit. Tale dimensione della chiave è utilizzata con l'algoritmo RC4 e fornisce un basso livello di sicurezza. Tuttavia, le vecchie versioni dei documenti pdf possono essere crittografate solo con tali chiavi (v. 1.3 e inferiori); |
| x128 | `1` | Chiave a 128 bit. Sia gli algoritmi RC4 che AES possono utilizzare tale dimensione della chiave. |
| x256 | `2` | Chiave a 256 bit. Tale dimensione della chiave può essere utilizzata solo con AES ed è riconosciuta con le ultime versioni di Adobe Reader (a partire dalla v.9). |

### Vedi Anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)