---
title: "TextSearchOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta le opzioni di ricerca del testo"
type: docs
weight: 460
url: /it/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Rappresenta le opzioni di ricerca del testo

Il tipo TextSearchOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Inizializza una nuova istanza della classe TextSearchOptions |
| TextSearchOptions(rectangle) | Inizializza una nuova istanza della classe TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Inizializza una nuova istanza della classe TextSearchOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_regular_expression_used | Ottiene o imposta l'indicazione che viene utilizzata un'espressione regolare. |
| limit_to_page_bounds | Ottiene o imposta l'indicazione che il testo viene cercato entro i limiti della pagina. |
| rectangle | Ottiene o imposta il rettangolo che delimita il testo cercato. |
| use_font_engine_encoding | Ottiene o imposta l'indicazione che il testo verrà cercato utilizzando la codifica del motore dei font.<br/>            true - indica che verrà utilizzata la codifica del motore dei font (prova questa opzione se la ricerca del testo fallisce a causa di una codifica imperfetta nel documento)<br/>            false - indica che verrà utilizzata la codifica del font del documento (valore predefinito) |
| ignore_shadow_text | Ottiene o imposta l'indicazione che i frammenti di testo che rappresentano l'ombra del testo normale saranno ignorati durante la ricerca.<br/>            true - indica che il testo in ombra non verrà trovato (prova questa opzione se la ricerca del testo restituisce frammenti duplicati in posizioni vicine)<br/>            false - indica che il testo in ombra verrà trovato insieme al testo normale (valore predefinito) |
| log_text_extraction_errors | Ottiene o imposta l'indicazione che gli errori di estrazione del testo (decodifica) saranno registrati nell'assorbitore di testo (frammenti).<br/>            true - indica che gli errori di estrazione del testo (decodifica) saranno registrati. Potrebbe ridurre le prestazioni.<br/>            false (default) - nessuna registrazione degli errori. |
| ignore_resource_font_errors | Ottiene o imposta l'indicazione che gli errori relativi all'assenza del font saranno ignorati dall'assorbitore di testo (fragment).<br/>            true - indica che gli errori di assenza del font saranno ignorati. I segmenti di testo che fanno riferimento a risorse errate saranno saltati durante l'elaborazione.<br/>            false (default) - l'errore di assenza del font terminerà l'elaborazione lanciando un'eccezione. |
| search_for_text_related_graphics | Ottiene o imposta il valore che consente la ricerca di elementi grafici correlati al testo (sottolineatura, sfondo ecc.) durante la ricerca del testo.<br/>            true - la ricerca di elementi grafici correlati al testo verrà eseguita (valore predefinito).<br/>            false - gli elementi grafici presenti nel documento sorgente saranno ignorati. Impostare questo in caso di problemi di prestazioni o se non è necessario gestire sottolineature, sfondi o ritagli. |
| stored_graphic_elements_max_count | Ottiene o imposta il valore che limita la ricerca di elementi grafici correlati al testo (sottolineatura, sfondo ecc.) su una pagina al numero specificato di elementi.<br/>            Il valore predefinito è 250. Impostare un valore inferiore in caso di problemi di prestazioni, provare un valore maggiore se alcuni elementi grafici non sono stati trovati. |
| search_in_annotations | Ottiene o imposta il valore che consente la ricerca di testo nelle Annotazioni.<br/>            true - il testo verrà cercato nelle Annotazioni.<br/>            false - il testo nelle Annotazioni non sarà analizzato da TextFragmentAbsorber. |

### Vedi anche

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

