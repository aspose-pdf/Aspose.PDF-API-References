---
title: Convert
second_title: Aspose.PDF per .NET API Reference
description: Converte il file di origine nel formato di origine nel file di destinazione nel formato di destinazione.
type: docs
weight: 790
url: /it/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converte il file di origine nel formato di origine nel file di destinazione nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del file di origine. |
| loadOptions | LoadOptions | Il formato del file di origine. |
| dstFileName | String | Il nome del file di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converte il flusso nel formato di origine nel file di destinazione nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | Il flusso di origine. |
| loadOptions | LoadOptions | Il formato del flusso di origine. |
| dstFileName | String | Il nome del file di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converte il file di origine nel formato di origine nel flusso nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del file di origine. |
| loadOptions | LoadOptions | Il formato del file di origine. |
| dstStream | Stream | Il flusso di destinazione. |
| saveOptions | SaveOptions | Il formato del flusso di destinazione. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converte lo stream nel formato sorgente in stream nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | Il flusso di origine. |
| loadOptions | LoadOptions | Il formato del flusso di origine. |
| dstStream | Stream | Il flusso di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogFileName | String | Percorso del file in cui verranno archiviati i commenti. |
| format | PdfFormat | Il formato pdf. |
| action | ConvertErrorAction | Azione per oggetti che non possono essere convertiti |
| transparencyAction | ConvertTransparencyAction | Azione per oggetti mascherati con immagini |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogStream | Stream | Stream in cui verranno archiviati i commenti. |
| format | PdfFormat | Il formato pdf. |
| action | ConvertErrorAction | Azione per oggetti che non possono essere convertiti |
| transparencyAction | ConvertTransparencyAction | Azione per oggetti mascherati con immagini |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogFileName | String | Percorso del file in cui verranno archiviati i commenti. |
| format | PdfFormat | Il formato pdf. |
| action | ConvertErrorAction | Azione per oggetti che non possono essere convertiti |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Converti documento utilizzando le opzioni di conversione specificate

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | PdfFormatConversionOptions | set di opzioni per convertire il documento PDF |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | CallBackGetHocr | Azione per oggetti che non possono essere convertiti |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Converti il documento e salva gli errori nel flusso specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogStream | Stream | Stream in cui verranno archiviati i commenti. |
| format | PdfFormat | Formato PDF. |
| action | ConvertErrorAction | Azione per oggetti che non possono essere convertiti |

### Valore di ritorno

Il risultato dell'operazione

### Guarda anche

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Converti documento applicando la correzione.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixup | Fixup | Il tipo di correzione. |
| outputLog | Stream | Il registro del processo. |
| onlyValidation | Boolean | Solo convalida dei documenti. |
| parameters | Object[] | Proprietà per la correzione che non possono essere impostate. |

### Valore di ritorno

Il risultato dell'operazione.

### Guarda anche

* enum [Fixup](../../fixup)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Converti documento applicando la correzione.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixup | Fixup | Il tipo di correzione. |
| outputLog | String | Il registro del processo. |
| onlyValidation | Boolean | Solo convalida dei documenti. |
| parameters | Object[] | Proprietà per la correzione che non possono essere impostate. |

### Valore di ritorno

Il risultato dell'operazione.

### Guarda anche

* enum [Fixup](../../fixup)
* class [Document](../../document)
* spazio dei nomi [Aspose.Pdf](../../document)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
