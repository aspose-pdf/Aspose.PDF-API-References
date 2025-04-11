---
title: Aspose.Pdf.Forms
second_title: Aspose.PDF for .NET API Reference
description: Der Aspose.Pdf.Forms-Namespace enthält Klassen, die Formulare (standard, statisch, dynamisch) und verschiedene Arten von Feldern wie Textfeld, Listenfeld, Optionsfeld usw. beschreiben.
type: docs
weight: 110
url: /de/net/aspose.pdf.forms/
---
Der **Aspose.Pdf.Forms**-Namespace enthält Klassen, die Formulare (standard, statisch, dynamisch) und verschiedene Arten von Feldern wie Textfeld, Listenfeld, Optionsfeld usw. beschreiben.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BarcodeField](./barcodefield/) | Klasse repräsentiert Barcode-Feld. |
| [ButtonField](./buttonfield/) | Klasse repräsentiert Druckknopf-Feld. |
| [CheckboxField](./checkboxfield/) | Klasse, die das Kontrollkästchenfeld darstellt. |
| [ChoiceField](./choicefield/) | Repräsentiert die Basisklasse für Auswahlfelder. |
| [ComboBoxField](./comboboxfield/) | Klasse, die das Kombinationsfeld des Formulars darstellt. |
| [DateField](./datefield/) | Datumsfeld mit Kalenderansicht. |
| [DocMDPSignature](./docmdpsignature/) | Repräsentiert die Klasse des Dokumenten-MDP (Modifikationserkennung und -verhinderung) Signaturtyps. |
| [ExternalSignature](./externalsignature/) | Erstellt eine abgetrennte PKCS#7-Signatur mit einem X509Certificate2. Es unterstützt USB-Smartcards, Tokens ohne exportierbare private Schlüssel. |
| [Field](./field/) | Basisklasse für Acro-Formulare. |
| [FileSelectBoxField](./fileselectboxfield/) | Feld für das Element der Dateiauswahlbox. |
| [Form](./form/) | Klasse, die das Formularobjekt darstellt. |
| [IconFit](./iconfit/) | Beschreibt, wie das Symbol der Widget-Anmerkung innerhalb seines Anmerkungsrechtecks angezeigt werden soll. |
| [ListBoxField](./listboxfield/) | Klasse repräsentiert Listenfeld. |
| [NumberField](./numberfield/) | Textfeld mit angegebenen gültigen Zeichen. |
| [Option](./option/) | Klasse repräsentiert die Option des Auswahlfeldes. |
| [OptionCollection](./optioncollection/) | Klasse, die die Sammlung von Optionen des Auswahlfeldes darstellt. |
| [PasswordBoxField](./passwordboxfield/) | Klasse beschreibt Textfeld zum Eingeben des Passworts. |
| [PKCS1](./pkcs1/) | Repräsentiert das Signaturobjekt gemäß dem PKCS#1-Standard. RSA-Verschlüsselungsalgorithmus und SHA-1-Hashmethode werden zum Signieren verwendet. |
| [PKCS7](./pkcs7/) | Repräsentiert das PKCS#7-Objekt, das der PKCS#7-Spezifikation in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5, entspricht. Der `SHA1-Hash` des Bytebereichs des Dokuments ist im PKCS#7 SignedData-Feld verkapselt. |
| [PKCS7Detached](./pkcs7detached/) | Repräsentiert das PKCS#7-Objekt, das der PKCS#7-Spezifikation in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5, entspricht. Der ursprüngliche signierte Nachrichten-Hash über den Bytebereich des Dokuments ist als normales PKCS#7 SignedData-Feld enthalten. Es dürfen keine Daten im PKCS#7 SignedData-Feld verkapselt sein. |
| [RadioButtonField](./radiobuttonfield/) | Klasse, die das Optionsfeld darstellt. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Klasse repräsentiert ein Element des Optionsfeldes. |
| [RichTextBoxField](./richtextboxfield/) | Klasse beschreibt die Komponente des Rich-Text-Editors. |
| [Signature](./signature/) | Eine abstrakte Klasse, die das Signaturobjekt im PDF-Dokument darstellt. Signaturen sind Felder mit Werten von Signaturobjekten, die letzte enthält Daten, die zur Überprüfung der Gültigkeit des Dokuments verwendet werden. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Eine abstrakte Klasse, die das benutzerdefinierte Erscheinungsbild des Signaturobjekts darstellt. |
| [SignatureField](./signaturefield/) | Repräsentiert das Signaturformularfeld. |
| [SignHash](./signhash/) | Delegat für das benutzerdefinierte Signieren des Dokumenten-Hashes. |
| [TextBoxField](./textboxfield/) | Klasse, die das Textfeld darstellt. |
| [XFA](./xfa/) | Repräsentiert das XML-Formular gemäß der XML Forms Architecture (XFA). |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [BoxStyle](./boxstyle/) | Repräsentiert Stile zum Zeichnen des Häkchens im Kontrollkästchen. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Die Zugriffsberechtigungen, die für dieses Dokument gewährt werden. Gültige Werte sind: 1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig. 2 - Erlaubte Änderungen sind das Ausfüllen von Formularen, das Instanziieren von Seitenvorlagen und das Signieren; andere Änderungen machen die Signatur ungültig. 3 - Erlaubte Änderungen sind die gleichen wie für 2, sowie die Erstellung, Löschung und Modifikation von Anmerkungen; andere Änderungen machen die Signatur ungültig. |
| [FormType](./formtype/) | Aufzählung der möglichen Typen von Acro-Formularen. |
| [IconCaptionPosition](./iconcaptionposition/) | Beschreibt die Position des Symbols. |
| [ScalingMode](./scalingmode/) | Der Typ der Skalierung, der verwendet werden soll. |
| [ScalingReason](./scalingreason/) | Die Umstände, unter denen das Symbol innerhalb des Anmerkungsrechtecks skaliert werden soll. |
| [SubjectNameElements](./subjectnameelements/) | Aufzählung beschreibt Elemente im Signaturbetreff-String. |
| [Symbology](./symbology/) | Eine (Barcode) Symbologie definiert die technischen Details eines bestimmten Typs von Barcode: die Breite der Balken, Zeichensatz, Kodierungsmethode, Prüfziffernspezifikationen usw. |