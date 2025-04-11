---
title: Enum PrinterMarksKind
second_title: Aspose.PDF for .NET API Reference
description: Indica i tipi di marche a stampa da aggiungere al documento.
type: docs
weight: 2380
url: /it/net/aspose.pdf.annotations/printermarkskind/
---
## Enumerazione PrinterMarksKind

Specifica i tipi di segni di stampa da aggiungere a un documento.

```csharp
[Flags]
public enum PrinterMarksKind
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nessuno | `0` | Specifica che non devono essere aggiunti segni di stampa. |
| SegniDiRifilo | `1` | Specifica che devono essere aggiunti segni di rifilo. |
| SegniDiSanguinamento | `2` | Specifica che devono essere aggiunti segni di sanguinamento. |
| SegniDiRegistrazione | `4` | Specifica che devono essere aggiunti segni di registrazione. |
| BarreColorate | `8` | Specifica che devono essere aggiunte barre colorate. |
| InformazioniPagina | `10` | Specifica che devono essere aggiunte informazioni sulla pagina. |
| Tutti | `1F` | Specifica che devono essere aggiunti tutti i tipi di segni di stampa. |

## Osservazioni

Questa enumerazione ha un attributo FlagsAttribute che consente una combinazione bitwise dei suoi valori membri.

### Vedi Anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)