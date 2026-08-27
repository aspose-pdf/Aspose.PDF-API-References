---
title: "AppearanceDictionary"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina."
type: docs
weight: 60
url: /it/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Dizionario di aspetto dell'annotazione che specifica come l'annotazione deve essere presentata visivamente sulla pagina.

Il tipo AppearanceDictionary espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_fixed_size | Ottiene un valore che indica se il dizionario ha una dimensione fissa. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | Valori D).state,<br/>            dove N - aspetto normale, R - aspetto rollover, D - aspetto premuto e state - il nome dello stato<br/>            (ad es. On, Off per le caselle di controllo). |
| valori | Ottiene l'elenco dei valori del dizionario. <br/>            La collezione risultato contiene l'elenco degli oggetti XForm. |
| is_synchronized | Ottiene un valore che indica se l'accesso al dizionario è sincronizzato (thread‑safe). |
| sync_root | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso al dizionario. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| add(key, value) | Aggiunge un elemento con la chiave e il valore forniti. |
| add(key, value) | Aggiungi il modulo X per la chiave specificata. |
| copy_to(array, index) | Copia gli elementi del dizionario in un Array, a partire da un indice specifico dell'Array. |
| contains_key(key) | Determina se questo dizionario contiene la chiave specificata. |
| remove(key) | Rimuove la chiave dal dizionario. |
| try_get_value(key, value) | Prova a trovare la chiave nel dizionario e recupera il valore se trovata. |

### Vedi anche

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

