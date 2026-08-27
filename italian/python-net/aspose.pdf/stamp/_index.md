---
title: "Stamp"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Una classe astratta per vari tipi di timbri che derivano come discendenti."
type: docs
weight: 1440
url: /it/python-net/aspose.pdf/stamp/
---

## Stamp class

Una classe astratta per vari tipi di timbri che derivano come discendenti.

Il tipo Stamp espone i seguenti membri:
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
## Metodi
| Nome | Descrizione |
| :- | :- |
| put(page) | Aggiunge un timbro alla pagina. |
| set_stamp_id(value) | Imposta l'ID del timbro. |
| get_stamp_id() | Restituisce l'ID del timbro. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

