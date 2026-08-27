---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato Pdf"
type: docs
weight: 3790
url: /it/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Opzioni di salvataggio per l'esportazione in formato Pdf

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Nome del font usato per impostazione predefinita per i font che sono assenti sul computer. Quando il documento PDF che viene salvato in PDF contiene font che non sono disponibili nel documento stesso e sul dispositivo, l'API sostituisce questi font con il font predefinito (se il font con {@code DefaultFontName} è trovato sul dispositivo) |
| [getTempPath](#getTempPath--) | Percorso per i file temporanei. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Nome del font usato per impostazione predefinita per i font che sono assenti sul computer. Quando il documento PDF che viene salvato in PDF contiene font che non sono disponibili nel documento stesso e sul dispositivo, l'API sostituisce questi font con il font predefinito (se il font con {@code DefaultFontName} è trovato sul dispositivo) |
| [setTempPath](#setTempPath-java.lang.String-) | Percorso per i file temporanei. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Costruttore

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Nome del font usato per impostazione predefinita per i font che sono assenti sul computer. Quando il documento PDF che viene salvato in PDF contiene font che non sono disponibili nel documento stesso e sul dispositivo, l'API sostituisce questi font con il font predefinito (se il font con {@code DefaultFontName} è trovato sul dispositivo)

**Returns:**
valore String

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Percorso per i file temporanei.

**Returns:**
valore String

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Nome del font usato per impostazione predefinita per i font che sono assenti sul computer. Quando il documento PDF che viene salvato in PDF contiene font che non sono disponibili nel documento stesso e sul dispositivo, l'API sostituisce questi font con il font predefinito (se il font con {@code DefaultFontName} è trovato sul dispositivo)

### setTempPath {#setTempPath-java.lang.String-}
Percorso per i file temporanei.
