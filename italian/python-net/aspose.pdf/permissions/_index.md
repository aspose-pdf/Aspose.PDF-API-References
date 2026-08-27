---
title: "Autorizzazioni"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Questa enumerazione rappresenta i permessi dell'utente per un PDF."
type: docs
weight: 6560
url: /it/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Questa enumerazione rappresenta i permessi dell'utente per un PDF.

## Members
| Nome membro | Descrizione |
| :- | :- |
| PRINT_DOCUMENT | (Gestori di sicurezza della revisione 2) Stampa il documento.<br/>            (Gestori di sicurezza della revisione 3 o successive) Stampa il documento <br/>            (possibilmente non al livello di qualità più alto, <br/>            a seconda che [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) sia anche impostato). |
| MODIFY_CONTENT | Modifica il contenuto del documento mediante operazioni diverse <br/>            da quelle controllate da  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), e 11. |
| EXTRACT_CONTENT | (Gestori di sicurezza della revisione 2) Copia o altrimenti estrae <br/>            testo e grafica dal documento, includendo l'estrazione <br/>            di testo e grafica (a supporto dell'accessibilità per gli utenti <br/>            con disabilità o per altri scopi).<br/>            (Gestori di sicurezza della revisione 3 o successive) Copia o altrimenti <br/>            estrae testo e grafica dal documento mediante operazioni <br/>            diverse da quelle controllate da [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Aggiungi o modifica annotazioni di testo, compila campi di modulo interattivi, <br/>            e, se [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) è anche impostato, crea o modifica campi di modulo interattivi <br/>            (inclusi i campi firma). |
| FILL_FORM | (Gestori di sicurezza della revisione 3 o successive) Compila i campi di modulo interattivi esistenti <br/>            (inclusi i campi firma), anche se <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) è disattivato. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Gestori di sicurezza della revisione 3 o successive) Estrai testo e <br/>            grafica (a supporto dell'accessibilità per gli utenti con disabilità <br/>            o per altri scopi). |
| ASSEMBLE_DOCUMENT | (Gestori di sicurezza della revisione 3 o successive) Assembla il documento <br/>            (inserisci, ruota o elimina pagine e crea segnalibri o miniature <br/>            immagini), anche se [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) è disattivato. |
| PRINTING_QUALITY | (Gestori di sicurezza della revisione 3 o successive) Stampa il documento in <br/>            una rappresentazione da cui può essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è disattivato (e il bit 3 è impostato), <br/>            la stampa è limitata a una rappresentazione di basso livello dell'aspetto, <br/>            possibilmente di qualità degradata. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

