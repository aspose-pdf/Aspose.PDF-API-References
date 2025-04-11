---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege klass. Representerar privilegier för att få åtkomst till Pdf-fil. Se PdfFileSecurity. Det finns 4 sätt att använda denna klass: 1. Använda fördefinierat privilegium direkt. 2. Baserat på ett fördefinierat privilegium och ändra vissa specifika behörigheter. 3. Baserat på ett fördefinierat privilegium och ändra vissa specifika kombinationer av Adobe Professional-behörigheter. 4. Blandar sätt 2 och sätt 3.
type: docs
weight: 4230
url: /sv/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege klass

Representerar privilegier för att få åtkomst till Pdf-fil. Se [`PdfFileSecurity`](../pdffilesecurity/). Det finns 4 sätt att använda denna klass: 1. Använda fördefinierat privilegium direkt. 2. Baserat på ett fördefinierat privilegium och ändra vissa specifika behörigheter. 3. Baserat på ett fördefinierat privilegium och ändra vissa specifika kombinationer av Adobe Professional-behörigheter. 4. Blandar sätt 2 och sätt 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Alla tillåtna. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Tillåter sammansättning av fil. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Tillåter kopiering av fil. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Tillåter försämrad utskrift. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Tillåter ifyllning av formulär i fil. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Alla förbjudna. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Tillåter modifiering av anteckningar i fil. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Tillåter modifiering av fil. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Tillåter utskrift av fil. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Tillåter att läsa på skärmen endast. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Ställer in behörigheten som tillåter sammansättning eller inte. true är tillåten och false är förbjuden. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Ställer in behörigheten som tillåter kopiering eller inte. true är tillåten och false är förbjuden. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Ställer in behörigheten som tillåter försämrad utskrift eller inte. true är tillåten och false är förbjuden. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true är tillåten och false är förbjuden. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Ställer in behörigheten som tillåter modifiering av anteckningar eller inte. true är tillåten och false är förbjuden. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Ställer in behörigheten som tillåter modifiering av innehåll eller inte. true är tillåten och false är förbjuden. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Ställer in behörigheten som tillåter utskrift eller inte. true är tillåten och false är förbjuden. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Ställer in behörigheten som tillåter skärmläsare eller inte. true är tillåten och false är förbjuden. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Hämtar och ställer in ändringsnivån för dokumentets privilegium. Precis som Adobe Professionals inställningar för tillåtna ändringar. 0: Inga. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt utom att extrahera sidor. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Hämtar och ställer in kopieringsnivån för dokumentets privilegium. Precis som Adobe Professionals behörighetsinställningar. 0: Inga. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Hämtar och ställer in utskriftsnivån för dokumentets privilegium. Precis som Adobe Professionals inställningar för tillåten utskrift. 0: Inga. 1: Låg upplösning (150 dpi). 2: Hög upplösning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Jämför två `DocumentPrivilege` objekt. Objektet att jämföra med. Ett signerat heltal som indikerar de relativa värdena för denna instans och värdet. Mindre än noll, denna instans är mindre än värdet. Noll, denna instans är lika med värdet. Större än noll, denna instans är större än värdet. |

## Exempel

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Se Även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)