---
title: "PdfFileInfo"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per accedere alle meta‑informazioni di un documento PDF."
type: docs
weight: 270
url: /it/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Rappresenta una classe per accedere alle meta‑informazioni di un documento PDF.

Il tipo PdfFileInfo espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileInfo() | Inizializza una nuova istanza della classe Aspose.Pdf.Facades.PdfFileInfo con valori predefiniti. |
| PdfFileInfo(input_stream) | Inizializza una nuova istanza della classe PdfFileInfo |
| PdfFileInfo(input_stream, password) | Inizializza una nuova istanza della classe PdfFileInfo |
| PdfFileInfo(input_file) | Inizializza una nuova istanza della classe PdfFileInfo |
| PdfFileInfo(input_file, password) | Inizializza una nuova istanza della classe PdfFileInfo |
| PdfFileInfo(document) | Inizializza una nuova istanza della classe PdfFileInfo |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| author | Ottiene o imposta le informazioni dell'Author del documento PDF. |
| is_encrypted | Verifica se il documento PDF è crittografato. |
| is_pdf_file | Verifica se l'input di origine è un file PDF valido. |
| use_strict_validation | Utilizza regole di validazione rigorose tramite la proprietà [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Ottiene o imposta le informazioni di CreationDate del documento PDF. |
| creator | Ottiene o imposta le informazioni del Creator del documento PDF. |
| has_collection | Restituisce true se il file di input corrente è un file 'Portfolio' che contiene una raccolta di file PDF. |
| input_file | Ottiene o imposta il file di input. |
| input_stream | Ottiene o imposta lo stream di input. |
| keywords | Ottiene o imposta le informazioni delle parole chiave del documento PDF. |
| mod_date | Ottiene o imposta le informazioni della data ModDate del documento PDF. |
| number_of_pages | Ottiene il numero di pagine del documento. |
| producer | Ottiene le informazioni del produttore del documento PDF. |
| subject | Ottiene o imposta le informazioni dell'oggetto del documento PDF. |
| title | Ottiene o imposta le informazioni del titolo del documento PDF. |
| password_type | Restituisce il tipo di password che è stato passato per creare l'istanza PdfFileInfo. Vedi i valori possibili in [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Nota che il documento PDF può essere aperto sia con la password utente (o di apertura) sia con la password proprietario (o di permessi, modifica). |
| has_open_password | Restituisce true se è necessaria una password per aprire un documento PDF protetto da password. |
| has_edit_password | Restituisce true se è necessaria una password per modificare i permessi o la proprietà di sicurezza del documento.<br/>            Nota che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Nel caso in cui PasswordType sia Inaccessible (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_doc) | Inizializza la facciata. |
| bind_pdf(src_file) | Inizializza la facciata. |
| bind_pdf(src_stream) | Inizializza la facciata. |
| save(dest_stream) | Salva il documento PDF aggiornato nello stream specificato. |
| save(dest_file) | Salva il documento PDF aggiornato nel file specificato. |
| save_new_info(output_stream) | Salva il documento PDF aggiornato nello stream specificato. |
| save_new_info(output_file) | Salva il documento PDF aggiornato nel file specificato. |
| close() | Deinizializza l'istanza. |
| clear_info() | Cancella tutte le informazioni meta del documento PDF. |
| get_document_privilege() | Ottiene le impostazioni dei privilegi del documento PDF. |
| get_meta_info(name) | Ottiene le informazioni personalizzate del documento PDF con il nome della proprietà. Se non esiste alcuna proprietà corrispondente al nome, restituisce una stringa vuota. |
| get_page_height(page_num) | Ottiene l'altezza della pagina specificata. |
| get_page_rotation(page_num) | Ottiene la rotazione della pagina specificata. |
| get_page_width(page_num) | Ottiene la larghezza della pagina specificata. |
| get_page_x_offset(page_num) | Ottiene lo spostamento orizzontale dell'area di visualizzazione della pagina specificata. |
| get_page_y_offset(page_num) | Ottiene lo spostamento verticale dell'area di visualizzazione della pagina specificata. |
| get_pdf_version() | Ottiene le informazioni sulla versione del documento PDF. |
| set_meta_info(name, value) | Imposta le informazioni personalizzate del documento PDF. |
| save_new_info_with_xmp(output_file_name) | Modifica le proprietà specificate esplicitamente impostando le informazioni del file, le altre proprietà rimangono. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

