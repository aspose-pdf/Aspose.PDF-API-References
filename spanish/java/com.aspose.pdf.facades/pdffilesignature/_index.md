---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para firmar un archivo PDF con un certificado."
type: docs
weight: 530
url: /es/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Representa una clase para firmar un archivo PDF con un certificado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | El constructor de la clase PdfFileSignature. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Vincula un flujo Pdf para editar. |
| [bindPdf](#bindPdf-java.lang.String-) | Vincula un archivo Pdf para editar. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certifica el documento con la firma MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certifica el documento con la firma MDP que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página correspondiente y el rectángulo se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro sigName). |
| [close](#close--) | Cierra la fachada. |
| [containsSignature](#containsSignature--) | Comprueba si el pdf tiene una firma digital o no. |
| [containsUsageRights](#containsUsageRights--) | Comprueba si el pdf tiene derechos de uso o no. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Comprueba si la firma cubre todo el documento. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Comprueba si la firma cubre todo el documento. |
| [dispose](#dispose--) | Cierra la fachada. Este método está obsoleto, use close() en su lugar. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extrae el único certificado X.509 de la firma como un flujo. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extrae el único certificado X.509 de la firma como un flujo. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extrae la imagen de la firma. |
| [extractImage](#extractImage-java.lang.String-) | Extrae la imagen de la firma. |
| [getAccessPermissions](#getAccessPermissions--) | Devuelve el valor de los permisos de acceso del documento certificado por el tipo de firma MDP. |
| [getBlankSignNames](#getBlankSignNames--) | Obtiene los nombres de todos los campos de firma vacíos. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Obtiene la información de contacto de una firma. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Obtiene la información de contacto de una firma. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Obtiene la fecha y hora de la firma. |
| [getDateTime](#getDateTime-java.lang.String-) | Obtiene la fecha y hora de la firma. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Obtiene la ubicación de una firma. |
| [getLocation](#getLocation-java.lang.String-) | Obtiene la ubicación de una firma. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Obtiene la razón de una firma. |
| [getReason](#getReason-java.lang.String-) | Obtiene la razón de una firma. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Obtiene la revisión de una firma. |
| [getRevision](#getRevision-java.lang.String-) | Obtiene la revisión de una firma. |
| [getSignatureAppearance](#getSignatureAppearance--) | Obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Obtiene los nombres de todas las firmas no vacías. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Obtiene los nombres de todas las firmas no vacías. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Recupera información sobre todos los algoritmos de firmas presentes en el documento PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Obtiene el nombre de la persona u organización que firma el documento PDF. |
| [getSignerName](#getSignerName-java.lang.String-) | Obtiene el nombre de la persona u organización que firma el documento PDF. |
| [getSignNames](#getSignNames--) | <p> Obtiene los nombres de todas las firmas no vacías. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Obtiene los nombres de todas las firmas no vacías. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Obtiene la revisión total. |
| [isCertified](#isCertified--) | Obtiene la bandera que determina si un documento está certificado o no. |
| [isContainSignature](#isContainSignature--) | Comprueba si el pdf tiene una firma digital o no. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Comprueba si la firma cubre todo el documento. |
| [isLtvEnabled](#isLtvEnabled--) | Obtiene la bandera de LTV habilitada. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Elimina la firma según el nombre de la firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Elimina la firma según el nombre de la firma. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Eliminar la firma según el nombre de la firma. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Elimina la firma según el nombre de la firma. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre> |
| [removeSignatures](#removeSignatures--) | Elimina todas las firmas. string inFile = TestPath + \"example1.pdf\"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeUsageRights](#removeUsageRights--) | Elimina la entrada de derechos de uso. |
| [save](#save--) | Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature. |
| [save](#save-java.io.OutputStream-) | Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature. |
| [save](#save-java.lang.String-) | Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Establece el archivo de certificado y la contraseña para la rutina de firma. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Establece una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Establece una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma el documento con la firma del tipo especificado. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Crea una firma en el documento PDF. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma el documento con la firma del tipo especificado. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, contacto y ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); sig.setReason ( \"Some reason\"); sig.setContact ( \"Smith\"); sig.setLocation ( \"New York\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", \"Allen\", \"success\", \"ChangSha\", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extrae el único certificado X.509 de la firma como un flujo. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extrae el único certificado X.509 de la firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Comprueba la validez de una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Comprueba la validez de una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Comprueba la validez de una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Comprueba la validez de una firma. |
| [verifySignature](#verifySignature-java.lang.String-) | Comprueba la validez de una firma. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Comprueba la validez de una firma. |
| [verifySigned](#verifySigned-java.lang.String-) | Comprueba la validez de una firma. El método está obsoleto y será eliminado en la versión 25.1. Use el método VerifySignature en su lugar. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

El constructor de la clase PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
El constructor de la clase PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
El constructor de la clase PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
El constructor de la clase PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
El constructor de la clase PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Vincula un flujo Pdf para editar.

### bindPdf {#bindPdf-java.lang.String-}
Vincula un archivo Pdf para editar.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certifica el documento con la firma MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certifica el documento con la firma MDP que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página correspondiente y el rectángulo se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro sigName).

### close {#close--}
```
public void close()
```

Cierra la fachada.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Comprueba si el pdf tiene una firma digital o no.

**Returns:**
Devuelve un resultado de tipo bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Comprueba si el pdf tiene derechos de uso o no.

**Returns:**
Devuelve un resultado de tipo bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Comprueba si la firma cubre todo el documento.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Comprueba si la firma cubre todo el documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Cierra la fachada. Este método está obsoleto, use close() en su lugar.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extrae el único certificado X.509 de la firma como un flujo.

### extractCertificate {#extractCertificate-java.lang.String-}
Extrae el único certificado X.509 de la firma como un flujo.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extrae la imagen de la firma.

### extractImage {#extractImage-java.lang.String-}
Extrae la imagen de la firma.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Devuelve el valor de los permisos de acceso del documento certificado por el tipo de firma MDP.

**Returns:**
PdfException Si el documento está siendo certificado, entonces devuelve el valor de permisos de acceso; de lo contrario, se lanza. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Obtiene los nombres de todos los campos de firma vacíos.

**Returns:**
Devuelve una arrayList. @deprecated Use GetBlankSignatureNames() en su lugar.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Obtiene la información de contacto de una firma.

### getContactInfo {#getContactInfo-java.lang.String-}
Obtiene la información de contacto de una firma.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Obtiene la fecha y hora de la firma.

### getDateTime {#getDateTime-java.lang.String-}
Obtiene la fecha y hora de la firma.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Obtiene la ubicación de una firma.

### getLocation {#getLocation-java.lang.String-}
Obtiene la ubicación de una firma.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Obtiene la razón de una firma.

### getReason {#getReason-java.lang.String-}
Obtiene la razón de una firma.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Obtiene la revisión de una firma.

### getRevision {#getRevision-java.lang.String-}
Obtiene la revisión de una firma.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen.

**Returns:**
valor String

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen.

**Returns:**
Elemento InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Obtiene los nombres de todas las firmas no vacías. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Devuelve un IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Obtiene los nombres de todas las firmas no vacías. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onlyActive |  | si es true, devuelve solo firmas activas; de lo contrario, devuelve todas las firmas. |

**Returns:**
Devuelve un IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Recupera información sobre todos los algoritmos de firmas presentes en el documento PDF.

**Returns:**
Una lista de instancias {@link SignatureAlgorithmInfo} que contiene información sobre cada firma.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Obtiene el nombre de la persona u organización que firma el documento PDF.

### getSignerName {#getSignerName-java.lang.String-}
Obtiene el nombre de la persona u organización que firma el documento PDF.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Obtiene los nombres de todas las firmas no vacías. </p> <hr>

**Returns:**
Devuelve una arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Obtiene los nombres de todas las firmas no vacías. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| onlyActive |  | valor booleano, si es true, devuelve solo firmas activas; de lo contrario, devuelve todas las firmas. |

**Returns:**
Devuelve una arrayList. @deprecated El método puede producir los mismos nombres de firma, los cuales no pueden distinguirse durante la verificación. Use getSignatureNames(boolean onlyActive) en su lugar.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Obtiene la revisión total.

**Returns:**
Devuelve el número total de revisiones de firma.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Obtiene la bandera que determina si un documento está certificado o no.

**Returns:**
valor booleano

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Comprueba si el pdf tiene una firma digital o no.

**Returns:**
Devuelve un resultado de tipo bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Comprueba si la firma cubre todo el documento.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Obtiene la bandera de LTV habilitada.

**Returns:**
valor booleano

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Elimina la firma según el nombre de la firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Elimina la firma según el nombre de la firma. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeSignature {#removeSignature-java.lang.String-}
<p> Eliminar la firma según el nombre de la firma. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Elimina la firma según el nombre de la firma. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Elimina todas las firmas. string inFile = TestPath + \"example1.pdf\"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Elimina la entrada de derechos de uso.

### save {#save--}
```
@Deprecated public void save()
```

Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature.

### save {#save-java.io.OutputStream-}
Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature.

### save {#save-java.lang.String-}
Guarda el archivo PDF firmado. El nombre del archivo de salida debe proporcionarse previamente con la ayuda del constructor correspondiente de PdfFileSignature.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Establece el archivo de certificado y la contraseña para la rutina de firma.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Establece una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Establece una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma el documento con la firma del tipo especificado.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Crea una firma en el documento PDF.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma el documento con la firma del tipo especificado.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, contacto y ubicación deben proporcionarse mediante las propiedades correspondientes del objeto Signature sig. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); sig.setReason ( \"Some reason\"); sig.setContact ( \"Smith\"); sig.setLocation ( \"New York\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Firma el documento con la firma del tipo especificado que se coloca en un campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Por lo tanto, el documento PDF ya tiene un campo de firma; no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", \"Allen\", \"success\", \"ChangSha\", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extrae el único certificado X.509 de la firma como un flujo.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extrae el único certificado X.509 de la firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Comprueba la validez de una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Comprueba la validez de una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Comprueba la validez de una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Comprueba la validez de una firma.

### verifySignature {#verifySignature-java.lang.String-}
Comprueba la validez de una firma.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Comprueba la validez de una firma.

### verifySigned {#verifySigned-java.lang.String-}
Comprueba la validez de una firma. El método está obsoleto y será eliminado en la versión 25.1. Use el método VerifySignature en su lugar.
