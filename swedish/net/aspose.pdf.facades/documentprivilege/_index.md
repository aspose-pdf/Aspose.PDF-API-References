---
title: DocumentPrivilege
second_title: Aspose.PDF för .NET API Referens
description: Representerar privilegierna för åtkomst till Pdf-fil. Hänvisa tillPdfFileSecurity./pdffilesecurity . Det finns fyra sätt att använda den här klassen 1.Användning av fördefinierad behörighet direkt. 2.Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3.Baserat på en fördefinierad behörighet och ändra någon specifik Adobe-kombination0 behörighet._x00d 4.Blandar way2 och way3.
type: docs
weight: 2240
url: /sv/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Representerar privilegierna för åtkomst till Pdf-fil. Hänvisa till[`PdfFileSecurity`](../pdffilesecurity) . Det finns fyra sätt att använda den här klassen: 1.Användning av fördefinierad behörighet direkt. 2.Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3.Baserat på en fördefinierad behörighet och ändra någon specifik Adobe-kombination0 behörighet._x00d 4.Blandar way2 och way3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall) { get; } | Alla tillåtna. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly) { get; } | Tillåter montering av fil. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy) { get; } | Tillåter kopiering av fil. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting) { get; } | Tillåter försämrad utskrift. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin) { get; } | Tillåter att fylla i formulär i fil. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall) { get; } | Alla förbjudna. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations) { get; } | Tillåter ändring av annoteringar av fil. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents) { get; } | Tillåter ändring av fil. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print) { get; } | Tillåter utskrift av fil. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders) { get; } | Tillåter endast läsare på skärmen. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly) { get; set; } | Anger behörigheten som tillåter montering eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy) { get; set; } | Anger behörigheten som tillåter kopiering eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting) { get; set; } | Anger behörigheten som tillåter försämrad utskrift eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin) { get; set; } | Anger behörighet som tillåter att fylla i formulär eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations) { get; set; } | Anger behörigheten som tillåter modifiering av kommentarer eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents) { get; set; } | Ställer in behörigheten som tillåter ändring av innehåll eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint) { get; set; } | Anger behörigheten som tillåter utskrift eller inte. true är tillåtet och falskt är förbjudet. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders) { get; set; } | Anger behörigheten som tillåter skärmläsare eller inte. true är tillåtet och falskt är förbjudet. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel) { set; } | Ställer in ändringsnivån för dokumentets behörighet. Precis som Adobe Professionals Ändringar tillåtna inställningar. 0: Inga. 1: Infoga, ta bort och rotera sidor. 2: Fylla i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i befintliga formulärfält, och signera signaturfält. 4: Alla utom extraherande sidor. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel) { set; } | Ställer in kopieringsnivån för dokumentets behörighet. Precis som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel) { set; } | Ställer in utskriftsnivån för dokumentets behörighet. Precis som Adobe Professionals Printing Allowed-inställningar. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto)(object) | Jämför två[`DocumentPrivilege`](../documentprivilege) objekt.  Objektet att jämföra med. Ett heltal med tecken som anger de relativa värdena för denna instans och värde. Mindre än noll denna instans är mindre än värdet. Noll denna instans är lika med värde. Större än noll denna instans är större än värdet. |

### Exempel

```csharp
[C#]	
//Way1: Använder fördefinierad behörighet direkt.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Baserat på en fördefinierad behörighet och ändra någon specifik Adobe Professional-behörighetskombination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Blandar way2 och way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Sätt 1: Använder fördefinierad behörighet direkt.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Sätt 2: Baserat på en fördefinierad behörighet och ändra några specifika behörigheter.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Sätt 3: Baserat på en fördefinierad behörighet och ändra någon specifik Adobe Professional-behörighetskombination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Blandar way2 och way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Se även

* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
