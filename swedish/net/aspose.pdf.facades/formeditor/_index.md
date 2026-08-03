---
title: "Klass FormEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.FormEditor klass. Klass för att redigera formulär, lägga till/ta bort fält etc"
type: docs
weight: 4450
url: /sv/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Klass för redigering av formulär (lägg till/ta bort fält etc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Konstruktor för FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Initierar nytt `FormEditor`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Ställer in alternativ för kombinationsruta med exportvärden. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Ställer in visuella attribut för fältet. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Hämtar eller sätter storlek på radioknappselement (när ett nytt radioknappfält läggs till). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Flaggan som indikerar om radioknapparna är ordnade horisontellt eller vertikalt, standardvärdet är true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Ställ in skicka-knappens inskickningsflaggor |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Lägg till fält av angiven typ till formuläret. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Lägg till fält av angiven typ till formuläret. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Lägg till JavaScript för ett PushButton-fält. Om ett gammalt händelse finns, läggs den nya händelsen till efter den. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Lägger till ett nytt objekt i listboxen. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Lägg till ett nytt objekt med Export‑värde till det befintliga listboxfältet, endast för AcroForm combo box field. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Lägg till en skicka‑knapp på formuläret. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Stänger fasaden. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Enda för AcroForm‑fält (exklusive radioknappar). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Ändrar visuella attribut för alla fält i PDF‑dokumentet. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Ändrar visuella attribut för det angivna fältet. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Ta bort objekt från listfältet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Hämta fältflaggor. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Ställ in ny position för fältet. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Ta bort fält från formuläret. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Ta bort skicka‑åtgärd för fältet. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Ändra namn på fältet. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Återställ alla visuella attribut till tomt värde. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Återställ alla visuella attribut för den inre fasaden till tomt värde. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Ställ in justeringsstilen för ett textfält. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Ställ in den vertikala justeringsstilen för ett textfält. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Ställ in fältflaggor |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Ställ in attribut för fältet. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Ställer in antalet fack för ett vanligt enkellinjigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller fack, som värdet på parametern combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Ställer in maximalt teckenantal för textfältet. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Ställ in JavaScript för ett PushButton-fält. Om tidigare JavaScript fanns, kommer det att ersättas av den nya. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Ställ in submit‑flaggan för submit‑knappen. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Ställer in URL för knappen. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Ändra ett enkellinjigt textfält till ett flerradigt. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


