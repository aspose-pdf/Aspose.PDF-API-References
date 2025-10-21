---
title: Aspose::Pdf::Forms namespace
linktitle: Aspose::Pdf::Forms
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms namespace. The Aspose.Pdf.Forms namespace has classes which describes forms (standard, static, dynamic) and various types of fields like text box, list box, radio button etc in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.forms/
---

The **[Aspose.Pdf.Forms](./)** namespace has classes which describes forms (standard, static, dynamic) and various types of fields like text box, list box, radio button etc.

## Classes

| Class | Description |
| --- | --- |
| [BarcodeField](./barcodefield/) | Class represents barcode field. |
| [ButtonField](./buttonfield/) | Class represnets push button field. |
| [CheckboxField](./checkboxfield/) | Class representing checkbox field. |
| [ChoiceField](./choicefield/) | Represents base class for choice fields. |
| [ComboBoxField](./comboboxfield/) | Class representing Combobox field of the form. |
| [DateField](./datefield/) | Date field with calendar view. |
| [DocMDPSignature](./docmdpsignature/) | Represents the class of document MDP (modification detection and prevention) signature type. |
| [ExternalSignature](./externalsignature/) | Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [Field](./field/) | Base class for acro form fields. |
| [FileSelectBoxField](./fileselectboxfield/) | [Field](./field/) for file select box element. |
| [Form](./form/) | Class representing form object. |
| [IconFit](./iconfit/) | Describes how the widget annotation's icon shall be displayed within its annotation rectangle. |
| [ListBoxField](./listboxfield/) | Class represents ListBox field. |
| [NumberField](./numberfield/) | [Text](../aspose.pdf.text/)[Field](./field/) with specified valid chars. |
| [Option](./option/) | Class represents option of choice field. |
| [OptionCollection](./optioncollection/) | Class representing collection of options of the choice field. |
| [PasswordBoxField](./passwordboxfield/) | Class descibes text field for entering password. |
| [PKCS1](./pkcs1/) | Represents signature object regarding PKCS#1 standard. RSA encryption algorithm and SHA-1 digest method are used for signing. |
| [PKCS7](./pkcs7/) | Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. The **SHA1 digest** of the document's byte range is encapsulated in the PKCS#7 SignedData field. |
| [PKCS7Detached](./pkcs7detached/) | Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. The original signed message digest over the document's byte range is incorporated as the normal PKCS#7 SignedData field. No data shall is encapsulated in the PKCS#7 SignedData field. |
| [RadioButtonField](./radiobuttonfield/) | Class representing radio button field. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Class represents item of RadioButton field. |
| [RichTextBoxField](./richtextboxfield/) | Class describes rich text editor component. |
| [Signature](./signature/) | An abstract class which represents signature object in the pdf document. [Signatures](../aspose.pdf.signatures/) are fields with values of signature objects, the last contain data which is used to verify the document validity. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | An abstract class which represents signature custon appearance object. |
| [SignatureField](./signaturefield/) | Represents signature form field. |
| [SignatureSubjectFormatter](./signaturesubjectformatter/) |  |
| [SymbologyConverter](./symbologyconverter/) |  |
| [TextBoxField](./textboxfield/) | Class representing text box field. |
| [XFA](./xfa/) | Represents XML form regarding XML [Forms](./) Architecture ([XFA](./xfa/)). |
## Enums

| Enum | Description |
| --- | --- |
| [BoxStyle](./boxstyle/) | Represents styles for drawing check in check box. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | The access permissions granted for this document. Valid values are: 1 - No changes to the document are permitted; any change to the document invalidates the signature. 2 - Permitted changes are filling in forms, instantiating page templates, and signing; other changes invalidate the signature. 3 - Permitted changes are the same as for 2, as well as annotation creation, deletion, and modification; other changes invalidate the signature. |
| [FormType](./formtype/) | Enumeration of posible types of Acro [Form](./form/). |
| [IconCaptionPosition](./iconcaptionposition/) | Describes position of icon. |
| [ScalingMode](./scalingmode/) | The type of scaling that shall be used. |
| [ScalingReason](./scalingreason/) | The circumstances under which the icon shall be scaled inside the annotation rectangle. |
| [SubjectNameElements](./subjectnameelements/) | Enumeration describes elements in signature subject string. |
| [Symbology](./symbology/) | A (Barcode) [Symbology](./symbology/) defines the technical details of a particular type of barcode: the width of the bars, character set, method of encoding, checksum specifications, etc. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SignHash](./signhash/) | Delegate for custom sign the document hash. |
