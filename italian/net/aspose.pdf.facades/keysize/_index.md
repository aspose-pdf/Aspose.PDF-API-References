---
title: "Enum KeySize"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Facades.KeySize. Definisce diverse dimensioni di chiave che possono essere utilizzate per crittografare documenti pdf"
type: docs
weight: 4510
url: /it/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

Definisce diverse dimensioni di chiave che possono essere usate per crittografare documenti pdf.

```csharp
public enum KeySize
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| x40 | `0` | Chiave a 40 bit. Questa dimensione di chiave è usata con l'algoritmo RC4 e fornisce un basso livello di sicurezza. Tuttavia le versioni più vecchie dei documenti pdf possono essere crittografate solo con tali chiavi (v. 1.3 e inferiori); |
| x128 | `1` | Chiave a 128 bit. Sia l'algoritmo RC4 che quello AES possono utilizzare questa dimensione di chiave. |
| x256 | `2` | Chiave a 256 bit. Questa dimensione di chiave può essere usata solo con AES ed è riconosciuta dalle ultime versioni di Adobe Reader (a partire dalla v.9). |

### Vedi anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


