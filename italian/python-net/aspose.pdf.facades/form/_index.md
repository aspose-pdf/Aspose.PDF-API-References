---
title: "Form"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta l'oggetto Acro form."
type: docs
weight: 80
url: /it/python-net/aspose.pdf.facades/form/
---

## Form class

Classe che rappresenta l'oggetto Acro form.

Il tipo Form espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Form(src_stream, dest_stream) | Inizializza una nuova istanza della classe Form |
| Form() | Costruttore di Form senza parametri. |
| Form(src_file_name) | Inizializza una nuova istanza della classe Form |
| Form(src_stream) | Inizializza una nuova istanza della classe Form |
| Form(src_file_name, dest_file_name) | Inizializza una nuova istanza della classe Form |
| Form(src_file_name, dest_stream) | Inizializza una nuova istanza della classe Form |
| Form(src_stream, dest_file_name) | Inizializza una nuova istanza della classe Form |
| Form(document) | Inizializza una nuova istanza della classe Form |
| Form(document, dest_file_name) | Inizializza una nuova istanza della classe Form |
| Form(document, dest_stream) | Inizializza una nuova istanza della classe Form |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| document | Ottiene la facciata del documento su cui si sta lavorando. |
| import_result | Risultato dell'ultima operazione di importazione. Array di oggetti che descrive il risultato dell'importazione per ogni campo. |
| src_file_name | Ottiene o imposta il nome del file di origine. |
| dest_file_name | Ottiene o imposta il nome del file di destinazione. |
| src_stream | Ottiene o imposta lo stream di origine. |
| dest_stream | Ottiene o imposta lo stream di destinazione. |
| field_names | Ottiene l'elenco dei nomi dei campi nel modulo. |
| form_submit_button_names | Ottiene tutti i nomi dei pulsanti di invio del modulo. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| bind_pdf(src_file) | Associa il documento PDF per la modifica. |
| bind_pdf(src_stream) | Associa il documento PDF per la modifica. |
| bind_pdf(src_doc) | Associa il documento PDF per la modifica. |
| save() | Salva il valore dei campi compilati e chiude il documento Pdf aperto. |
| save(dest_file) | Salva il documento nel file specificato. |
| save(dest_stream) | Salva il documento nello stream specificato. |
| fill_field(field_name, field_value) | Compila il campo con un valore valido in base a un nome di campo completamente qualificato.<br/>            Prima di compilare i campi, è necessario conoscere tutti i nomi dei campi e i relativi valori validi.<br/>            Sia il nome del campo che i valori sono sensibili al maiuscolo/minuscolo.<br/>            Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi parziali <br/>            rispetto a Aspose.Pdf.Kit;<br/>            Ad esempio, se il campo ha il nome completo "Form.Subform.TextField" è necessario specificare il nome completo e non "TextField". <br/>            È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. |
| fill_field(field_name, index) | Compila il campo radio box con un valore indice valido in base a un nome di campo completamente qualificato.<br/>            Prima di compilare i campi, è necessario conoscere solo il nome del campo. Il valore può essere specificato tramite il suo indice.<br/>            Nota: Applicabile solo ai campi Radio Box, Combo Box e List Box.<br/>            Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi parziali <br/>            rispetto a Aspose.Pdf.Kit;<br/>            Ad esempio, se il campo ha il nome completo "Form.Subform.ListBoxField" è necessario specificare il nome completo e non "ListBoxField". <br/>            È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. |
| fill_field(field_name, be_checked) | Compila il campo check box con un valore booleano.<br/>            Nota: Applicabile solo ai campi Check Box.<br/>            Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi parziali <br/>            rispetto a Aspose.Pdf.Kit;<br/>            Ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". <br/>            È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. |
| fill_field(field_name, field_values) | Compila i campi di testo con valori testuali e salva il documento.<br/>            Rilevante per documenti firmati.<br/>            Nota: Applicabile solo ai campi Text Box.<br/>            Sia il nome dei campi che i valori sono sensibili al maiuscolo/minuscolo. |
| fill_field(field_name, value, fit_font_size) | Compila il campo check box con un valore booleano.<br/>            Nota: Applicabile solo ai campi Check Box.<br/>            Si noti che Aspose.Pdf.Facades supporta solo nomi di campo completi e non funziona con nomi parziali <br/>            rispetto a Aspose.Pdf.Kit;<br/>            Ad esempio, se il campo ha il nome completo "Form.Subform.CheckBoxField" è necessario specificare il nome completo e non "CheckBoxField". <br/>            È possibile utilizzare la proprietà FieldNames per esplorare i nomi dei campi esistenti e cercare il campo richiesto per nome parziale. |
| import_xml(input_xml_stream) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo PDF. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importa il contenuto dei campi dal file xml e li inserisce nel nuovo PDF. |
| fill_image_field(field_name, image_file_name) | Incolla un'immagine sul campo pulsante esistente come sua apparenza in base a <br/>            il suo nome di campo completamente qualificato. |
| fill_image_field(field_name, image_stream) | Sovraccarica la funzione di FillImageField.<br/>            L'input è un flusso di immagine. |
| close() | Chiude i file aperti senza alcuna modifica. |
| get_field_facade(field_name) | Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto. |
| fill_fields(field_names, field_values, output) | Compila i campi di testo con valori testuali e salva il documento.<br/>            Rilevante per documenti firmati.<br/>            Nota: Applicabile solo ai campi Text Box.<br/>            Sia il nome dei campi che i valori sono sensibili al maiuscolo/minuscolo. |
| get_button_option_current_value(field_name) | Restituisce il valore corrente per i campi di opzione dei pulsanti radio. |
| get_field(field_name) | Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto. |
| get_full_field_name(field_name) | Ottiene il nome completo del campo in base al suo nome breve. |
| get_field_limit(field_name) | Ottieni la limitazione del campo di testo. |
| flatten_all_fields() | Appiattisce tutti i campi. |
| flatten_field(field_name) | Appiattisce un campo specificato con il nome completo del campo.<br/>            Qualsiasi altro campo rimarrà invariato. Se il fieldName è non valido, <br/>            tutti i campi rimarranno invariati. |
| fill_barcode_field(field_name, data) | Compila un campo barcode in base al suo nome completo del campo. |
| import_fdf(input_fdf_stream) | Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo pdf. |
| export_fdf(output_fdf_stream) | Esporta il contenuto dei campi del pdf nello stream fdf. |
| export_xml(output_xml_stream) | Esporta il contenuto dei campi del pdf nello stream xml.<br/>            Il valore del campo pulsante non sarà esportato. |
| extract_xfa_data(output_xml_stream) | Estrae il pacchetto dati XFA |
| set_xfa_data(input_xml_stream) | Sostituisce i dati XFA con il pacchetto dati specificato. Il pacchetto dati può essere estratto usando ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Importa il contenuto dei campi dal file xfdf(xml) e lo inserisce nel nuovo PDF. |
| export_xfdf(output_xfdf_stream) | Esporta il contenuto dei campi del pdf nello stream xml.<br/>            Il valore del campo pulsante non sarà esportato. |
| rename_field(field_name, new_field_name) | Rinomina un campo. Va bene sia un campo AcroForm sia un campo XFA. |
| get_rich_text(field_name) | Ottiene il valore di un campo Rich Text, includendo le informazioni di formattazione di ogni carattere. |
| get_submit_flags(field_name) | Restituisce le flag di invio del pulsante di submit |
| get_field_type(field_name) | Restituisce il tipo di campo. |
| is_required_field(field_name) | Determina se il campo è obbligatorio o meno. |
| get_field_flag(field_name) | Restituisce le flag del campo. |

### Vedi anche

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

