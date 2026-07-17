---
title: PdfFileSignature
linktitle: PdfFileSignature
second_title: Aspose.PDF for Java API Reference
description: Represents a class to sign a pdf file with a certificate.
type: docs
weight: 530
url: /java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Represents a class to sign a pdf file with a certificate.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | The constructor of PdfFileSignature class. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | The constructor of PdfFileSignature class. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Binds a Pdf stream for editing. |
| [bindPdf](#bindPdf-java.lang.String-) | Binds a Pdf file for editing. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certify the document with the MDP signature. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter). |
| [close](#close--) | Closes the facade. |
| [containsSignature](#containsSignature--) | Checks if the pdf has a digital signature or not. |
| [containsUsageRights](#containsUsageRights--) | Checks if the pdf has a usage rights or not. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Checks if the signature covers the whole document. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Checks if the signature covers the whole document. |
| [dispose](#dispose--) | Closes the facade. This method is obsolete, use close() instead. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extracts signature's single X.509 certificate as a stream. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extracts signature's single X.509 certificate as a stream. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extracts signature's image. |
| [extractImage](#extractImage-java.lang.String-) | Extracts signature's image. |
| [getAccessPermissions](#getAccessPermissions--) | Returns the access permissions value of certified document by the MDP signature type. |
| [getBlankSignNames](#getBlankSignNames--) | Gets the names of all empty signature fields. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Gets the contact information of a signature. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Gets the contact information of a signature. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Gets the signature's datetime. |
| [getDateTime](#getDateTime-java.lang.String-) | Gets the signature's datetime. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Gets the location of a signature. |
| [getLocation](#getLocation-java.lang.String-) | Gets the location of a signature. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Gets the reason of a signature. |
| [getReason](#getReason-java.lang.String-) | Gets the reason of a signature. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Gets the revision of a signature. |
| [getRevision](#getRevision-java.lang.String-) | Gets the revision of a signature. |
| [getSignatureAppearance](#getSignatureAppearance--) | Gets a graphic appearance for the signature. Property value represents image file name. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Gets a graphic appearance for the signature. Property value represents image stream. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Gets the names of all not empty signatures. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Gets the names of all not empty signatures. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Retrieves information about all signatures algorithm present in the PDF document. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Gets the name of person or organization who signing the pdf document. |
| [getSignerName](#getSignerName-java.lang.String-) | Gets the name of person or organization who signing the pdf document. |
| [getSignNames](#getSignNames--) | <p> Gets the names of all not empty signatures. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Gets the names of all not empty signatures. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Gets the toltal revision. |
| [isCertified](#isCertified--) | Gets the flag determining whether a document is certified or not. |
| [isContainSignature](#isContainSignature--) | Checks if the pdf has a digital signature or not. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Checks if the signature covers the whole document. |
| [isLtvEnabled](#isLtvEnabled--) | Gets the LTV enabled flag. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Remove the signature according to the name of the signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Removes the signature according to the name of the signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Remove the signature according to the name of the signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Removes the signature according to the name of the signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Removes all signatures. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Removes the usage rights entry. |
| [save](#save--) | Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor. |
| [save](#save-java.io.OutputStream-) | Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor. |
| [save](#save-java.lang.String-) | Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Set certificate file and password for signing routine. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Sets a graphic appearance for the signature. Property value represents image file name. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Sets a graphic appearance for the signature. Property value represents image stream. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Make a signature on the pdf document. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature which is placed in already presented signature field. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extracts signature's single X.509 certificate as a stream. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extracts signature's single X.509 certificate. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Checks the validity of a signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Checks the validity of a signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Checks the validity of a signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Checks the validity of a signature. |
| [verifySignature](#verifySignature-java.lang.String-) | Checks the validity of a signature. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Checks the validity of a signature. |
| [verifySigned](#verifySigned-java.lang.String-) | Checks the validity of a signature. The method is deprecated and will be deleted in 25.1 version. Use VerifySignature method instead. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

The constructor of PdfFileSignature class.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
The constructor of PdfFileSignature class.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
The constructor of PdfFileSignature class.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
The constructor of PdfFileSignature class.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
The constructor of PdfFileSignature class.

### bindPdf {#bindPdf-java.io.InputStream-}
Binds a Pdf stream for editing.

### bindPdf {#bindPdf-java.lang.String-}
Binds a Pdf file for editing.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certify the document with the MDP signature.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter).

### close {#close--}
```
public void close()
```

Closes the facade.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Checks if the pdf has a digital signature or not.

**Returns:**
Return a result of bool type.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Checks if the pdf has a usage rights or not.

**Returns:**
Returns a result of bool type.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Checks if the signature covers the whole document.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Checks if the signature covers the whole document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Closes the facade. This method is obsolete, use close() instead.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extracts signature's single X.509 certificate as a stream.

### extractCertificate {#extractCertificate-java.lang.String-}
Extracts signature's single X.509 certificate as a stream.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extracts signature's image.

### extractImage {#extractImage-java.lang.String-}
Extracts signature's image.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Returns the access permissions value of certified document by the MDP signature type.

**Returns:**
PdfException If the document is being certified, then returns access permissions value; otherwise, is thrown. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Gets the names of all empty signature fields.

**Returns:**
Return a arrayList. @deprecated Use GetBlankSignatureNames() instead.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Gets the contact information of a signature.

### getContactInfo {#getContactInfo-java.lang.String-}
Gets the contact information of a signature.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Gets the signature's datetime.

### getDateTime {#getDateTime-java.lang.String-}
Gets the signature's datetime.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Gets the location of a signature.

### getLocation {#getLocation-java.lang.String-}
Gets the location of a signature.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Gets the reason of a signature.

### getReason {#getReason-java.lang.String-}
Gets the reason of a signature.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Gets the revision of a signature.

### getRevision {#getRevision-java.lang.String-}
Gets the revision of a signature.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Gets a graphic appearance for the signature. Property value represents image file name.

**Returns:**
String value

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Gets a graphic appearance for the signature. Property value represents image stream.

**Returns:**
InputStream element

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Gets the names of all not empty signatures. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Return an IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Gets the names of all not empty signatures. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive |  | if true, return only active signatures; otherwise, return all signatures. |

**Returns:**
Return an IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Retrieves information about all signatures algorithm present in the PDF document.

**Returns:**
A list of {@link SignatureAlgorithmInfo} instances containing information about each signature.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Gets the name of person or organization who signing the pdf document.

### getSignerName {#getSignerName-java.lang.String-}
Gets the name of person or organization who signing the pdf document.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Gets the names of all not empty signatures. </p> <hr>

**Returns:**
Return a arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Gets the names of all not empty signatures. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive |  | boolean value, if true, return only active signatures; otherwise, return all signatures. |

**Returns:**
Return a arrayList. @deprecated The method can produce the same signature names, which cannot be distinguished during verification. Use getSignatureNames(boolean onlyActive) instead.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Gets the toltal revision.

**Returns:**
Return the total number of signature revision.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Gets the flag determining whether a document is certified or not.

**Returns:**
boolean value

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Checks if the pdf has a digital signature or not.

**Returns:**
Return a result of bool type.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Checks if the signature covers the whole document.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Gets the LTV enabled flag.

**Returns:**
boolean value

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Remove the signature according to the name of the signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Removes the signature according to the name of the signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Remove the signature according to the name of the signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Removes the signature according to the name of the signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Removes all signatures. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Removes the usage rights entry.

### save {#save--}
```
@Deprecated public void save()
```

Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor.

### save {#save-java.io.OutputStream-}
Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor.

### save {#save-java.lang.String-}
Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Set certificate file and password for signing routine.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Sets a graphic appearance for the signature. Property value represents image file name.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Sets a graphic appearance for the signature. Property value represents image stream.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Sign the document with the given type signature.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Make a signature on the pdf document.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Sign the document with the given type signature.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Sign the document with the given type signature which is placed in already presented signature field.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extracts signature's single X.509 certificate as a stream.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extracts signature's single X.509 certificate.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Checks the validity of a signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Checks the validity of a signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Checks the validity of a signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Checks the validity of a signature.

### verifySignature {#verifySignature-java.lang.String-}
Checks the validity of a signature.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Checks the validity of a signature.

### verifySigned {#verifySigned-java.lang.String-}
Checks the validity of a signature. The method is deprecated and will be deleted in 25.1 version. Use VerifySignature method instead.
