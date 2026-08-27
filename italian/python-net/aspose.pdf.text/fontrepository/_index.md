---
title: "FontRepository"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Esegue la ricerca dei font. Cerca nei font installati nel sistema e nei font PDF standard.<br/>             Fornisce inoltre la funzionalità per aprire font personalizzati."
type: docs
weight: 130
url: /it/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Esegue la ricerca dei font. Cerca nei font installati nel sistema e nei font PDF standard.<br/>             Fornisce inoltre la funzionalità per aprire font personalizzati.

Il tipo FontRepository espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| FontRepository() | Inizializza una nuova istanza della classe FontRepository |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| substitutions | Ottiene la collezione delle strategie di sostituzione dei font. |
| sources | Ottiene la collezione delle sorgenti dei font. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| find_font(font_name) | Cerca e restituisce il font con il nome specificato. |
| find_font(font_name, ignore_case) | Cerca e restituisce il font con il nome specificato ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| find_font(font_family_name, stl) | Cerca e restituisce il font con il nome e lo stile specificati. |
| find_font(font_family_name, stl, ignore_case) | Cerca e restituisce il font con il nome e lo stile specificati <br/>             ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| open_font(font_stream, font_type) | Apre il font con lo stream del font specificato. |
| open_font(font_file_path) | Apre il font con il percorso del file del font specificato. |
| open_font(font_file_path, metrics_file_path) | Apre il font con il percorso del file del font specificato. |
| load_fonts() | Carica i font installati nel sistema e i font Pdf standard. Questo metodo è stato progettato per velocizzare il processo di caricamento dei font.<br/>            Per impostazione predefinita i font vengono caricati alla prima richiesta di qualsiasi font. L'uso di questo metodo carica i font di sistema e i font Pdf standard<br/>            immediatamente prima che venga aperto qualsiasi documento Pdf. |
| reload_fonts() | Ricarica tutti i font specificati dalla proprietà [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

