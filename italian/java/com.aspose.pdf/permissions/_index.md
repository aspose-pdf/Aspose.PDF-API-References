---
title: "Autorizzazioni"
linktitle: "Autorizzazioni"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Flag binario Questa enumerazione rappresenta i permessi dell'utente per un pdf."
type: docs
weight: 3830
url: /it/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Flag binario Questa enumerazione rappresenta i permessi dell'utente per un pdf.

## Campi

| Campo | Descrizione |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Gestori di sicurezza della revisione 3 o successive) Assembla il documento (inserisci, ruota o elimina pagine e crea segnalibri o miniature), anche se {@code ModifyContent} è impostato su chiaro. |
| [ExtractContent](#ExtractContent) | (Gestori di sicurezza della revisione 2) Copia o estrae in altro modo testo e grafica dal documento, inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). (Gestori di sicurezza della revisione 3 o successive) Copia o estrae in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate da {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Gestori di sicurezza della revisione 3 o successive) Estrai testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). |
| [FillForm](#FillForm) | (Gestori di sicurezza della revisione 3 o successive) Compila i campi interattivi del modulo esistenti (inclusi i campi firma), anche se {@code ModifyTextAnnotations} è impostato su chiaro. |
| [ModifyContent](#ModifyContent) | Modifica il contenuto del documento mediante operazioni diverse da quelle controllate da {@code ModifyTextAnnotations}, {@code FillForm} e 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Aggiungi o modifica annotazioni di testo, compila i campi interattivi del modulo e, se {@code ModifyContent} è anche impostato, crea o modifica i campi interattivi del modulo (inclusi i campi firma). |
| [PrintDocument](#PrintDocument) | (Gestori di sicurezza della revisione 2) Stampa il documento. (Gestori di sicurezza della revisione 3 o successive) Stampa il documento (potenzialmente non al livello di qualità più alto, a seconda se {@code PrintingQuality} è anche impostato). |
| [PrintingQuality](#PrintingQuality) | (Gestori di sicurezza della revisione 3 o successive) Stampa il documento in una rappresentazione da cui può essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è cancellato (e il bit 3 è impostato), la stampa è limitata a una rappresentazione a basso livello dell'aspetto, possibilmente di qualità degradata. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Gestori di sicurezza della revisione 3 o successive) Assembla il documento (inserisci, ruota o elimina pagine e crea segnalibri o miniature), anche se {@code ModifyContent} è impostato su chiaro.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Gestori di sicurezza della revisione 2) Copia o estrae in altro modo testo e grafica dal documento, inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). (Gestori di sicurezza della revisione 3 o successive) Copia o estrae in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate da {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Gestori di sicurezza della revisione 3 o successive) Estrai testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Gestori di sicurezza della revisione 3 o successive) Compila i campi interattivi del modulo esistenti (inclusi i campi firma), anche se {@code ModifyTextAnnotations} è impostato su chiaro.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modifica il contenuto del documento mediante operazioni diverse da quelle controllate da {@code ModifyTextAnnotations}, {@code FillForm} e 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Aggiungi o modifica annotazioni di testo, compila i campi interattivi del modulo e, se {@code ModifyContent} è anche impostato, crea o modifica i campi interattivi del modulo (inclusi i campi firma).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Gestori di sicurezza della revisione 2) Stampa il documento. (Gestori di sicurezza della revisione 3 o successive) Stampa il documento (potenzialmente non al livello di qualità più alto, a seconda se {@code PrintingQuality} è anche impostato).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Gestori di sicurezza della revisione 3 o successive) Stampa il documento in una rappresentazione da cui può essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è cancellato (e il bit 3 è impostato), la stampa è limitata a una rappresentazione a basso livello dell'aspetto, possibilmente di qualità degradata.
