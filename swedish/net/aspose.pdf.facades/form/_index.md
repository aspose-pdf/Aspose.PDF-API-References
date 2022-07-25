---
title: Form
second_title: Aspose.PDF för .NET API Referens
description: Klass som representerar Acro-formulärobjekt.
type: docs
weight: 2300
url: /sv/net/aspose.pdf.facades/form/
---
## Form class

Klass som representerar Acro-formulärobjekt.

```csharp
public sealed class Form : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Form](form#constructor)() | Formkonstruktion utan parametrar. |
| [Form](form#constructor_1)(Document) | Initierar ny[`Form`](../form) objekt på basen av*document* . |
| [Form](form#constructor_4)(Stream) | Konstruktör för form. |
| [Form](form#constructor_8)(string) | Formkonstruktör. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Hämtar eller ställer in namnet på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Hämtar eller ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om den här egenskapen inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Hämtar lista med fältnamn på formuläret. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Får alla namn på knappen för formulärsändning. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Resultat av senaste importåtgärd. Array av objekt som beskriver resultatet av import för varje fält. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Hämtar eller ställer in svarsobjekt där resultatet av operationen kommer att lagras. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Hämtar eller ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/form/close)() | Stänger öppnade filer utan några ändringar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Exporterar innehållet i fälten i pdf:en till fdf-strömmen. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Exporterar innehållet i fälten i pdf:en till xml-strömmen. Knappfältets värde kommer inte att exporteras. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Exporterar innehållet i fälten i pdf:en till xml-strömmen. Knappfältets värde kommer inte att exporteras. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Extraherar XFA-datapaket |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Fyll ett streckkodsfält enligt dess fullständiga fältnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Fyller kryssrutan med ett booleskt värde. Observera: Används endast för kryssrutan. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella -fältnamn i motsats till Aspose.Pdf .Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.CheckBoxField" bör du ange fullständigt namn och inte "CheckBoxField". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Fyller radioboxfältet med ett giltigt indexvärde enligt ett fullt kvalificerat fältnamn. Innan du fyller i fälten måste endast fältets namn vara känt. Medan värdet kan specificeras av dess index. Observera: Används endast för radiobox-, kombinationsbox- och listboxfält. Observera att Aspose.Pdf.Facades endast stöder fullständiga fältnamn och inte fungerar med partiella -fältnamn i motsats till Aspose.Pdf.Kit; Till exempel om fältet har det fullständiga namnet "Form.Subform.ListBoxField" ska du ange fullständigt namn och inte "ListBoxField". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Fyller fältet med ett giltigt värde enligt ett fullständigt kvalificerat fältnamn. Innan du fyller i fälten måste varje fälts namn och dess motsvarande giltiga värden vara kända. Både fältens namn och värden är skiftlägeskänsliga. Observera att Aspose.Pdf.Facades stöder endast fullständiga fältnamn och fungerar inte med partiella fältnamn i motsats till Aspose.Pdf.Kit; Om t.ex. fältet har fullständigt namn "Form.Subform.TextField" ska du ange fullständigt namn och inte "Textfält". Du kan använda FieldNames-egenskapen för att utforska befintliga fältnamn och söka efter obligatoriskt fält med dess delnamn. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Fyll ett fält med flera val. Notera: endast för AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Fyller fältet med angivet värde. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Fyller textrutans fält med ett textvärde och spara dokumentet. Relevant för signerade dokument. Observera: Används endast för textruta. Både fältens namn och värden är skiftlägeskänsliga. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Överlastar funktionen för FillImageField. Ingången är en bildström. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Klistrar in en bild på det befintliga knappfältet som dess utseende enligt dess fullständiga fältnamn. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Plattar ut alla fält. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Plattar ut ett specificerat fält med det fullständiga fältnamnet. Alla andra fält förblir oföränderliga. Om fältnamnet är ogiltigt kommer alla fält att förbli oföränderliga. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Returnerar det aktuella värdet för alternativknappsfälten. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Hämtar alternativknappsfälten och relaterade värden baserat på fältnamnet. Denna metod har betydelse för alternativknappsgrupper. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Hämtar fältets värde enligt dess fältnamn. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Returnerar FromFieldFacade-objekt som innehåller alla utseendeattribut. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Returnerar fältets flaggor. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Få textfältets begränsning. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Returnerar typ av fält. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Får det fullständiga fältnamnet enligt dess korta fältnamn. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Få ett Rich Text-fälts värde, inklusive formatinf-information för varje tecken. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Returnerar submit-knappens submission flags |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Importerar innehållet i fälten från fdf-filen och lägger in dem i den nya pdf-filen. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Importerar innehållet i fälten från xfdf(xml)-filen och lägger in dem i den nya pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Importerar innehållet i fälten från xml-filen och lägger in dem i den nya pdf-filen. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Importerar innehållet i fälten från xml-filen och lägger in dem i den nya pdf-filen. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Bestämmer om fältet är obligatoriskt eller inte. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Byter namn på ett fält. Antingen AcroForm-fältet eller XFA-fältet är OK. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Sparar dokument i angiven ström. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Sparar dokument i angiven fil. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Ersätter XFA-data med specificerat datapaket. Datapaket kan extraheras med ExtractXfaData. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Klass som beskriver resultatet vid import av fält. |
| enum [ImportStatus](form.importstatus) | Status för importerat fält |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
