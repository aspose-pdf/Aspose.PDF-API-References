---
title: "XImage"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta l'oggetto immagine X-Object."
type: docs
weight: 1680
url: /it/python-net/aspose.pdf/ximage/
---

## XImage class

Classe che rappresenta l'oggetto immagine X-Object.

Il tipo XImage espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| contains_transparency | Se l'immagine contiene trasparenza restituisce true; altrimenti, false. |
| grayscaled | Ottiene la versione in scala di grigi dell'immagine. |
| filter_type | Ottiene il tipo di filtro dell'immagine. |
| width | Ottiene la larghezza dell'immagine. |
| height | Ottiene l'altezza dell'immagine. |
| name | Ottiene o imposta il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare errato. Si prega di utilizzare il metodo XImage.Rename in questo caso. |
| metadata | Metadati dell'immagine. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| save(stream) | Salva i dati dell'immagine nello stream come immagine JPEG. |
| save(stream, format) | Salva l'immagine nello stream con il formato richiesto. |
| save(stream, resolution) | Salva i dati dell'immagine nello stream come immagine JPEG con la risoluzione specificata. |
| save(stream, format, resolution) | Salva l'immagine nello stream con il formato richiesto e con la risoluzione specificata. |
| rename(name) | Rinomina l'immagine e sostituisce tutti i riferimenti all'immagine con il nuovo nome |
| get_color_type() | Restituisce il tipo di colore dell'immagine. |
| detect_color_type(bmp) | Restituisce il tipo di colore dell'immagine. |
| is_the_same_object(image) | Restituisce true se entrambe le immagini fanno riferimento allo stesso oggetto. |
| get_name_in_collection() | Restituisce il nome dell'immagine nella collezione ints. |
| to_stream() | Restituisce lo stream originale dell'immagine. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

