---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Questa classe descrive regole che possono essere usate per risolvere l'errore Adobe Preflight <br/>            \"Il testo non può essere mappato su Unicode\"."
type: docs
weight: 20
url: /it/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Questa classe descrive regole che possono essere usate per risolvere l'errore Adobe Preflight <br/>            "Il testo non può essere mappato su Unicode".

Il tipo ToUnicodeProcessingRules espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| ToUnicodeProcessingRules() | Costruttore |
| ToUnicodeProcessingRules(remove_spaces) | Inizializza una nuova istanza della classe ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Inizializza una nuova istanza della classe ToUnicodeProcessingRules |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| remove_spaces_from_c_map_names | Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori<br/>            con la mappatura del testo Unicode. Questa opzione indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode.<br/>            Per impostazione predefinita false. |
| map_non_linked_symbols_on_space | Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. <br/>            Questa mancanza di informazioni genera un errore \"Il testo non può essere mappato su Unicode\".<br/>            Usa questa opzione per mappare i simboli non collegati sul \"spazio\" Unicode (codice 32). |

### Vedi anche

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

