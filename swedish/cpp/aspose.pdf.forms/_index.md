---
title: "Aspose::Pdf::Forms namnrymd"
linktitle: "Aspose::Pdf::Forms"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms namnrymd. Aspose.Pdf.Forms namnrymd har klasser som beskriver formulär (standard, statiska, dynamiska) och olika typer av fält som textruta, listruta, radioknapp etc i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf.forms/
---

Den **[Aspose.Pdf.Forms](./)** namnrymden har klasser som beskriver formulär (standard, statiska, dynamiska) och olika typer av fält som textruta, listruta, radioknapp etc.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BarcodeField](./barcodefield/) | Klassen representerar streckkodsfält. |
| [ButtonField](./buttonfield/) | Klassen representerar tryckknappsfält. |
| [CheckboxField](./checkboxfield/) | Klassen som representerar kryssrutfält. |
| [ChoiceField](./choicefield/) | Representerar basklass för valfält. |
| [ComboBoxField](./comboboxfield/) | Klassen som representerar kombinationsrutfält i formuläret. |
| [DateField](./datefield/) | Datumfält med kalendervy. |
| [DocMDPSignature](./docmdpsignature/) | Representerar klassen för dokument-MDP (modifieringsdetektering och förebyggande) signaturtyp. |
| [ExternalSignature](./externalsignature/) | Skapar en fristående PKCS#7-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar. |
| [Field](./field/) | Basklass för acro-formulärfält. |
| [FileSelectBoxField](./fileselectboxfield/) | [Field](./field/) för filväljarruta element. |
| [Form](./form/) | Klass som representerar formulärobjekt. |
| [IconFit](./iconfit/) | Beskriver hur widget-annotationens ikon ska visas inom dess annoteringsrektangel. |
| [ListBoxField](./listboxfield/) | Klass representerar ListBox-fält. |
| [NumberField](./numberfield/) | [Text](../aspose.pdf.text/)[Field](./field/) med angivna giltiga tecken. |
| [Option](./option/) | Klass representerar alternativ för valfält. |
| [OptionCollection](./optioncollection/) | Klass som representerar samling av alternativ för valfältet. |
| [PasswordBoxField](./passwordboxfield/) | Klass beskriver textfält för att ange lösenord. |
| [PKCS1](./pkcs1/) | Representerar signaturobjekt enligt PKCS#1-standarden. RSA-krypteringsalgoritm och SHA-1-digestmetod används för signering. |
| [PKCS7](./pkcs7/) | Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. **SHA1 digest** av dokumentets byteintervall kapslas in i PKCS#7 SignedData-fältet. |
| [PKCS7Detached](./pkcs7detached/) | Representerar PKCS#7-objektet som följer PKCS#7-specifikationen i Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. Den ursprungliga signerade meddelandedigesten över dokumentets byteintervall införlivas som det normala PKCS#7 SignedData-fältet. Ingen data ska kapslas in i PKCS#7 SignedData-fältet. |
| [RadioButtonField](./radiobuttonfield/) | Klass som representerar radioknappsfält. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Klass representerar objekt i RadioButton-fält. |
| [RichTextBoxField](./richtextboxfield/) | Klass beskriver komponent för rik textredigerare. |
| [Signature](./signature/) | En abstrakt klass som representerar signaturobjekt i pdf-dokumentet. [Signatures](../aspose.pdf.signatures/) är fält med värden av signaturobjekt, där de sista innehåller data som används för att verifiera dokumentets giltighet. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | En abstrakt klass som representerar signaturens anpassade utseendeobjekt. |
| [SignatureField](./signaturefield/) | Representerar signaturformulärfält. |
| [SignatureSubjectFormatter](./signaturesubjectformatter/) |  |
| [SymbologyConverter](./symbologyconverter/) |  |
| [TextBoxField](./textboxfield/) | Klass som representerar textrutefält. |
| [XFA](./xfa/) | Representerar XML-formulär avseende XML [Forms](./) Architecture ([XFA](./xfa/)). |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [BoxStyle](./boxstyle/) | Representerar stilar för att rita kryss i kryssruta. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Åtkomstbehörigheterna som beviljas för detta dokument. Giltiga värden är: 1 - Inga ändringar i dokumentet är tillåtna; varje ändring av dokumentet ogiltigförklarar signaturen. 2 - Tillåtna ändringar är ifyllning av formulär, instansiering av sidmallar och signering; andra ändringar ogiltigförklarar signaturen. 3 - Tillåtna ändringar är samma som för 2, samt skapande, borttagning och modifiering av annotationer; andra ändringar ogiltigförklarar signaturen. |
| [FormType](./formtype/) | Enumeration av möjliga typer av Acro [Form](./form/). |
| [IconCaptionPosition](./iconcaptionposition/) | Beskriver ikonens position. |
| [ScalingMode](./scalingmode/) | Typen av skalning som ska användas. |
| [ScalingReason](./scalingreason/) | Omständigheterna under vilka ikonen ska skalas inom annoteringsrektangeln. |
| [SubjectNameElements](./subjectnameelements/) | Enumeration beskriver element i signaturens ämnessträng. |
| [Symbology](./symbology/) | En (Streckkod) [Symbology](./symbology/) definierar de tekniska detaljerna för en viss typ av streckkod: bredden på staplarna, teckenuppsättningen, kodningsmetoden, kontrollsummaspecifikationer osv. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [SignHash](./signhash/) | Delegat för att anpassa signering av dokumenthashen. |
