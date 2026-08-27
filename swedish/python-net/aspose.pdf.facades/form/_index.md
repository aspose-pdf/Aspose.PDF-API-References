---
title: "Form"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Klass som representerar Acro‑formulärobjekt."
type: docs
weight: 80
url: /sv/python-net/aspose.pdf.facades/form/
---

## Form class

Klass som representerar Acro‑formulärobjekt.

Form-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Form(src_stream, dest_stream) | Initierar en ny instans av Form-klassen |
| Form() | Konstruktor för Form utan parametrar. |
| Form(src_file_name) | Initierar en ny instans av Form-klassen |
| Form(src_stream) | Initierar en ny instans av Form-klassen |
| Form(src_file_name, dest_file_name) | Initierar en ny instans av Form-klassen |
| Form(src_file_name, dest_stream) | Initierar en ny instans av Form-klassen |
| Form(src_stream, dest_file_name) | Initierar en ny instans av Form-klassen |
| Form(document) | Initierar en ny instans av Form-klassen |
| Form(document, dest_file_name) | Initierar en ny instans av Form-klassen |
| Form(document, dest_stream) | Initierar en ny instans av Form-klassen |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
| import_result | Resultat av den senaste importoperationen. Array av objekt som beskriver resultatet av importen för varje fält. |
| src_file_name | Hämtar eller anger källfilens namn. |
| dest_file_name | Hämtar eller anger destinationsfilens namn. |
| src_stream | Hämtar eller anger källström. |
| dest_stream | Hämtar eller anger målström. |
| field_names | Hämtar en lista med fältnamn på formuläret. |
| form_submit_button_names | Hämtar alla namn på formulärets submit‑knappar. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save() | Sparar värdet på de ifyllda fälten och stänger det öppnade PDF‑dokumentet. |
| save(dest_file) | Sparar dokumentet till angiven fil. |
| save(dest_stream) | Sparar dokumentet till angiven ström. |
| fill_field(field_name, field_value) | Fyller i fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn.<br/>            Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända.<br/>            Både fältnamnen och värdena är skiftlägeskänsliga.<br/>            Observera att **Aspose.Pdf.Facades** endast stöder fullständiga fältnamn och fungerar inte med partiella <br/>            fältnamn i motsats till **Aspose.Pdf.Kit**;<br/>            Till exempel, om fältet har det fullständiga namnet \"Form.Subform.TextField\" bör du ange hela namnet och inte \"TextField\". <br/>            Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet med dess partiella namn. |
| fill_field(field_name, index) | Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn.<br/>            Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan specificeras med dess index.<br/>            Obs: Gäller endast för Radio Box-, Combo Box- och List Box-fält.<br/>            Observera att **Aspose.Pdf.Facades** endast stöder fullständiga fältnamn och fungerar inte med partiella <br/>            fältnamn i motsats till **Aspose.Pdf.Kit**;<br/>            Till exempel, om fältet har det fullständiga namnet \"Form.Subform.ListBoxField\" bör du ange hela namnet och inte \"ListBoxField\". <br/>            Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet med dess partiella namn. |
| fill_field(field_name, be_checked) | Fyller i kryssrutan med ett booleskt värde.<br/>            Obs: Gäller endast för Check Box.<br/>            Observera att **Aspose.Pdf.Facades** endast stöder fullständiga fältnamn och fungerar inte med partiella <br/>            fältnamn i motsats till **Aspose.Pdf.Kit**;<br/>            Till exempel, om fältet har det fullständiga namnet \"Form.Subform.CheckBoxField\" bör du ange hela namnet och inte \"CheckBoxField\". <br/>            Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet med dess partiella namn. |
| fill_field(field_name, field_values) | Fyller i textrutefälten med textvärden och sparar dokumentet.<br/>            Relevant för signerade dokument.<br/>            Obs: Gäller endast för Text Box.<br/>            Både fältnamnen och värdena är skiftlägeskänsliga. |
| fill_field(field_name, value, fit_font_size) | Fyller i kryssrutan med ett booleskt värde.<br/>            Obs: Gäller endast för Check Box.<br/>            Observera att **Aspose.Pdf.Facades** endast stöder fullständiga fältnamn och fungerar inte med partiella <br/>            fältnamn i motsats till **Aspose.Pdf.Kit**;<br/>            Till exempel, om fältet har det fullständiga namnet \"Form.Subform.CheckBoxField\" bör du ange hela namnet och inte \"CheckBoxField\". <br/>            Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter det önskade fältet med dess partiella namn. |
| import_xml(input_xml_stream) | Importerar innehållet i fälten från XML‑filen och placerar dem i den nya PDF‑filen. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importerar innehållet i fälten från XML‑filen och placerar dem i den nya PDF‑filen. |
| fill_image_field(field_name, image_file_name) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt <br/>            dess fullständigt kvalificerade fältnamn. |
| fill_image_field(field_name, image_stream) | Överlagrar funktionen FillImageField.<br/>            Indatan är en bildström. |
| close() | Stänger öppnade filer utan några ändringar. |
| get_field_facade(field_name) | Returnerar FrofmFieldFacade-objekt som innehåller alla utseendeattribut. |
| fill_fields(field_names, field_values, output) | Fyller i textrutefälten med textvärden och sparar dokumentet.<br/>            Relevant för signerade dokument.<br/>            Obs: Gäller endast för Text Box.<br/>            Både fältnamnen och värdena är skiftlägeskänsliga. |
| get_button_option_current_value(field_name) | Returnerar det aktuella värdet för radioknappsalternativfält. |
| get_field(field_name) | Returnerar FrofmFieldFacade-objekt som innehåller alla utseendeattribut. |
| get_full_field_name(field_name) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| get_field_limit(field_name) | Hämta begränsningen för textfältet. |
| flatten_all_fields() | Plattar till alla fält. |
| flatten_field(field_name) | Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet.<br/>            Alla andra fält förblir oförändrade. Om fieldName är ogiltigt, <br/>            kommer alla fält att förbli oförändrade. |
| fill_barcode_field(field_name, data) | Fyll i ett streckkodsfält enligt dess fullständigt kvalificerade fältnamn. |
| import_fdf(input_fdf_stream) | Importerar innehållet i fälten från fdf-filen och placerar dem i den nya pdf-filen. |
| export_fdf(output_fdf_stream) | Exporterar innehållet i pdf-fältens data till fdf-strömmen. |
| export_xml(output_xml_stream) | Exporterar innehållet i pdf-fälten till xml-strömmen.<br/>            Värdet för knappfältet kommer inte att exporteras. |
| extract_xfa_data(output_xml_stream) | Extraherar XFA-datapaket |
| set_xfa_data(input_xml_stream) | Ersätter XFA-data med specificerat datapaket. Datapaketet kan extraheras med hjälp av ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Importerar innehållet i fälten från xfdf(xml)-filen och placerar dem i den nya pdf-filen. |
| export_xfdf(output_xfdf_stream) | Exporterar innehållet i pdf-fälten till xml-strömmen.<br/>            Värdet för knappfältet kommer inte att exporteras. |
| rename_field(field_name, new_field_name) | Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är OK. |
| get_rich_text(field_name) | Hämta ett Rich Text-fälts värde, inklusive formateringsinformation för varje tecken. |
| get_submit_flags(field_name) | Returnerar flaggorna för inskickningsknappen. |
| get_field_type(field_name) | Returnerar fältets typ. |
| is_required_field(field_name) | Avgör om fältet är obligatoriskt eller inte. |
| get_field_flag(field_name) | Returnerar fältets flaggor. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

