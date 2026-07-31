---
title: "Classe PsLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.PsLoadOptions class. Rappresenta le opzioni per il caricamento/importazione di .mhtfile in un documento pdf."
type: docs
weight: 9880
url: /it/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Rappresenta le opzioni per il caricamento/importazione di file .mht in un documento pdf.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | Specifica se salvare i font non TrueType in TTF. Riduce in modo significativo il volume del documento risultante nella conversione da PS a PDF e aumenta la velocità di conversione dei file PS con una grande quantità di testo in font non TrueType in qualsiasi formato di output. Tuttavia, si verifica un piccolo spostamento verticale del testo durante la conversione del file PostSctipt in immagine. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Ottiene o imposta i percorsi delle cartelle dei font. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


