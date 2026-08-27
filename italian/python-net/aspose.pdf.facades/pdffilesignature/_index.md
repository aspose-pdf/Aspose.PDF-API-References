---
title: "PdfFileSignature"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Rappresenta una classe per firmare un file pdf con un certificato."
type: docs
weight: 310
url: /it/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Rappresenta una classe per firmare un file pdf con un certificato.

Il tipo PdfFileSignature espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PdfFileSignature() | Il costruttore della classe PdfFileSignature. |
| PdfFileSignature(input_file) | Inizializza una nuova istanza della classe PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Inizializza una nuova istanza della classe PdfFileSignature |
| PdfFileSignature(document) | Inizializza una nuova istanza della classe PdfFileSignature |
| PdfFileSignature(document, output_file) | Inizializza una nuova istanza della classe PdfFileSignature |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| signature_appearance | Imposta o ottiene l'aspetto grafico della firma. Il valore della proprietà rappresenta il nome del file immagine. |
| is_ltv_enabled | Ottiene il flag LTV abilitato. |
| is_certified | Ottiene il flag che determina se un documento è certificato o meno. |
| signature_appearance_stream | Imposta o ottiene l'aspetto grafico della firma. Il valore della proprietà rappresenta lo stream dell'immagine. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(input_file) | Associa un file Pdf per la modifica. |
| bind_pdf(input_stream) | Associa un flusso Pdf per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save(output_file) | Salva il PDF risultante su file. |
| save(output_stream) | Salva il PDF risultante su stream. |
| save() | Salva il PDF risultante su file. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Crea una firma sul documento pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Firma il documento con la firma di tipo fornita. |
| sign(page, visible, annot_rect, sig) | Firma il documento con la firma di tipo fornita. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Firma il documento con la firma di tipo fornita. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Firma il documento con la firma di tipo fornita. |
| sign(sig_name, sig) | Firma il documento con la firma di tipo fornita. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Certifica il documento con la firma MDP.<br/>            Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig. |
| certify(sig_name, doc_mdp_signature) | Certifica il documento con la firma MDP.<br/>            Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig. |
| remove_signature(sign_name) | Rimuovi la firma in base al nome della firma. |
| remove_signature(sign_name, remove_field) | Rimuove la firma in base al nome della firma. |
| close() | Chiude la facciata. |
| get_access_permissions() | Restituisce il valore dei permessi di accesso del documento certificato dal tipo di firma MDP. |
| get_sign_names(only_active) | Ottiene i nomi di tutte le firme non vuote. |
| get_blank_sign_names() | Ottiene i nomi di tutti i campi firma vuoti. |
| is_contain_signature() | Verifica se il pdf ha una firma digitale o meno. |
| contains_signature() | Verifica se il pdf ha una firma digitale o meno. |
| contains_usage_rights() | Verifica se il PDF ha diritti d'uso o meno. |
| is_covers_whole_document(sign_name) | Verifica se la firma copre l'intero documento. |
| covers_whole_document(sign_name) | Verifica se la firma copre l'intero documento. |
| get_revision(sign_name) | Restituisce la revisione di una firma. |
| get_total_revision() | Restituisce la revisione totale. |
| remove_usage_rights() | Rimuove la voce dei diritti d'uso. |
| verify_signed(sign_name) | Verifica la validità di una firma. |
| get_signer_name(sign_name) | Restituisce il nome della persona o dell'organizzazione che firma il documento PDF. |
| get_date_time(sign_name) | Restituisce la data e l'ora della firma. |
| get_reason(sign_name) | Restituisce il motivo di una firma. |
| get_location(sign_name) | Restituisce la posizione di una firma. |
| get_contact_info(sign_name) | Restituisce le informazioni di contatto di una firma. |
| verify_signature(sign_name) | Verifica la validità di una firma. |
| extract_image(sign_name) | Estrae l'immagine della firma. |
| extract_certificate(sign_name) | Estrae il singolo certificato X.509 della firma come flusso. |
| set_certificate(pfx, pass) | Imposta il file del certificato e la password per la routine di firma. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

