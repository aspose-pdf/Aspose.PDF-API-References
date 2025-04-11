---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Permissions. Questo enum rappresenta i permessi degli utenti per un pdf
type: docs
weight: 8480
url: /it/net/aspose.pdf/permissions/
---
## Enumerazione dei permessi

Questo enum rappresenta i permessi dell'utente per un pdf.

```csharp
[Flags]
public enum Permissions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PrintDocument | `4` | (Gestori di sicurezza della revisione 2) Stampa il documento. (Gestori di sicurezza della revisione 3 o superiore) Stampa il documento (possibilmente non al livello di qualità più elevato, a seconda che PrintingQuality sia impostato). |
| ModifyContent | `8` | Modifica il contenuto del documento tramite operazioni diverse da quelle controllate da ModifyTextAnnotations, FillForm e 11. |
| ExtractContent | `10` | (Gestori di sicurezza della revisione 2) Copia o estrae in altro modo testo e grafica dal documento, inclusa l'estrazione di testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). (Gestori di sicurezza della revisione 3 o superiore) Copia o estrae in altro modo testo e grafica dal documento tramite operazioni diverse da quelle controllate da ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Aggiungi o modifica annotazioni di testo, compila i campi del modulo interattivo e, se ModifyContent è impostato, crea o modifica i campi del modulo interattivo (inclusi i campi di firma). |
| FillForm | `100` | (Gestori di sicurezza della revisione 3 o superiore) Compila i campi del modulo interattivo esistenti (inclusi i campi di firma), anche se ModifyTextAnnotations è chiaro. |
| ExtractContentWithDisabilities | `200` | (Gestori di sicurezza della revisione 3 o superiore) Estrai testo e grafica (a supporto dell'accessibilità per utenti con disabilità o per altri scopi). |
| AssembleDocument | `400` | (Gestori di sicurezza della revisione 3 o superiore) Assembla il documento (inserisci, ruota o elimina pagine e crea segnalibri o immagini in miniatura), anche se ModifyContent è chiaro. |
| PrintingQuality | `800` | (Gestori di sicurezza della revisione 3 o superiore) Stampa il documento in una rappresentazione dalla quale potrebbe essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è chiaro (e il bit 3 è impostato), la stampa è limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)