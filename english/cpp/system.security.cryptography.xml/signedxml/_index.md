---
title: System::Security::Cryptography::Xml::SignedXml class
linktitle: SignedXml
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::Xml::SignedXml class. Used for XML signing and verification. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.security.cryptography.xml/signedxml/
---
## SignedXml class


Used for XML signing and verification. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SignedXml : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddObject](./addobject/)(SharedPtr\<DataObject\>) |  |
| [AddReference](./addreference/)(SharedPtr\<Reference\>) |  |
| [CheckSignature](./checksignature/)() |  |
| [CheckSignature](./checksignature/)(SharedPtr\<AsymmetricAlgorithm\>) |  |
| [CheckSignature](./checksignature/)(SharedPtr\<X509Certificates::X509Certificate2\>, bool) |  |
| [CheckSignatureReturningKey](./checksignaturereturningkey/)(SharedPtr\<AsymmetricAlgorithm\>\&) |  |
| [ComputeSignature](./computesignature/)() |  |
| [get_KeyInfo](./get_keyinfo/)() |  |
| [get_SignatureLength](./get_signaturelength/)() |  |
| [get_SignatureMethod](./get_signaturemethod/)() |  |
| [get_SignatureValue](./get_signaturevalue/)() |  |
| [get_SignedInfo](./get_signedinfo/)() |  |
| [get_SigningKey](./get_signingkey/)() |  |
| [get_SigningKeyName](./get_signingkeyname/)() |  |
| virtual [GetIdElement](./getidelement/)(SharedPtr\<System::Xml::XmlDocument\>, String) |  |
| [GetXml](./getxml/)() |  |
| [LoadXml](./loadxml/)(SharedPtr\<System::Xml::XmlElement\>) |  |
| [set_KeyInfo](./set_keyinfo/)(SharedPtr\<KeyInfo\>) |  |
| [set_SigningKey](./set_signingkey/)(SharedPtr\<AsymmetricAlgorithm\>) |  |
| [set_SigningKeyName](./set_signingkeyname/)(String) |  |
| [SignedXml](./signedxml/)() |  |
| [SignedXml](./signedxml/)(SharedPtr\<System::Xml::XmlDocument\>) |  |
| [SignedXml](./signedxml/)(SharedPtr\<System::Xml::XmlElement\>) |  |
## Fields

| Field | Description |
| --- | --- |
| static [XmlDecryptionTransformUrl](./xmldecryptiontransformurl/) |  |
| static [XmlDsigBase64TransformUrl](./xmldsigbase64transformurl/) |  |
| static [XmlDsigC14NTransformUrl](./xmldsigc14ntransformurl/) |  |
| static [XmlDsigC14NWithCommentsTransformUrl](./xmldsigc14nwithcommentstransformurl/) |  |
| static [XmlDsigCanonicalizationUrl](./xmldsigcanonicalizationurl/) |  |
| static [XmlDsigCanonicalizationWithCommentsUrl](./xmldsigcanonicalizationwithcommentsurl/) |  |
| static [XmlDsigDSAUrl](./xmldsigdsaurl/) |  |
| static [XmlDsigEnvelopedSignatureTransformUrl](./xmldsigenvelopedsignaturetransformurl/) |  |
| static [XmlDsigExcC14NTransformUrl](./xmldsigexcc14ntransformurl/) |  |
| static [XmlDsigExcC14NWithCommentsTransformUrl](./xmldsigexcc14nwithcommentstransformurl/) |  |
| static [XmlDsigHMACSHA1Url](./xmldsighmacsha1url/) |  |
| static [XmlDsigMinimalCanonicalizationUrl](./xmldsigminimalcanonicalizationurl/) |  |
| static [XmlDsigNamespaceUrl](./xmldsignamespaceurl/) |  |
| static [XmlDsigRSASHA1Url](./xmldsigrsasha1url/) |  |
| static [XmlDsigRSASHA256Url](./xmldsigrsasha256url/) |  |
| static [XmlDsigRSASHA384Url](./xmldsigrsasha384url/) |  |
| static [XmlDsigRSASHA512Url](./xmldsigrsasha512url/) |  |
| static [XmlDsigSHA1Url](./xmldsigsha1url/) |  |
| static [XmlDsigSHA256Url](./xmldsigsha256url/) |  |
| static [XmlDsigSHA384Url](./xmldsigsha384url/) |  |
| static [XmlDsigSHA512Url](./xmldsigsha512url/) |  |
| static [XmlDsigXPathTransformUrl](./xmldsigxpathtransformurl/) |  |
| static [XmlDsigXsltTransformUrl](./xmldsigxslttransformurl/) |  |
| static [XmlLicenseTransformUrl](./xmllicensetransformurl/) |  |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Xml](../)
* Library [Aspose.PDF for C++](../../)
