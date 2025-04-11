---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TextDevice. Rappresenta la classe per convertire le pagine dei documenti pdf in testo
type: docs
weight: 3680
url: /it/net/aspose.pdf.devices/textdevice/
---
## Classe TextDevice

Rappresenta la classe per convertire le pagine dei documenti pdf in testo.

```csharp
public sealed class TextDevice : PageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Inizializza una nuova istanza di `TextDevice` con la modalità di formattazione del testo Raw e la codifica del testo Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Inizializza una nuova istanza di `TextDevice` per la codifica specificata. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Inizializza una nuova istanza di `TextDevice` con opzioni di estrazione del testo. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Inizializza una nuova istanza di `TextDevice` per la codifica specificata con opzioni di estrazione del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Ottiene o imposta la codifica del testo estratto. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Converte la pagina e la salva come flusso di testo. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

## Osservazioni

L'oggetto `TextDevice` è fondamentalmente utilizzato per estrarre testo dalla pagina pdf.

## Esempi

L'esempio dimostra come estrarre testo dalla prima pagina del documento PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Vedi Anche

* classe [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)