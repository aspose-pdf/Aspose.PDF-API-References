---
title: "Aspose::Pdf::Facades::Form klass"
linktitle: "Form"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::Form klass. Klass som representerar Acro-formulärobjekt i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/form/
---
## Form class


Klass som representerar Acro‑formobjekt.

```cpp
class Form : public Aspose::Pdf::Facades::SaveableFacade
```

## Nested classes

* Class [FormImportResult](./formimportresult/)
## Enums

| Enum | Beskrivning |
| --- | --- |
| [ImportStatus](./importstatus/) | Status för importerat fält. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger öppna filer utan några ändringar. |
| [ExportFdf](./exportfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporterar innehållet i pdf-fältens till fdf-strömmen. |
| [ExportXfdf](./exportxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporterar innehållet i pdf-fältens till xml-strömmen. Knappfältets värde kommer inte att exporteras. |
| [ExportXml](./exportxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporterar innehållet i pdf-fältens till xml-strömmen. Knappfältets värde kommer inte att exporteras. |
| [ExtractXfaData](./extractxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Extraherar XFA-datapaket. |
| [FillBarcodeField](./fillbarcodefield/)(const System::String\&, const System::String\&) | Fyll i ett streckkodsfält enligt dess fullständigt kvalificerade fältnamn. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&) | Fyller i fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste varje fältnamns namn och dess motsvarande giltiga värden vara kända. Både fältnamnen och värdena är skiftlägeskänsliga. Observera att [Aspose.Pdf.Facades](../) endast stödjer fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har fullständigt namn "Form.Subform.TextField" ska du ange det fullständiga namnet och inte "TextField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](./fillfield/)(const System::String\&, int32_t) | Fyller i radioknappsfältet med ett giltigt indexvärde enligt ett fullständigt kvalificerat fältnamn. Innan fälten fylls i måste endast fältets namn vara känt. Värdet kan specificeras med dess index. Obs: Detta gäller endast för Radio Box-, Combo Box- och List Box-fält. Observera att [Aspose.Pdf.Facades](../) endast stödjer fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har fullständigt namn "Form.Subform.ListBoxField" ska du ange det fullständiga namnet och inte "ListBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](./fillfield/)(const System::String\&, bool) | Fyller i kryssrutan med ett booleskt värde. Obs: Detta gäller endast för Check Box. Observera att [Aspose.Pdf.Facades](../) endast stödjer fullständiga fältnamn och inte fungerar med partiella fältnamn i kontrast till Aspose.Pdf.Kit; Till exempel om fältet har fullständigt namn "Form.Subform.CheckBoxField" ska du ange det fullständiga namnet och inte "CheckBoxField". Du kan använda egenskapen FieldNames för att utforska befintliga fältnamn och söka efter önskat fält via dess partiella namn. |
| [FillField](./fillfield/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Fyll i ett fält med flera val. Obs: endast för AcroForm List Box-fält. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&, bool) | Fyller fältet med angivet värde. |
| [FillFields](./fillfields/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<System::String\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Fyller i textrutefälten med textvärden och sparar dokumentet. Relevant för signerade dokument. Obs: Detta gäller endast för [Text](../../aspose.pdf.text/) Box. Både fältens namn och värden är skiftlägeskänsliga. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::String\&) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständigt kvalificerade fältnamn. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Överlagrar funktionen FillImageField. Inmatningen är en bildström. |
| [FlattenAllFields](./flattenallfields/)() | Plattar till alla fält. |
| [FlattenField](./flattenfield/)(const System::String\&) | Plattar till ett specificerat fält med det fullständigt kvalificerade fältnamnet. Alla andra fält förblir oförändrade. Om fieldName är ogiltigt, förblir alla fält oförändrade. |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor för [Form](./) med två strömparametrar. Ange samma källa- och destinationsström för inkrementell uppdatering. |
| [Form](./form/)() | Konstruktor för [Form](./) utan parametrar. |
| [Form](./form/)(const System::String\&) | Konstruktor för [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor för formulär. |
| [Form](./form/)(const System::String\&, const System::String\&) | Konstruktor för klassen [Form](./). Ange samma källfilnamn och destinationsfilnamn för att utföra inkrementell uppdatering. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor för [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Konstruktor för [Form](./). |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [Form](./)-objekt baserat på *dokumentet*. |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [Form](./)-objekt baserat på *dokumentet*. |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar ett nytt [Form](./)-objekt baserat på *dokumentet*. |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar ett formulär som sparar resultatet i ett HttpResponse-objekt. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar ett formulär som sparar resultatet i ett HttpResponse-objekt. |
| [get_AttachmentName](./get_attachmentname/)() const | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse‑objekt som bilaga. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i ett HttpResponse‑objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [get_DestFileName](./get_destfilename/)() const | Hämtar destinationsfilnamn. |
| [get_DestStream](./get_deststream/)() const | Hämtar destinationsström. |
| [get_FieldNames](./get_fieldnames/)() | Hämtar lista över fältnamn i formuläret. |
| [get_FormSubmitButtonNames](./get_formsubmitbuttonnames/)() | Hämtar alla namn på formulärets inskickningsknappar. |
| [get_ImportResult](./get_importresult/)() | Resultat av den senaste importoperationen. En array av objekt som beskriver importresultatet för varje fält. |
| [get_Response](./get_response/)() const | Hämtar Response-objektet där resultatet av operationen kommer att lagras. |
| [get_SaveOptions](./get_saveoptions/)() const | Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Hämtar källfilnamn. |
| [get_SrcStream](./get_srcstream/)() const | Hämtar källströmmen. |
| [GetButtonOptionCurrentValue](./getbuttonoptioncurrentvalue/)(const System::String\&) | Returnerar det aktuella värdet för radioknappsalternativfält. |
| [GetButtonOptionValues](./getbuttonoptionvalues/)(const System::String\&) | Hämtar radioknappsalternativfälten och relaterade värden baserat på fältnamnet. Denna metod är relevant för radioknappsgupper. |
| [GetField](./getfield/)(const System::String\&) | Hämtar fältets värde enligt dess fältnamn. |
| [GetFieldFacade](./getfieldfacade/)(const System::String\&) | Returnerar ett FrofmFieldFacade-objekt som innehåller alla utseendeattribut. |
| [GetFieldFlag](./getfieldflag/)(const System::String\&) | Returnerar fältets flaggor. |
| [GetFieldLimit](./getfieldlimit/)(const System::String\&) | Hämta begränsningen för textfältet. |
| [GetFieldType](./getfieldtype/)(const System::String\&) | Returnerar fälttyp. |
| [GetFullFieldName](./getfullfieldname/)(const System::String\&) | Hämtar det fullständiga fältnamnet enligt dess korta fältnamn. |
| [GetRichText](./getrichtext/)(const System::String\&) | Hämta ett Rich [Text](../../aspose.pdf.text/)-fältvärde, inklusive formateringsinformation för varje tecken. |
| [GetSubmitFlags](./getsubmitflags/)(const System::String\&) | Returnerar inskickningsknappens inskickningsflaggor. |
| [ImportFdf](./importfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar innehållet i fälten från fdf-filen och placerar dem i den nya pdf-filen. |
| [ImportXfdf](./importxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar innehållet i fälten från xfdf(xml)-filen och placerar dem i den nya pdf-filen. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar innehållet i fälten från xml-filen och placerar dem i den nya pdf-filen. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Importerar innehållet i fälten från xml-filen och placerar dem i den nya pdf-filen. |
| [IsRequiredField](./isrequiredfield/)(const System::String\&) | Bestämmer om fältet är obligatoriskt eller inte. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Byter namn på ett fält. Antingen AcroForm-fält eller XFA-fält är OK. |
| [Save](./save/)() | Sparar värdet på de ifyllda fälten och stänger det öppnade [Pdf](../../aspose.pdf/) dokumentet. |
| [Save](./save/)(System::String) override | Sparar dokumentet i angiven fil. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar dokumentet i angiven ström. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Ställer in PDF-filformat. Resultatfilen sparas i det angivna filformatet. Om denna egenskap inte specificeras sparas filen i standard PDF-format utan konvertering. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Ställer in destinationsfilnamn. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in destinationsströmmen. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Ställer in Response-objektet där resultatet av operationen kommer att lagras. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Ställer in källfilnamn. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in källströmmen. |
| [SetXfaData](./setxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ersätter XFA-data med angivet datapaket. Datapaketet kan extraheras med hjälp av ExtractXfaData. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
