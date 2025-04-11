---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: Campo SvgSaveOptions. Questa opzione definisce se verrà creata una directory di destinazione se non presente, con lo stesso nome del file di output richiesto invece del file di output stesso. In questo modo, la directory conterrà tutte le immagini SVG di output delle pagine come descritto di seguito. Se non verranno creati file di output delle pagine diversi dal primo, verranno creati esattamente nella directory richiesta come file di output principale, ma conterranno nel nome del file il suffisso _2...n, definito dal numero di pagina, ad esempio, se definisci il file di output "C:\AsposeTests\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine verranno creati anche nella directory "C:\AsposeTests\" e avranno nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc.
type: docs
weight: 50
url: /it/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## Campo SvgSaveOptions.TreatTargetFileNameAsDirectory

Questa opzione definisce se verrà creata una directory di destinazione (se non presente) con lo stesso nome del file di output richiesto invece del file di output stesso. In questo modo, la directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diversi dal primo verranno creati esattamente nella directory richiesta come file di output principale, ma conterranno nel nome del file il suffisso _[2...n], definito dal numero di pagina, ad esempio, se definisci il file di output "C:\AsposeTests\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine verranno creati anche nella directory "C:\AsposeTests\" e avranno nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Vedi Anche

* classe [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)