---
title: FormEditor
second_title: Aspose.PDF för .NET API Referens
description: Klass för redigering av formulär lägga till/ta bort fält etc
type: docs
weight: 2340
url: /sv/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Klass för redigering av formulär (lägga till/ta bort fält etc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Konstruktör för FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Initierar ny[`FormEditor`](../formeditor) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Hämtar eller ställer in namnet på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Hämtar eller ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om den här egenskapen inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Ställer in alternativ för kombinationsrutan med exportvärden. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Anger visuella attribut för fältet. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Ställer in objekt som kommer att läggas till i en nyskapad listruta eller kombinationsruta. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Hämtar eller ställer in storleken på alternativknappens objektstorlek (när ett nytt alternativknappfält läggs till). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | Medlemmen som ska spela in gapet mellan två angränsande radioknappar i pixlar, standard är 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Flaggan för att indikera om radioapparaterna är anordnade horisontellt eller vertikalt, standardvärdet är sant. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Hämtar eller ställer in svarsobjekt där resultatet av operationen kommer att lagras. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Hämtar eller ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Ställ in skicka-knappens inlämningsflaggor |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Lägg till fält av angiven typ i formuläret. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Lägg till fält av angiven typ i formuläret. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Lägg till JavaScript för ett tryckknappsfält. Om det finns en gammal händelse läggs en ny händelse till efter den. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Lägger till nytt objekt i listrutan. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Lägg till ett nytt objekt med exportvärde till det befintliga listboxfältet, endast för AcroForms kombinationsrutafält. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Lägg till knappen skicka i formuläret. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Stänger fasaden. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Kopierar ett befintligt fält till samma position i angivet sidnummer. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Kopierar ett befintligt fält till en ny position specificerad av både sidnummer och ordinater. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med originalsidnummer och ordinater. Observera: Endast för AcroForm-fält (exklusive radiobox). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och originalordinater. Observera: Endast för AcroForm-fält (exklusive radiobox). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och ordinater. Observera: Endast för AcroForm-fält (exklusive radiobox). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Ändrar visuella attribut för alla fält i PDF-dokumentet. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Ändrar visuella attribut för det angivna fältet. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Ta bort objekt från listfältet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Få fältflaggor. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Ställ in ny position för fältet. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Ta bort fält från formuläret. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Ta bort inlämningsåtgärd från fältet. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Ändra namn på fältet. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Återställ alla visuella attribut till tomt värde. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Återställ alla visuella attribut för inre fasad till tomt värde. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Ställ in justeringsstilen för ett textfält. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Ställ in stilen för vertikal justering av ett textfält. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Ange fältflaggor |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Ställ in attribut för fält. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Ställer in antalet kammar för ett vanligt enrads textfält (fältet är automatiskt uppdelat i lika många positioner med lika mellanrum, eller kammar, som värdet på parametern combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Anger maximalt antal tecken i textfältet. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Ställ in JavaScript för ett tryckknappsfält. Om gammalt JavaScript fanns kommer det att ersättas av det nya. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Ställ in skicka flagga för skicka knappen. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Anger URL för knappen. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Ändra ett enkelradigt textfält till ett flerradigt. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
