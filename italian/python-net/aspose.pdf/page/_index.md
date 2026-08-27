---
title: "Page"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta una pagina di un documento PDF."
type: docs
weight: 1080
url: /it/python-net/aspose.pdf/page/
---

## Page class

Classe che rappresenta una pagina di un documento PDF.

Il tipo Page espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| is_add_paragraphs_after_last | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina |
| background_image | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene riempita durante la lettura del documento). |
| toc_info | Ottiene o imposta le informazioni dell'indice. |
| header | Ottiene o imposta l'intestazione della pagina. |
| livelli | Ottiene o imposta la raccolta dei livelli. |
| piè di pagina | Ottiene o imposta il piè di pagina della pagina. |
| paragraphs | Ottiene i paragrafi. |
| page_info | Ottiene o imposta le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento). |
| rect | Ottiene o imposta il rettangolo della pagina.<br/>            Per la lettura: viene restituita la crop box della pagina se specificata, altrimenti viene restituita la media box della pagina.<br/>            Per l'impostazione: la media box della pagina è sempre impostata.<br/>            Si prega di notare che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina tenendo conto della rotazione, utilizzare ActualRect. |
| color_type | Imposta il tipo di colore delle pagine in base alle informazioni ottenute dagli operatori SetColor,<br/>            immagini e moduli. |
| note_line_style | Ottiene o imposta lo stile della linea per le note (solo per il generatore, non compilato durante la lettura del documento). |
| tab_order | Ottiene o imposta l'ordine delle schede della pagina. <br/>            Valori possibili: Row, Column. Predefinito, Manuale |
| duration | Ottiene o imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione.<br/>            Restituisce -1 se la durata non è definita. |
| contents | Ottiene la raccolta di operatori nel flusso di contenuto della pagina.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| group | Ottiene o imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagina della pagina per l'uso nel modello di imaging trasparente. |
| annotations | Ottiene la raccolta di annotazioni della pagina.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Ottiene le risorse della pagina. L'oggetto Resources contiene raccolte di immagini, moduli e font.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| ruota | Ottiene o imposta la rotazione della pagina. |
| trim_box | Ottiene o imposta la trim box della pagina. |
| art_box | Ottiene o imposta la art box della pagina. |
| bleed_box | Ottiene o imposta la bleed box della pagina. |
| crop_box | Ottiene o imposta la crop box della pagina. |
| media_box | Ottiene o imposta la media box della pagina. |
| numero | Ottieni il numero della pagina. |
| rotation_matrix | Ottiene la matrice di trasformazione per la pagina. |
| background | Ottiene o imposta il colore di sfondo della pagina. |
| watermark | Ottiene o imposta la filigrana della pagina. |
| artifacts | Ottiene la collezione di artifact sulla pagina. |
| actions | Ottiene la collezione delle proprietà della pagina. |
| fields_in_tab_order | Ottiene l'elenco di oggetti Field in ordine Tab su questa pagina. |
| user_unit | Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1 ⁄ 72 di pollice.<br/>            Il valore predefinito è 1. Si prega di impostare zero o un valore negativo per cancellare questa voce nella pagina. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| send_to(device, output) | Invia la pagina al processo con il dispositivo pagina fornito. |
| send_to(device, output_file_name) | Invia la pagina al processo con il dispositivo pagina fornito. |
| accept(visitor) | Accetta l'oggetto visitor [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) che fornisce funzionalità per lavorare con le annotazioni. |
| accept(visitor) | Accetta l'oggetto visitor [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| accept(visitor) | Accetta l'oggetto visitor [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) che fornisce funzionalità per lavorare con gli oggetti di posizionamento delle immagini. |
| accept(visitor) | Accetta l'oggetto visitor [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) che fornisce funzionalità per lavorare con gli oggetti di testo. |
| add_image(image_stream, image_rect) | Aggiunge l'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| add_image(hocr, image_stream, image_rect) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Aggiunge un'immagine alla pagina e la posiziona in base alla posizione del rettangolo dell'immagine. |
| add_image(image_path, rectangle) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| is_blank(fill_threshold_factor) | Ottiene il flag che indica se la pagina è vuota o meno. |
| get_page_rect(consider_rotation) | Restituisce il rettangolo della pagina in base al suo CropBox (o MediaBox se CropBox è nullo). |
| calculate_content_b_box() | Calcola il valore bbox - rettangolo che contiene i contenuti senza margini visibili. |
| rotation_to_int(rotation) | Traduce il membro dell'enumerazione di rotazione in valore intero. |
| int_to_rotation(rotation) | Traduce il valore intero nel corrispondente membro dell'enumerazione di rotazione. |
| add_stamp(stamp) | Inserisce un timbro nella pagina. Il timbro può essere il numero di pagina, un'immagine o un semplice testo, ad esempio un logo. |
| flatten() | Rimuove tutti i campi presenti nella pagina e ne inserisce i valori al loro posto. |
| set_page_size(width, height) | Imposta la dimensione della pagina. |
| make_grayscale() | Converte la pagina in scala di grigi. |
| free_memory() | Cancella i dati memorizzati nella cache |
| get_notifications() | Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Attualmente sono supportate solo le notifiche sugli eventi di paragrafo negli scenari di aggiunta di testo.) |
| as_byte_array(resolution) | Converte la pagina corrente in bitmap e poi restituisce un array di byte. |
| as_xml() | Converte la pagina corrente in XML con codifica UTF-8. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

