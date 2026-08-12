---
title: "Aspose::Pdf::Facades::FormEditor class"
linktitle: "FormEditor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::FormEditor class. Klass för att redigera formulär (lägga till/ta bort fält etc) i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf.facades/formeditor/
---
## FormEditor class


Klass för redigering av formulär (lägg till/ta bort fält etc)

```cpp
class FormEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddField](./addfield/)(FieldType, const System::String\&, int32_t, float, float, float, float) | Lägg till fält av angiven typ i formuläret. |
| [AddField](./addfield/)(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) | Lägg till fält av angiven typ i formuläret. |
| [AddFieldScript](./addfieldscript/)(const System::String\&, const System::String\&) | Lägg till JavaScript för ett PushButton-fält. Om ett gammalt händelse finns, läggs den nya händelsen till efter den. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::String\&) | Lägger till ett nytt objekt i listbox. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Lägg till ett nytt objekt med Export‑värde i det befintliga listbox‑fältet, endast för AcroForm‑kombinationsruta. |
| [AddSubmitBtn](./addsubmitbtn/)(const System::String\&, int32_t, const System::String\&, const System::String\&, float, float, float, float) | Lägg till en skicka‑knapp på formuläret. |
| [Close](./close/)() override | Stänger fasaden. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t) | Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Kopierar ett befintligt fält till en ny position som anges av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [DecorateField](./decoratefield/)(const System::String\&) | Ändrar visuella attribut för det angivna fältet. |
| [DecorateField](./decoratefield/)(FieldType) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [DecorateField](./decoratefield/)() | Ändrar visuella attribut för alla fält i PDF‑dokumentet. |
| [DelListItem](./dellistitem/)(const System::String\&, const System::String\&) | Ta bort objekt från listfältet. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Konstruktor för [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::String\&, const System::String\&) | Konstruktor för [FormEditor](./). |
| [FormEditor](./formeditor/)() | Konstruktor för [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [FormEditor](./)-objekt baserat på *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [FormEditor](./)-objekt baserat på *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initierar ett nytt [FormEditor](./)-objekt baserat på *document*. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar [FormEditor](./) som sparar resultatet i ett HttpResponse‑objekt. |
| [FormEditor](./formeditor/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Skapar [FormEditor](./) som sparar resultatet i ett HttpResponse‑objekt. |
| [get_AttachmentName](./get_attachmentname/)() const | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse‑objekt som bilaga. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i ett HttpResponse‑objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [get_DestFileName](./get_destfilename/)() const | Hämtar destinationsfilens namn. |
| [get_DestStream](./get_deststream/)() const | Hämtar destinationsström. |
| [get_ExportItems](./get_exportitems/)() const | Ställer in alternativ för kombinationsruta med exportvärden. |
| [get_Facade](./get_facade/)() const | Ställer in visuella attribut för fältet. |
| [get_Items](./get_items/)() const | Ställer in objekt som kommer att läggas till i nyss skapad listbox eller kombinationsruta. |
| [get_RadioButtonItemSize](./get_radiobuttonitemsize/)() const | Hämtar storleken på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { \"First\", \"Second\", \"Third\" }; formEditor.AddField([FieldType.Radio](../fieldtype/), \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [get_RadioGap](./get_radiogap/)() | Medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [get_RadioHoriz](./get_radiohoriz/)() const | Flaggan för att ange om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [get_Response](./get_response/)() const | Hämtar Response-objektet där resultatet av operationen kommer att lagras. |
| [get_SaveOptions](./get_saveoptions/)() const | Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Hämtar namnet på källfilen. |
| [get_SrcStream](./get_srcstream/)() const | Hämtar källströmmen. |
| [get_SubmitFlag](./get_submitflag/)() const | Ställ in inskickningsknappens inskickningsflaggor. |
| [GetFieldAppearance](./getfieldappearance/)(const System::String\&) | Hämta fältflaggor. |
| [MoveField](./movefield/)(const System::String\&, float, float, float, float) | Ställ in ny position för fältet. |
| [RemoveField](./removefield/)(const System::String\&) | Ta bort fältet från formuläret. |
| [RemoveFieldAction](./removefieldaction/)(const System::String\&) | Ta bort inskickningsåtgärden för fältet. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Ändra fältets namn. |
| [ResetFacade](./resetfacade/)() | Återställ alla visuella attribut till tomt värde. |
| [ResetInnerFacade](./resetinnerfacade/)() | Återställ alla visuella attribut för den inre fasaden till tomt värde. |
| [Save](./save/)() | Sparar ändringar i destinationsfilen. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Ställer in PDF-filformat. Resultatfilen sparas i det angivna filformatet. Om denna egenskap inte specificeras sparas filen i standard PDF-format utan konvertering. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Ställer in destinationsfilens namn. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in destinationsströmmen. |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Ställer in alternativ för kombinationsruta med exportvärden. |
| [set_Facade](./set_facade/)(const System::SharedPtr\<FormFieldFacade\>\&) | Ställer in visuella attribut för fältet. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Ställer in objekt som kommer att läggas till i nyss skapad listbox eller kombinationsruta. |
| [set_RadioButtonItemSize](./set_radiobuttonitemsize/)(double) | Ställer in storleken på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [set_RadioGap](./set_radiogap/)(float) | Medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [set_RadioHoriz](./set_radiohoriz/)(bool) | Flaggan för att ange om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Ställer in Response-objektet där resultatet av operationen kommer att lagras. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Ställer in namn på källfilen. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in källströmmen. |
| [set_SubmitFlag](./set_submitflag/)(SubmitFormFlag) | Ställ in inskickningsknappens inskickningsflaggor. |
| [SetFieldAlignment](./setfieldalignment/)(const System::String\&, int32_t) | Ställ in justeringsstilen för ett textfält. |
| [SetFieldAlignmentV](./setfieldalignmentv/)(const System::String\&, int32_t) | Ställ in den vertikala justeringsstilen för ett textfält. |
| [SetFieldAppearance](./setfieldappearance/)(const System::String\&, Annotations::AnnotationFlags) | Ange fältflaggor. |
| [SetFieldAttribute](./setfieldattribute/)(const System::String\&, PropertyFlag) | Ange attribut för fältet. |
| [SetFieldCombNumber](./setfieldcombnumber/)(const System::String\&, int32_t) | Ställer in antalet kammar för ett vanligt enkellinjigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller kammar, som värdet på parametern combNumber). |
| [SetFieldLimit](./setfieldlimit/)(const System::String\&, int32_t) | Ställer in maximalt teckenantal för textfältet. |
| [SetFieldScript](./setfieldscript/)(const System::String\&, const System::String\&) | Ange JavaScript för ett PushButton-fält. Om tidigare JavaScript fanns, kommer det att ersättas av det nya. |
| [SetSubmitFlag](./setsubmitflag/)(const System::String\&, SubmitFormFlag) | Ange sändningsflagga för sändningsknappen. |
| [SetSubmitUrl](./setsubmiturl/)(const System::String\&, const System::String\&) | Ställer in URL för knappen. |
| [Single2Multiple](./single2multiple/)(const System::String\&) | Ändra ett enkellinjigt textfält till ett flerradigt. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
