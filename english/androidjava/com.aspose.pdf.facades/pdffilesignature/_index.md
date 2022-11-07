---
title: PdfFileSignature
second_title: Aspose.PDF for Java API Reference
description: Represents a class to sign a pdf file with a certificate.
type: docs
weight: 40
url: /java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileSignature extends SaveableFacade
```

Represents a class to sign a pdf file with a certificate.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSignature()](#PdfFileSignature--) | The constructor of PdfFileSignature class. |
| [PdfFileSignature(String inputFile)](#PdfFileSignature-java.lang.String-) | The constructor of PdfFileSignature class. |
| [PdfFileSignature(String inputFile, String outputFile)](#PdfFileSignature-java.lang.String-java.lang.String-) | The constructor of PdfFileSignature class. |
| [PdfFileSignature(IDocument document)](#PdfFileSignature-com.aspose.pdf.IDocument-) | Initializes new  PdfFileSignature  object on base of the  document . |
| [PdfFileSignature(IDocument document, String outputFile)](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  PdfFileSignature  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [getSignatureAppearance()](#getSignatureAppearance--) | Gets a graphic appearance for the signature. |
| [setSignatureAppearance(String value)](#setSignatureAppearance-java.lang.String-) | Sets a graphic appearance for the signature. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Binds a Pdf file for editing. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Binds a Pdf stream for editing. |
| [save(String outputFile)](#save-java.lang.String-) | Saves the result PDF to file. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves the result PDF to stream. |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-) | Make a signature on the pdf document. |
| [sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature. |
| [sign(int page, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature. |
| [sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | Sign the document with the given type signature which is placed in already presented signature field. |
| [sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rect annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-android.graphics.Rect-com.aspose.pdf.Signature-) |  |
| [sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-) | Sign the document with the given type signature which is placed in already presented signature field. |
| [sign(String SigName, Signature sig)](#sign-java.lang.String-com.aspose.pdf.Signature-) | Sign the document with the given type signature which is placed in already presented signature field. |
| [getSignNames()](#getSignNames--) | Gets the names of all not empty signatures. |
| [getBlankSignNames()](#getBlankSignNames--) | Gets the names of all empty signature fields. |
| [isContainSignature()](#isContainSignature--) | Checks if the pdf has a digital signature or not. |
| [isCoversWholeDocument(String signName)](#isCoversWholeDocument-java.lang.String-) | Checks if the signature covers the whole document. |
| [getRevision(String signName)](#getRevision-java.lang.String-) | Gets the revision of a signature. |
| [getTotalRevision()](#getTotalRevision--) | Gets the toltal revision. |
| [removeSignature(String signName)](#removeSignature-java.lang.String-) | Remove the signature according to the name of the signature. |
| [removeSignature(String signName, boolean removeField)](#removeSignature-java.lang.String-boolean-) | Removes the signature according to the name of the signature. |
| [verifySigned(String signName)](#verifySigned-java.lang.String-) | Checks the validity of a signature. |
| [getSignerName(String signName)](#getSignerName-java.lang.String-) | Gets the name of person or organization who signing the pdf document. |
| [getDateTime(String signName)](#getDateTime-java.lang.String-) | Gets the signature's datetime. |
| [getReason(String signName)](#getReason-java.lang.String-) | Gets the reason of a signature. |
| [getLocation(String signName)](#getLocation-java.lang.String-) | Gets the location of a signature. |
| [getContactInfo(String signName)](#getContactInfo-java.lang.String-) | Gets the contact information of a signature. |
| [verifySignature(String signName)](#verifySignature-java.lang.String-) | Checks the validity of a signature. |
| [save()](#save--) | Save signed pdf file. |
| [setCertificate(String pfx, String pass)](#setCertificate-java.lang.String-java.lang.String-) | Set certificate file and password for signing routine. |
| [getSignatureAppearanceStream()](#getSignatureAppearanceStream--) | Gets a graphic appearance for the signature. |
| [setSignatureAppearanceStream(InputStream value)](#setSignatureAppearanceStream-java.io.InputStream-) | Sets a graphic appearance for the signature. |
| [close()](#close--) |  |
| [dispose()](#dispose--) |  |
### PdfFileSignature() {#PdfFileSignature--}
```
public PdfFileSignature()
```


The constructor of PdfFileSignature class.

### PdfFileSignature(String inputFile) {#PdfFileSignature-java.lang.String-}
```
public PdfFileSignature(String inputFile)
```


The constructor of PdfFileSignature class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file for signature. |

### PdfFileSignature(String inputFile, String outputFile) {#PdfFileSignature-java.lang.String-java.lang.String-}
```
public PdfFileSignature(String inputFile, String outputFile)
```


The constructor of PdfFileSignature class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file for signature. |
| outputFile | java.lang.String | The output file. |

### PdfFileSignature(IDocument document) {#PdfFileSignature-com.aspose.pdf.IDocument-}
```
public PdfFileSignature(IDocument document)
```


Initializes new  PdfFileSignature  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### PdfFileSignature(IDocument document, String outputFile) {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSignature(IDocument document, String outputFile)
```


Initializes new  PdfFileSignature  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputFile | java.lang.String | The output file. |

### getSignatureAppearance() {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```


Gets a graphic appearance for the signature. Property value represents image file name.

**Returns:**
java.lang.String
### setSignatureAppearance(String value) {#setSignatureAppearance-java.lang.String-}
```
public void setSignatureAppearance(String value)
```


Sets a graphic appearance for the signature. Property value represents image file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Binds a Pdf file for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The pdf file to be edited. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Binds a Pdf stream for editing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be edited. |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves the result PDF to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | output pdf file |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves the result PDF to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | output pdf stream |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect)
```


Make a signature on the pdf document.

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PdfFileSignature pdfSign = new PdfFileSignature();
>  pdfSign.bindPdf(inFile);
>  Rectangle rect = new Rectangle(100, 100, 200, 200);
>  pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
>  pdfSign.setCertificate("certificate.pfx", "password");
>  pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect);
>  pdfSign.save(outFile);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page on which signature is made. |
| SigReason | java.lang.String | The reason of signature. |
| SigContact | java.lang.String | The contact of signature. |
| SigLocation | java.lang.String | The location of signature. |
| visible | boolean | The visiblity of signature. |
| annotRect | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) | The rect of signature. |

### sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


Sign the document with the given type signature.

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
>  Rectangle rect = new Rectangle(100, 100, 200, 100);
>  pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
>  pdfSign.sign(2, "Allen", "success", "ChangSha", true, rect, new PKCS1("certificate.pfx", "password"));
>  pdfSign.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page on which signature is made. |
| SigReason | java.lang.String | The reason of signature. |
| SigContact | java.lang.String | The contact of signature. |
| SigLocation | java.lang.String | The location of signature. |
| visible | boolean | The visiblity of signature. |
| annotRect | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) | The rect of signature. |
| sig | [Signature](../../com.aspose.pdf/signature) | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

### sign(int page, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, boolean visible, Rectangle annotRect, Signature sig)
```


Sign the document with the given type signature.

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PKCS1 sig = new PKCS1("certificate.pfx", "password");
>  sig.setReason ( "Some reason");
>  sig.setContact ( "Smith");
>  sig.setLocation ( "New York");
>  PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
>  Rectangle rect = new Rectangle(100, 100, 200, 100);
>  pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
>  pdfSign.sign(2, true, rect, sig);
>  pdfSign.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page on which signature is made. |
| visible | boolean | The visiblity of signature. |
| annotRect | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) | The rect of signature. |
| sig | [Signature](../../com.aspose.pdf/signature) | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. Such data as signature reason, contact and location must be already present in this object (see corresponding properties). |

### sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig) {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, String SigReason, String SigContact, String SigLocation, Signature sig)
```


Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter).

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PKCS1 sig = new PKCS1("certificate.pfx", "password");
>  PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
>  pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
>  pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig);
>  pdfSign.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SigName | java.lang.String | The name of the signature field. |
| SigReason | java.lang.String | The reason of signature. |
| SigContact | java.lang.String | The contact of signature. |
| SigLocation | java.lang.String | The location of signature. |
| sig | [Signature](../../com.aspose.pdf/signature) | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

### sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rect annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-android.graphics.Rect-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rect annotRect, Signature sig)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int |  |
| SigName | java.lang.String |  |
| SigReason | java.lang.String |  |
| SigContact | java.lang.String |  |
| SigLocation | java.lang.String |  |
| visible | boolean |  |
| annotRect | android.graphics.Rect |  |
| sig | [Signature](../../com.aspose.pdf/signature) |  |

### sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig) {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-com.aspose.pdf.java.awt.Rectangle-com.aspose.pdf.Signature-}
```
public void sign(int page, String SigName, String SigReason, String SigContact, String SigLocation, boolean visible, Rectangle annotRect, Signature sig)
```


Sign the document with the given type signature which is placed in already presented signature field. Before signing pdf document should already has signature field, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter).

--------------------

> ```
> String inFile = TestPath + "blankWithSignature.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PKCS7 sig = new PKCS7("certificate.pfx", "password");
>  PdfFileSignature pdfSign = new PdfFileSignature(inFile);
>  Rectangle rect = new Rectangle(100, 100, 100, 100);
>  pdfSign.setSignatureAppearance( TestPath + "butterfly.jpg");
>  pdfSign.sign(1, "Signature1", "ReasonToTest", "ContactMe", "SomeLocation", true, rect, sig);
>  pdfSign.save(outFile);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | The page on which signature is made. |
| SigName | java.lang.String | The name of the signature field. |
| SigReason | java.lang.String | The reason of signature. |
| SigContact | java.lang.String | The contact of signature. |
| SigLocation | java.lang.String | The location of signature. |
| visible | boolean | The visiblity of signature. |
| annotRect | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) | The rect of signature. |
| sig | [Signature](../../com.aspose.pdf/signature) | The type of the signature, could be PKCS1, PKCS7 and PKCS7Detached. |

### sign(String SigName, Signature sig) {#sign-java.lang.String-com.aspose.pdf.Signature-}
```
public void sign(String SigName, Signature sig)
```


Sign the document with the given type signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see SigName parameter). Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  String outFile = TestPath + "signature.pdf";
>  PKCS1 sig = new PKCS1("certificate.pfx", "password");
>  sig.setReason ( "Some reason");
>  sig.setContact ( "Smith");
>  sig.setLocation ( "New York");
>  PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile);
>  pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg");
>  pdfSign.sign("Signature1", sig);
>  pdfSign.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| SigName | java.lang.String | The name of the signature field. |
| sig | [Signature](../../com.aspose.pdf/signature) | The type of the signature, could be PKCS1 (Pkcs1Signature object), PKCS7 and PKCS7 detached (Pkcs7Signature object) |

### getSignNames() {#getSignNames--}
```
public List getSignNames()
```


Gets the names of all not empty signatures.

--------------------

> ```
> String inFile=TestPath + "example1.pdf";
>   PdfFileSignature pdfSign=new PdfFileSignature();
>   pdfSign.bindPdf(inFile); 
>   ArrayList names=pdfSign.getSignNames();
>  for(int i=0;i<names.Count;i++)
>  {
>    System.out.println("signature name:"+(String)names[i]);
>    System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i]));
>    System.out.println("revision:"+pdfSign.GetRevision((String)names[i]));	
>    System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i]));
>    System.out.println("reason:"+pdfSign.GetReason((String)names[i]));
>    System.out.println("location:"+pdfSign.GetLocation((String)names[i]));
>    System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i]));		
>   }
>   System.out.println("totalvision:"+pdfSign.GetTotalRevision());
> ```

**Returns:**
java.util.List - Return a arrayList.
### getBlankSignNames() {#getBlankSignNames--}
```
public System.Collections.IList getBlankSignNames()
```


Gets the names of all empty signature fields.

**Returns:**
com.aspose.ms.System.Collections.IList - Return a arrayList.
### isContainSignature() {#isContainSignature--}
```
public boolean isContainSignature()
```


Checks if the pdf has a digital signature or not.

**Returns:**
boolean - Return a result of bool type.
### isCoversWholeDocument(String signName) {#isCoversWholeDocument-java.lang.String-}
```
public boolean isCoversWholeDocument(String signName)
```


Checks if the signature covers the whole document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
boolean - Return a result of bool type.
### getRevision(String signName) {#getRevision-java.lang.String-}
```
public int getRevision(String signName)
```


Gets the revision of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
int - Return the number of signature revision.
### getTotalRevision() {#getTotalRevision--}
```
public int getTotalRevision()
```


Gets the toltal revision.

**Returns:**
int - Return the total number of signature revision.
### removeSignature(String signName) {#removeSignature-java.lang.String-}
```
public void removeSignature(String signName)
```


Remove the signature according to the name of the signature.

--------------------

> ```
> String inFile = TestPath + "example1.pdf";
>  PdfFileSignature pdfSign = new PdfFileSignature();
>  pdfSign.bindPdf(inFile); 
>  List names = pdfSign.getSignNames();
>  for(int i = 0; i < names.size(); i++)
>  {
>     pdfSign.removeSignature((String)names.get(i));
>  }
>  pdfSign.save(TestPath + "signed_removed.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

### removeSignature(String signName, boolean removeField) {#removeSignature-java.lang.String-boolean-}
```
public void removeSignature(String signName, boolean removeField)
```


Removes the signature according to the name of the signature.

--------------------

> ```
> [C#]
>  string inFile = TestPath + "example1.pdf";
>  PdfFileSignature pdfSign = new PdfFileSignature();
>  pdfSign.BindPdf(inFile); 
>  IList names = pdfSign.GetSignNames();
>  for(int i = 0; i < names.Count; i++)
>  {
>     pdfSign.RemoveSignature((string)names[i], false);
>  }
>  pdfSign.Save(TestPath + "signed_removed.pdf");
>  [Visual Basic]
>  Dim pdfSign as PdfFileSignature = new PdfFileSignature
>  pdfSign.BindPdf(inFile)
>  Dim names as IList
>  names = pdfSign.GetSignNames()
>  For i = 0 To names.Count
>   pdfSign.RemoveSignature((string)names[i], false)
>  Next i
>  pdfSign.Save(TestPath + "signed_removed.pdf")
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |
| removeField | boolean | If set to true, than removes both of signature and field from document; otherwise, signature only. |

### verifySigned(String signName) {#verifySigned-java.lang.String-}
```
public boolean verifySigned(String signName)
```


Checks the validity of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
boolean - Return a result of bool type.
### getSignerName(String signName) {#getSignerName-java.lang.String-}
```
public String getSignerName(String signName)
```


Gets the name of person or organization who signing the pdf document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
java.lang.String - Returns the result of the signer's name.
### getDateTime(String signName) {#getDateTime-java.lang.String-}
```
public System.DateTime getDateTime(String signName)
```


Gets the signature's datetime.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
com.aspose.ms.System.DateTime - Return the result of DateTime type.
### getReason(String signName) {#getReason-java.lang.String-}
```
public String getReason(String signName)
```


Gets the reason of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
java.lang.String - Returns a result of String type.
### getLocation(String signName) {#getLocation-java.lang.String-}
```
public String getLocation(String signName)
```


Gets the location of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
java.lang.String - Returns a result of String type.
### getContactInfo(String signName) {#getContactInfo-java.lang.String-}
```
public String getContactInfo(String signName)
```


Gets the contact information of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
java.lang.String - Returns a result of String type.
### verifySignature(String signName) {#verifySignature-java.lang.String-}
```
public boolean verifySignature(String signName)
```


Checks the validity of a signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signName | java.lang.String | The name of signature. |

**Returns:**
boolean - Return a result of bool type.
### save() {#save--}
```
public void save()
```


Save signed pdf file. Output filename must be provided before with the help of coresponding PdfFileSignature constructor.

### setCertificate(String pfx, String pass) {#setCertificate-java.lang.String-java.lang.String-}
```
public void setCertificate(String pfx, String pass)
```


Set certificate file and password for signing routine.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.lang.String | PKCS \#12 certificate file. |
| pass | java.lang.String | Password to get access for the certificate private key. |

### getSignatureAppearanceStream() {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```


Gets a graphic appearance for the signature. Property value represents image stream.

**Returns:**
java.io.InputStream
### setSignatureAppearanceStream(InputStream value) {#setSignatureAppearanceStream-java.io.InputStream-}
```
public void setSignatureAppearanceStream(InputStream value)
```


Sets a graphic appearance for the signature. Property value represents image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### close() {#close--}
```
public void close()
```


Disposes Document bound with a facade.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

