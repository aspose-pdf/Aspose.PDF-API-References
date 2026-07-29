---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato SVG"
type: docs
weight: 4720
url: /it/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Opzioni di salvataggio per l'esportazione in formato SVG

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Questo campo può contenere una strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate create (come BMP o JPEG incorporati) incorporati nello SVG salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nello SVG generato. Se l'elaborazione di questo o di quell'altro file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non esistesse alcun codice personalizzato esterno. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Specifica se l'output verrà creato come un unico archivio zip. Si prega di fare riferimento al commento delle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output. |
| [isScaleToPixels](#isScaleToPixels--) | Specifica se scalare il documento di output da punti tipografici a pixel. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Questa opzione definisce se verrà creata una directory di destinazione (se ancora assente) con lo stesso nome del file di output richiesto invece del file di output stesso. In tal caso, quella directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta come file di output principale, ma con un suffisso _[2...n] nel nome file, definito dal numero di pagina, per es. se si definisce il file di output "C:\\AsposeTests\\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine saranno creati anche nella directory "C:\\AsposeTests\\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Specifica se l'output verrà creato come un unico archivio zip. Si prega di fare riferimento al commento delle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate creati (come BMP o JPEG incorporati) incorporati nello SVG salvato. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Specifica se scalare il documento di output da punti tipografici a pixel. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Questa opzione definisce se verrà creata una directory di destinazione (se ancora assente) con lo stesso nome del file di output richiesto invece del file di output stesso. In tal caso, quella directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta come file di output principale, ma con un suffisso _[2...n] nel nome file, definito dal numero di pagina, per es. se si definisce il file di output "C:\\AsposeTests\\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine saranno creati anche nella directory "C:\\AsposeTests\\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Costruttore

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Questo campo può contenere una strategia di salvataggio che deve essere utilizzata (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate create (come BMP o JPEG incorporati) incorporati nello SVG salvato. Tale strategia deve elaborare le risorse e restituire una stringa che rappresenta l'URI desiderato della risorsa salvata nello SVG generato. Se l'elaborazione di questo o di quell'altro file per qualche motivo deve essere eseguita dal codice del convertitore stesso, non dal codice personalizzato, impostare nel codice personalizzato il flag 'CustomProcessingCancelled' della variabile del parametro 'imageSavingInfo'. Questo segnala al convertitore che tutti i passaggi necessari per l'elaborazione di quella risorsa devono essere eseguiti nel convertitore stesso come se non esistesse alcun codice personalizzato esterno.

**Returns:**
Istanza di EmbeddedImagesSavingStrategy

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Specifica se l'output verrà creato come un unico archivio zip. Si prega di fare riferimento al commento delle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output.

**Returns:**
valore booleano

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Specifica se scalare il documento di output da punti tipografici a pixel.

**Returns:**
valore booleano

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Questa opzione definisce se verrà creata una directory di destinazione (se ancora assente) con lo stesso nome del file di output richiesto invece del file di output stesso. In tal caso, quella directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta come file di output principale, ma con un suffisso _[2...n] nel nome file, definito dal numero di pagina, per es. se si definisce il file di output "C:\\AsposeTests\\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine saranno creati anche nella directory "C:\\AsposeTests\\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc.

**Returns:**
valore booleano

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Specifica se l'output verrà creato come un unico archivio zip. Si prega di fare riferimento al commento delle opzioni 'TreatTargetFileNameAsDirectory' per vedere le regole di denominazione dei file svg delle pagine per documenti sorgente multipagina, che sono applicate anche al set compresso di file di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compressOutputToZipArchive |  | valore booleano |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Questo campo può contenere la strategia di salvataggio da utilizzare (se presente) durante la conversione per la gestione personalizzata dei file di immagini esterne referenziate creati (come BMP o JPEG incorporati) incorporati nello SVG salvato.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Specifica se scalare il documento di output da punti tipografici a pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleToPixels |  | valore booleano |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Questa opzione definisce se verrà creata una directory di destinazione (se ancora assente) con lo stesso nome del file di output richiesto invece del file di output stesso. In tal caso, quella directory conterrà tutte le immagini SVG di output delle pagine (come descritto di seguito). Se no, i file di output delle pagine diverse dalla prima verranno creati esattamente nella directory richiesta come file di output principale, ma con un suffisso _[2...n] nel nome file, definito dal numero di pagina, per es. se si definisce il file di output "C:\\AsposeTests\\output.svg" e l'output conterrà diversi file svg delle pagine, allora i file delle pagine saranno creati anche nella directory "C:\\AsposeTests\\" e avranno i nomi 'output.svg', 'output_2.svg', 'output_3.svg' ecc.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | valore booleano |
