---
title: "Classe TextDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "classe Aspose.Pdf.Devices.TextDevice. Rappresenta una classe per convertire le pagine del documento pdf in testo."
type: docs
weight: 3800
url: /it/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

Rappresenta una classe per convertire le pagine del documento pdf in testo.

```csharp
public sealed class TextDevice : PageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Inizializza una nuova istanza di `TextDevice` con la modalità di formattazione Raw text e la codifica Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Inizializza una nuova istanza di `TextDevice` per la codifica specificata. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Inizializza una nuova istanza di `TextDevice` con le opzioni di estrazione del testo. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Inizializza una nuova istanza di `TextDevice` per la codifica specificata con le opzioni di estrazione del testo. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Ottiene o imposta la codifica del testo estratto. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Ottiene o imposta le opzioni di estrazione del testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Converti la pagina e salvala come stream di testo. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

## Osservazioni

L'oggetto `TextDevice` è fondamentalmente usato per estrarre testo da una pagina pdf.

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // crea dispositivo di testo
    TextDevice device = new TextDevice();

    // converti la pagina e salva il testo nello stream
    device.Process(doc.Pages[1], ms);

    // usa il testo estratto
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Vedi anche

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


