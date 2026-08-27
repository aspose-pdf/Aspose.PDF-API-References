---
title: "Form"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die ein Acro‑Formularobjekt darstellt."
type: docs
weight: 80
url: /de/python-net/aspose.pdf.facades/form/
---

## Form class

Klasse, die ein Acro‑Formularobjekt darstellt.

Der Form‑Typ stellt die folgenden Member bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Form(src_stream, dest_stream) | Initialisiert eine neue Instanz der Form-Klasse |
| Form() | Konstruktor von Form ohne Parameter. |
| Form(src_file_name) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(src_stream) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(src_file_name, dest_file_name) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(src_file_name, dest_stream) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(src_stream, dest_file_name) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(document) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(document, dest_file_name) | Initialisiert eine neue Instanz der Form-Klasse |
| Form(document, dest_stream) | Initialisiert eine neue Instanz der Form-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
| import_result | Ergebnis der letzten Importoperation. Array von Objekten, das das Ergebnis des Imports für jedes Feld beschreibt. |
| src_file_name | Liest oder setzt den Quelldateinamen. |
| dest_file_name | Liest oder setzt den Zieldateinamen. |
| src_stream | Liest oder setzt den Quell-Stream. |
| dest_stream | Liest oder setzt den Ziel-Stream. |
| field_names | Liefert die Liste der Feldnamen im Formular. |
| form_submit_button_names | Liefert alle Namen der Formular‑Absende‑Buttons. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save() | Speichert den Wert der ausgefüllten Felder und schließt das geöffnete PDF‑Dokument. |
| save(dest_file) | Speichert das Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das Dokument in den angegebenen Stream. |
| fill_field(field_name, field_value) | Füllt das Feld mit einem gültigen Wert gemäß einem vollqualifizierten Feldnamen.<br/>            Vor dem Ausfüllen der Felder müssen alle Feldnamen und die zugehörigen gültigen Werte bekannt sein.<br/>            Sowohl die Feldnamen als auch die Werte sind case‑sensitive.<br/>            Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit partiellen <br/>            Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert;<br/>            Zum Beispiel, wenn ein Feld den vollständigen Namen \"Form.Subform.TextField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"TextField\". <br/>            Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. |
| fill_field(field_name, index) | Füllt das Radio‑Box‑Feld mit einem gültigen Indexwert gemäß einem vollqualifizierten Feldnamen.<br/>            Vor dem Ausfüllen der Felder muss nur der Feldname bekannt sein. Der Wert kann über seinen Index angegeben werden.<br/>            Hinweis: Wird nur auf Radio‑Box-, Kombinations‑Box- und Listen‑Box‑Felder angewendet.<br/>            Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit partiellen <br/>            Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert;<br/>            Zum Beispiel, wenn ein Feld den vollständigen Namen \"Form.Subform.ListBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"ListBoxField\". <br/>            Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. |
| fill_field(field_name, be_checked) | Füllt das Kontrollkästchen‑Feld mit einem booleschen Wert.<br/>            Hinweis: Wird nur auf Check‑Boxen angewendet.<br/>            Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit partiellen <br/>            Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert;<br/>            Zum Beispiel, wenn ein Feld den vollständigen Namen \"Form.Subform.CheckBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"CheckBoxField\". <br/>            Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. |
| fill_field(field_name, field_values) | Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument.<br/>            Relevant für signierte Dokumente.<br/>            Hinweis: Wird nur auf Textfelder angewendet.<br/>            Sowohl die Feldnamen als auch die Werte sind case‑sensitive. |
| fill_field(field_name, value, fit_font_size) | Füllt das Kontrollkästchen‑Feld mit einem booleschen Wert.<br/>            Hinweis: Wird nur auf Check‑Boxen angewendet.<br/>            Bitte beachten Sie, dass Aspose.Pdf.Facades nur vollständige Feldnamen unterstützt und nicht mit partiellen <br/>            Feldnamen im Gegensatz zu Aspose.Pdf.Kit funktioniert;<br/>            Zum Beispiel, wenn ein Feld den vollständigen Namen \"Form.Subform.CheckBoxField\" hat, sollten Sie den vollständigen Namen angeben und nicht \"CheckBoxField\". <br/>            Sie können die Eigenschaft FieldNames verwenden, um vorhandene Feldnamen zu erkunden und das gewünschte Feld über seinen Teilnamen zu suchen. |
| import_xml(input_xml_stream) | Importiert den Inhalt der Felder aus der XML‑Datei und fügt ihn in das neue PDF ein. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importiert den Inhalt der Felder aus der XML‑Datei und fügt ihn in das neue PDF ein. |
| fill_image_field(field_name, image_file_name) | Fügt ein Bild in das vorhandene Schaltflächenfeld als dessen Darstellung ein, gemäß <br/>            seinem vollqualifizierten Feldnamen. |
| fill_image_field(field_name, image_stream) | Überlädt die Funktion von FillImageField.<br/>            Die Eingabe ist ein Bildstrom. |
| close() | Schließt geöffnete Dateien ohne Änderungen. |
| get_field_facade(field_name) | Gibt ein FrodmFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. |
| fill_fields(field_names, field_values, output) | Füllt die Textfeld‑Felder mit Textwerten und speichert das Dokument.<br/>            Relevant für signierte Dokumente.<br/>            Hinweis: Wird nur auf Textfelder angewendet.<br/>            Sowohl die Feldnamen als auch die Werte sind case‑sensitive. |
| get_button_option_current_value(field_name) | Gibt den aktuellen Wert für Radio-Button-Optionsfelder zurück. |
| get_field(field_name) | Gibt ein FrodmFieldFacade-Objekt zurück, das alle Darstellungsattribute enthält. |
| get_full_field_name(field_name) | Ermittelt den vollständigen Feldnamen anhand seines Kurzfeldnamens. |
| get_field_limit(field_name) | Ermittelt die Beschränkung des Textfeldes. |
| flatten_all_fields() | Flacht alle Felder ab. |
| flatten_field(field_name) | Flacht ein angegebenes Feld mit dem vollqualifizierten Feldnamen ab.<br/>            Alle anderen Felder bleiben unveränderlich. Wenn der fieldName ungültig ist, <br/>            bleiben alle Felder unveränderlich. |
| fill_barcode_field(field_name, data) | Füllt ein Barcode-Feld gemäß seinem vollqualifizierten Feldnamen aus. |
| import_fdf(input_fdf_stream) | Importiert den Inhalt der Felder aus der fdf-Datei und legt ihn in das neue PDF. |
| export_fdf(output_fdf_stream) | Exportiert den Inhalt der Felder des PDFs in den fdf-Stream. |
| export_xml(output_xml_stream) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream.<br/>            Der Wert des Schaltflächenfeldes wird nicht exportiert. |
| extract_xfa_data(output_xml_stream) | Extrahiert XFA-Datenpaket |
| set_xfa_data(input_xml_stream) | Ersetzt XFA-Daten durch das angegebene Datenpaket. Das Datenpaket kann mit ExtractXfaData extrahiert werden. |
| import_xfdf(input_xfdf_stream) | Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und fügt ihn in das neue PDF ein. |
| export_xfdf(output_xfdf_stream) | Exportiert den Inhalt der Felder des PDFs in den XML-Stream.<br/>            Der Wert des Schaltflächenfeldes wird nicht exportiert. |
| rename_field(field_name, new_field_name) | Benennt ein Feld um. Sowohl AcroForm-Feld als auch XFA-Feld sind zulässig. |
| get_rich_text(field_name) | Gibt den Wert eines Rich-Text-Feldes zurück, einschließlich der Formatierungsinformationen jedes Zeichens. |
| get_submit_flags(field_name) | Gibt die Übermittlungsflags des Submit-Buttons zurück. |
| get_field_type(field_name) | Gibt den Typ des Feldes zurück. |
| is_required_field(field_name) | Bestimmt, ob das Feld erforderlich ist oder nicht. |
| get_field_flag(field_name) | Gibt die Flags des Feldes zurück. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

