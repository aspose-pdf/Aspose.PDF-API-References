---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor klass. Klass för att redigera formulär, lägga till/ta bort fält etc.
type: docs
weight: 4330
url: /sv/net/aspose.pdf.facades/formeditor/
---
## FormEditor klass

Klass för att redigera formulär (lägga till/ta bort fält etc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Konstruktör för FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Initierar ett nytt `FormEditor` objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om denna egenskap inte anges kommer filen att sparas i standard PDF-format utan konvertering. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentet som fasaden arbetar med. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Ställer in alternativ för kombinationsruta med exportvärden. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Ställer in visuella attribut för fältet. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Ställer in objekt som kommer att läggas till i den nyss skapade listboxen eller kombinationsrutan. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Hämtar eller ställer in storleken på radioknappens objektstorlek (när ett nytt radioknappfält läggs till). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Medlem för att registrera avståndet mellan två närliggande radioknappar i pixlar, standard är 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Flagga för att ange om radioknapparna är ordnade horisontellt eller vertikalt, standardvärde är sant. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Ställ in submit-knappens inlämningsflaggor |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Lägger till ett fält av angiven typ till formuläret. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Lägger till ett fält av angiven typ till formuläret. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Lägger till JavaScript för ett PushButton-fält. Om ett gammalt evenemang finns, läggs det nya evenemanget till efter det. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Lägger till ett nytt objekt i listboxen. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Lägger till ett nytt objekt med exportvärde till det befintliga listboxfältet, endast för AcroForm kombinationsrutor. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Lägger till en submit-knapp på formuläret. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Stänger fasaden. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Kopierar ett befintligt fält till samma position i angivet sidnummer. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Kopierar ett befintligt fält till en ny position angiven av både sidnummer och koordinater. Ett nytt dokument kommer att produceras, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med original sidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Kopierar ett befintligt fält från ett PDF-dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm-fält (exklusive radioknapp). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Ändrar visuella attribut för alla fält i PDF-dokumentet. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Ändrar visuella attribut för alla fält med den angivna fälttypen. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Ändrar visuella attribut för det angivna fältet. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Tar bort objekt från listfältet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Hämtar fältflaggor. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Ställer in ny position för fältet. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Tar bort fältet från formuläret. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Tar bort inlämningsåtgärden för fältet. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Ändrar namnet på fältet. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Återställer alla visuella attribut till tomt värde. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Återställer alla visuella attribut för inre fasad till tomt värde. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Ställer in justeringsstil för ett textfält. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Ställer in vertikal justeringsstil för ett textfält. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Ställer in fältflaggor |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Ställer in attribut för fältet. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Ställer in antal kombinationer för ett vanligt enradigt textfält (fältet delas automatiskt upp i så många lika avstånd som värdet av parametern combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Ställer in maximalt antal tecken för textfältet. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Ställer in JavaScript för ett PushButton-fält. Om gammal JavaScript fanns, kommer den att ersättas av den nya. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Ställer in inlämningsflagga för submit-knappen. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Ställer in URL för knappen. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Ändrar ett enradigt textfält till ett flerradigt. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../)