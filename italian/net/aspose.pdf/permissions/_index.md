---
title: Permissions
second_title: Aspose.PDF per .NET API Reference
description: Questa enum rappresenta i permessi dellutente per un pdf.
type: docs
weight: 6110
url: /it/net/aspose.pdf/permissions/
---
## Permissions enumeration

Questa enum rappresenta i permessi dell'utente per un pdf.

```csharp
[Flags]
public enum Permissions
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PrintDocument | `4` | (Gestori di sicurezza di revisione 2) Stampa il documento. (Gestori di sicurezza di revisione 3 o superiore) Stampa il documento (possibilmente non al massimo livello di qualità, a seconda chePrintingQualityè impostato anche). |
| ModifyContent | `8` | Modifica il contenuto del documento con operazioni diverse da quelle controllate daModifyTextAnnotations , FillForm e 11. |
| ExtractContent | `10` | (gestori di sicurezza della revisione 2) Copiare o estrarre in altro modo testo e grafica dal documento, inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità agli utenti con disabilità o per altri scopi). (gestori di sicurezza della revisione 3 o maggiore) Copiare o altrimenti estrarre testo e grafica dal documento con operazioni diverse da quelle controllate daExtractContentWithDisabilities . |
| ModifyTextAnnotations | `20` | Aggiungi o modifica annotazioni di testo, compila i campi modulo interattivi, e, seModifyContent è anche impostato, crea o modifica i campi del modulo interattivo (inclusi i campi della firma). |
| FillForm | `100` | (gestori di sicurezza della revisione 3 o successiva) Compila i campi del modulo interattivo esistenti (inclusi i campi della firma), anche se ModifyTextAnnotations è chiaro. |
| ExtractContentWithDisabilities | `200` | (gestori di sicurezza della revisione 3 o superiore) Estrae testo e grafica (a supporto dell'accessibilità agli utenti con disabilità o per altri scopi). |
| AssembleDocument | `400` | (gestori di sicurezza della revisione 3 o successiva) Assembla il documento (inserisci, ruota o elimina le pagine e crea segnalibri o miniature ), anche seModifyContent è chiaro. |
| PrintingQuality | `800` | (Gestori di sicurezza di revisione 3 o superiore) Stampa il documento su una rappresentazione da cui potrebbe essere generata una copia digitale fedele del contenuto PDF . Quando questo bit è azzerato (e il bit 3 è impostato), la stampa è limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->