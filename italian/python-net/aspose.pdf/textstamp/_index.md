---
title: "TextStamp"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta timbro testuale."
type: docs
weight: 1550
url: /it/python-net/aspose.pdf/textstamp/
---

## TextStamp class

Rappresenta timbro testuale.

Il tipo TextStamp espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| TextStamp(value) | Inizializza una nuova istanza della classe TextStamp |
| TextStamp(value, text_state) | Inizializza una nuova istanza della classe TextStamp |
| TextStamp(formatted_text) | Inizializza una nuova istanza della classe TextStamp |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| background | Imposta o ottiene un valore booleano che indica se il contenuto è stampato come sfondo.<br/>            Se il valore è true, il contenuto del timbro è posizionato in basso.<br/>            Per impostazione predefinita, il valore è false, il contenuto del timbro è posizionato in alto. |
| opacità | Ottiene o imposta un valore per indicare l'opacità del timbro. Il valore è compreso tra 0.0 e 1.0.<br/>            Per impostazione predefinita il valore è 1.0. |
| outline_opacity | Ottiene o imposta un valore per indicare l'opacità del contorno del timbro. Il valore è compreso tra 0.0 e 1.0.<br/>            Per impostazione predefinita il valore è 1.0. |
| outline_width | Ottiene o imposta un valore per la larghezza del contorno del timbro.<br/>            Per impostazione predefinita il valore è 1.0. |
| rotate | Imposta o ottiene la rotazione del contenuto del timbro secondo i valori di [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/>            Nota. Questa proprietà è per angoli impostati che sono multipli di 90 gradi (0, 90, 180, 270 gradi).<br/>            Per impostare un angolo arbitrario usa la proprietà RotateAngle. <br/>            Se l'angolo impostato da ArbitraryAngle non è un multiplo di 90, la proprietà Rotate restituisce Rotation.None. |
| x_indent | Coordinata orizzontale del timbro, a partire da sinistra. |
| y_indent | Coordinata verticale del timbro, a partire dal basso. |
| horizontal_alignment | Ottiene o imposta l'allineamento orizzontale del timbro nella pagina. |
| vertical_alignment | Ottiene o imposta l'allineamento verticale del timbro nella pagina. |
| left_margin | Ottiene o imposta il margine sinistro del timbro. |
| right_margin | Ottiene o imposta il margine destro del timbro. |
| bottom_margin | Ottiene o imposta il margine inferiore del timbro. |
| top_margin | Ottiene o imposta il margine superiore del timbro. |
| zoom_x | Fattore di zoom orizzontale del timbro. Consente di scalare il timbro orizzontalmente. |
| width | Larghezza desiderata del timbro nella pagina. |
| height | Altezza desiderata del timbro nella pagina. |
| zoom_y | Fattore di zoom verticale del timbro. Consente di scalare il timbro verticalmente. |
| zoom | Fattore di zoom del timbro. Consente di scalare il timbro.<br/>            Si noti che la coppia di proprietà ZoomX e ZoomY consente di impostare il fattore di zoom per ogni asse separatamente. <br/>            L'impostazione di questa proprietà modifica entrambe le proprietà ZoomX e ZoomY. <br/>            Se ZoomX e ZoomY sono diversi, la proprietà Zoom restituisce il valore di ZoomX. |
| rotate_angle | Ottiene o imposta l'angolo di rotazione del timbro in gradi.<br/>            Questa proprietà consente di impostare un angolo di rotazione arbitrario. |
| draw | Questa proprietà determina come il timbro viene disegnato sulla pagina. Se Draw = true il timbro è disegnato come operatori grafici e se draw = false il timbro è disegnato come testo. |
| treat_y_indent_as_base_line | Definisce l'origine delle coordinate per posizionare il testo.<br/>            Se TreatYIndentAsBaseLine = true (predefinito quando Draw = true) il valore YIndent sarà trattato come linea di base del testo.<br/>            Se TreatYIndentAsBaseLine = false (predefinito quando Draw = false) il valore YIndent sarà trattato come fondo (linea di discesa) del testo. |
| word_wrap | Definisce l'andata a capo delle parole. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo verrà suddiviso in più righe per adattarsi alla larghezza specificata. Valore predefinito: false. |
| justify | Definisce la giustificazione del testo. Se questa proprietà è impostata su true, entrambi i bordi sinistro e destro del testo sono allineati. Valore predefinito: false. |
| scale | Definisce la scalatura del testo. Se questa proprietà è impostata su true e viene specificato un valore Width, il testo sarà scalato per adattarsi alla larghezza specificata. |
| value | Ottiene o imposta il valore stringa utilizzato come timbro sulla pagina. |
| text_state | Ottiene le proprietà di testo del timbro. Vedi [text_state](/pdf/python-net/aspose.pdf/textstamp/) per i dettagli. |
| text_alignment | Allineamento del testo all'interno del timbro. |
| max_row_width | Altezza massima della riga per l'opzione WordWrap. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| put(page) | Aggiunge un timbro testuale nella pagina. |
| set_stamp_id(value) | Imposta l'ID del timbro. |
| get_stamp_id() | Restituisce l'ID del timbro. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

