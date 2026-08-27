---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som beskriver submit-form-åtgärden."
type: docs
weight: 4690
url: /sv/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Klass som beskriver submit-form-åtgärden.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Om angivet ska alla inskickade fältvärden som representerar datum konverteras till standardformatet. |
| [EMBED_FORM](#EMBED_FORM) | Om angivet ska F‑posten i den inskickade FDF vara en filspecificering som innehåller ett inbäddat filström som representerar PDF‑filen som FDF‑filen skickas från. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Om angivet ska den inskickade FDF utesluta F‑posten. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Om angivet ska den endast inkludera de markup‑annoteringar vars T‑post matchar namnet på den aktuella användaren. |
| [EXCLUDE](#EXCLUDE) | Om rensad anger Fields‑arrayen vilka fält som ska inkluderas i inskickandet. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Om angivet ska fältnamn och värden skickas in i HTML‑formulärformat. |
| [GET_METHOD](#GET_METHOD) | Om den är inställd ska fältnamn och värden skickas med en HTTP GET request. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Om den är inställd ska den inskickade FDF-filen innehålla alla markup annotations i det underliggande PDF-dokumentet. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Om den är inställd ska den inskickade FDF-filen innehålla innehållet i alla inkrementella uppdateringar. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Om den är inställd ska alla fält som anges av Fields‑arrayen och Include/Exclude‑flaggan skickas. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Om den är inställd ska koordinaterna för musklicken som orsakade submit‑form‑åtgärden överföras som en del av formulärdata. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Om den är inställd ska dokumentet skickas som PDF med MIME‑innehållstypen application/pdf. |
| [XFDF](#XFDF) | Om den är inställd ska fältnamn och värden skickas som XFDF. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Initierar SubmitFormAction‑objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFlags](#getFlags--) | Hämtar flaggor för submit‑åtgärden. |
| [getUrl](#getUrl--) | Destinations‑URL. |
| [setFlags](#setFlags-int-) | Ställer in flaggor för submit‑åtgärden. |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | Destinations‑URL. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Om angivet ska alla inskickade fältvärden som representerar datum konverteras till standardformatet.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Om angivet ska F‑posten i den inskickade FDF vara en filspecificering som innehåller ett inbäddat filström som representerar PDF‑filen som FDF‑filen skickas från.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Om angivet ska den inskickade FDF utesluta F‑posten.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Om angivet ska den endast inkludera de markup‑annoteringar vars T‑post matchar namnet på den aktuella användaren.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Om rensad anger Fields‑arrayen vilka fält som ska inkluderas i inskickandet.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Om angivet ska fältnamn och värden skickas in i HTML‑formulärformat.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Om den är inställd ska fältnamn och värden skickas med en HTTP GET request.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Om den är inställd ska den inskickade FDF-filen innehålla alla markup annotations i det underliggande PDF-dokumentet.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Om den är inställd ska den inskickade FDF-filen innehålla innehållet i alla inkrementella uppdateringar.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Om den är inställd ska alla fält som anges av Fields‑arrayen och Include/Exclude‑flaggan skickas.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Om den är inställd ska koordinaterna för musklicken som orsakade submit‑form‑åtgärden överföras som en del av formulärdata.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Om den är inställd ska dokumentet skickas som PDF med MIME‑innehållstypen application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Om den är inställd ska fältnamn och värden skickas som XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Initierar SubmitFormAction‑objekt.

### getFlags {#getFlags--}
```
public int getFlags()
```

Hämtar flaggor för submit‑åtgärden.

**Returns:**
int‑värde

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

Destinations‑URL.

**Returns:**
FileSpecification-värde

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Ställer in flaggor för submit‑åtgärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
Destinations‑URL.
