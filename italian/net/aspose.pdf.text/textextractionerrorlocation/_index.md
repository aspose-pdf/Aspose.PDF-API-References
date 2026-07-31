---
title: "Classe TextExtractionErrorLocation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.TextExtractionErrorLocation. Rappresenta la posizione nel PDF document dove è comparso l'errore di estrazione del testo"
type: docs
weight: 11060
url: /it/net/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class

Rappresenta la posizione nel documento PDF in cui è comparso l'errore di estrazione del testo.

```csharp
public sealed class TextExtractionErrorLocation
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FontUsedKey](../../aspose.pdf.text/textextractionerrorlocation/fontusedkey/) { get; } | Chiave (nome) dell'oggetto PDF Font utilizzata per la visualizzazione dell'operatore che causa l'errore di estrazione del testo. |
| [FormKey](../../aspose.pdf.text/textextractionerrorlocation/formkey/) { get; } | Chiave (nome) del PDF Form XObject in cui è stato individuato l'errore di estrazione del testo nel flusso dei contenuti. Non vuoto se ObjectType == 'xForm'. |
| [ObjectType](../../aspose.pdf.text/textextractionerrorlocation/objecttype/) { get; } | Tipo dell'oggetto PDF (Page o xForm) in cui è stato individuato l'errore di estrazione del testo nel flusso dei contenuti. |
| [OperatorIndex](../../aspose.pdf.text/textextractionerrorlocation/operatorindex/) { get; } | Indice dell'operatore di visualizzazione del testo nel flusso dei contenuti (collezione di operatori) che causa l'errore di estrazione del testo. |
| [OperatorString](../../aspose.pdf.text/textextractionerrorlocation/operatorstring/) { get; } | Operatore di visualizzazione del testo che causa l'errore di estrazione del testo. |
| [PageNumber](../../aspose.pdf.text/textextractionerrorlocation/pagenumber/) { get; } | Numero della pagina del document dove è stato individuato l'errore di estrazione del testo. |
| [Path](../../aspose.pdf.text/textextractionerrorlocation/path/) { get; } | Posizione del PDF document dove è comparso l'errore di estrazione del testo. |
| [TextStartPoint](../../aspose.pdf.text/textextractionerrorlocation/textstartpoint/) { get; } | Chiave (nome) dell'oggetto PDF Font utilizzata per la visualizzazione dell'operatore che causa l'errore di estrazione del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.text/textextractionerrorlocation/tostring/)() | Restituisce la rappresentazione stringa. |

### Vedi anche

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


