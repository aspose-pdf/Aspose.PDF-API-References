---
title: "Aspose::Pdf::Facades::DocumentPrivilege klass"
linktitle: "DocumentPrivilege"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::DocumentPrivilege klass. Representerar behörigheterna för åtkomst till Pdf‑fil. Se toPdfFileSecurity. Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3. Baserat på en fördefinierad behörighet och ändra en viss kombination av Adobe Professional‑behörigheter. 4. Blanda sätt 2 och sätt 3 i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class


Representerar behörigheterna för åtkomst till [Pdf](../../aspose.pdf/) fil. Se [PdfFileSecurity](../pdffilesecurity/). Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3. Baserat på en fördefinierad behörighet och ändra en viss kombination av Adobe Professional‑behörigheter. 4. Blanda sätt 2 och sätt 3.

```cpp
class DocumentPrivilege : public System::IComparable<System::SharedPtr<System::Object>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<System::Object\>) override | Jämför två [DocumentPrivilege](./) objekt. |
| static [get_AllowAll](./get_allowall/)() | Allt tillåtet. |
| [get_AllowAssembly](./get_allowassembly/)() | Ställer in behörigheten som tillåter sammansättning eller inte. true är tillåten och false är förbjuden. |
| [get_AllowCopy](./get_allowcopy/)() | Ställer in behörigheten som tillåter kopiering eller inte. true är tillåten och false är förbjuden. |
| [get_AllowDegradedPrinting](./get_allowdegradedprinting/)() | Ställer in behörigheten som tillåter degraderad utskrift eller inte. true är tillåten och false är förbjuden. |
| [get_AllowFillIn](./get_allowfillin/)() | Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true är tillåten och false är förbjuden. |
| [get_AllowModifyAnnotations](./get_allowmodifyannotations/)() | Ställer in behörigheten som tillåter modifiering av annoteringar eller inte. true är tillåten och false är förbjuden. |
| [get_AllowModifyContents](./get_allowmodifycontents/)() | Ställer in behörigheten som tillåter modifiering av innehåll eller inte. true är tillåten och false är förbjuden. |
| [get_AllowPrint](./get_allowprint/)() | Ställer in behörigheten som tillåter utskrift eller inte. true är tillåten och false är förbjuden. |
| [get_AllowScreenReaders](./get_allowscreenreaders/)() | Ställer in behörigheten som tillåter skärmläsare eller inte. true är tillåten och false är förbjuden. |
| static [get_Assembly](./get_assembly/)() | Tillåter sammansättning av fil. |
| [get_ChangeAllowLevel](./get_changeallowlevel/)() | Hämtar och anger ändringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställning Changes Allowed. 0: Ingen. 1: Infoga, radera och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fyll i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. |
| static [get_Copy](./get_copy/)() | Tillåter kopiering av fil. |
| [get_CopyAllowLevel](./get_copyallowlevel/)() | Hämtar och anger kopieringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. |
| static [get_DegradedPrinting](./get_degradedprinting/)() | Tillåter degraderad utskrift. |
| static [get_FillIn](./get_fillin/)() | Tillåter ifyllning av formulär i fil. |
| static [get_ForbidAll](./get_forbidall/)() | Allt förbjudet. |
| static [get_ModifyAnnotations](./get_modifyannotations/)() | Tillåter att ändra filens annotationer. |
| static [get_ModifyContents](./get_modifycontents/)() | Tillåter att ändra fil. |
| static [get_Print](./get_print/)() | Tillåter utskrift av fil. |
| [get_PrintAllowLevel](./get_printallowlevel/)() | Hämtar och anger utskriftsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. |
| static [get_ScreenReaders](./get_screenreaders/)() | Tillåter endast läsning på skärmen. |
| [set_AllowAssembly](./set_allowassembly/)(bool) | Ställer in behörigheten som tillåter sammansättning eller inte. true är tillåten och false är förbjuden. |
| [set_AllowCopy](./set_allowcopy/)(bool) | Ställer in behörigheten som tillåter kopiering eller inte. true är tillåten och false är förbjuden. |
| [set_AllowDegradedPrinting](./set_allowdegradedprinting/)(bool) | Ställer in behörigheten som tillåter degraderad utskrift eller inte. true är tillåten och false är förbjuden. |
| [set_AllowFillIn](./set_allowfillin/)(bool) | Ställer in behörigheten som tillåter ifyllning av formulär eller inte. true är tillåten och false är förbjuden. |
| [set_AllowModifyAnnotations](./set_allowmodifyannotations/)(bool) | Ställer in behörigheten som tillåter modifiering av annoteringar eller inte. true är tillåten och false är förbjuden. |
| [set_AllowModifyContents](./set_allowmodifycontents/)(bool) | Ställer in behörigheten som tillåter modifiering av innehåll eller inte. true är tillåten och false är förbjuden. |
| [set_AllowPrint](./set_allowprint/)(bool) | Ställer in behörigheten som tillåter utskrift eller inte. true är tillåten och false är förbjuden. |
| [set_AllowScreenReaders](./set_allowscreenreaders/)(bool) | Ställer in behörigheten som tillåter skärmläsare eller inte. true är tillåten och false är förbjuden. |
| [set_ChangeAllowLevel](./set_changeallowlevel/)(int32_t) | Hämtar och anger ändringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställning Changes Allowed. 0: Ingen. 1: Infoga, radera och rotera sidor. 2: Fyll i formulärfält och signera befintliga signaturfält. 3: Kommentera, fyll i formulärfält och signera befintliga signaturfält. 4: Allt förutom att extrahera sidor. |
| [set_CopyAllowLevel](./set_copyallowlevel/)(int32_t) | Hämtar och anger kopieringsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals behörighetsinställningar. 0: Ingen. 1: Aktivera textåtkomst för skärmläsarenheter för synskadade. 2: Aktivera kopiering av text, bilder och annat innehåll. |
| [set_PrintAllowLevel](./set_printallowlevel/)(int32_t) | Hämtar och anger utskriftsnivån för dokumentets behörighet. På samma sätt som Adobe Professionals inställningar för Tillåten utskrift. 0: Ingen. 1: Låg upplösning (150 dpi). 2: Hög upplösning. |
## Se även

* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
