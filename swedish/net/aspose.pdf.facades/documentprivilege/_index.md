---
title: "Klass DocumentPrivilege"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.DocumentPrivilege-klass. Representerar behörigheterna för åtkomst till Pdf-fil. Se PdfFileSecurity. Det finns 4 sätt att använda denna klass 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3. Baserat på en fördefinierad behörighet och ändra en viss kombination av Adobe Professional-behörigheter. 4. Blanda sätt 2 och sätt 3."
type: docs
weight: 4350
url: /sv/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Representerar behörigheterna för åtkomst till Pdf-fil. Se [`PdfFileSecurity`](../pdffilesecurity/). Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3. Baserat på en fördefinierad behörighet och ändra en viss kombination av Adobe Professional-behörigheter. 4. Blanda sätt 2 och sätt 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Alla tillåtna. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Tillåter montering av fil. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Tillåter kopiering av fil. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Tillåter degraderad utskrift. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Tillåter ifyllning av formulär i fil. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Alla förbjudna. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Tillåter modifiering av annotationer i fil. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Tillåter modifiering av fil. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Tillåter utskrift av fil. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Tillåter endast läsning på skärm. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Ställer in behörigheten som tillåter montering eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Ställer in behörigheten som tillåter kopiering eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Ställer in behörigheten som tillåter degraderad utskrift eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Ställer in behörigheten som tillåter att fylla i formulär eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Ställer in behörigheten som tillåter att ändra annotationer eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Ställer in behörigheten som tillåter att ändra innehåll eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Ställer in behörigheten som tillåter utskrift eller inte. true betyder tillåten och false betyder förbjuden. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Ställer in behörigheten som tillåter skärmläsare eller inte. true betyder tillåten och false betyder förbjuden. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Hämtar och anger ändringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställning för tillåtna ändringar. 0: Ingen. 1: Infoga, ta bort och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fylla i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Hämtar och anger kopieringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Hämtar och anger utskriftsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställning för tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Jämför två `DocumentPrivilege`-objekt.  Objektet att jämföra med. Ett signerat heltal som indikerar de relativa värdena för detta objekt och värdet. Mindre än noll betyder att detta objekt är mindre än värdet. Noll betyder att detta objekt är lika med värdet. Större än noll betyder att detta objekt är större än värdet. |

## Exempel

```csharp
[C#]	
//Way1: Använder fördefinierad behörighet direkt.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Baserat på en fördefinierad behörighet och ändra en viss kombination av Adobe Professionals specifika behörigheter.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Blandar way2 och way3
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

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


