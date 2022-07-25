---
title: PdfFileSignature
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para firmar un archivo pdf con un certificado.
type: docs
weight: 2570
url: /es/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Representa una clase para firmar un archivo pdf con un certificado.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Inicializa nuevo[`PdfFileSignature`](../pdffilesignature) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Obtiene el indicador que determina si un documento está certificado o no. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Obtiene el indicador de LTV habilitado. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Establece u obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Establece u obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imágenes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Vincula una secuencia de PDF para editar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Vincula un archivo PDF para editarlo. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Certifique el documento con la firma MDP que se encuentra en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para selle la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por nombre de firma (consulte el parámetro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certificar el documento con la firma MDP. Tales datos como motivo de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Firma sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Cierra la fachada. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Comprueba si el pdf tiene firma digital o no. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Comprueba si el pdf tiene derechos de uso o no. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Comprueba si la firma cubre todo el documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Extrae el certificado único X.509 de la firma como un flujo. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Extrae la imagen de la firma. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Devuelve el valor de los permisos de acceso del documento certificado por el tipo de firma MDP. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Obtiene los nombres de todos los campos de firma vacíos. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Obtiene la información de contacto de una firma. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Obtiene la fecha y hora de la firma. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Obtiene la ubicación de una firma. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Obtiene el motivo de una firma. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Obtiene la revisión de una firma. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Obtiene el nombre de la persona u organización que firma el documento pdf. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Obtiene los nombres de todas las firmas no vacías. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Obtiene la revisión total. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Eliminar la firma según el nombre de la firma. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Elimina la firma según el nombre de la firma. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Elimina la entrada de derechos de uso. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Guarda el PDF resultante en flujo. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Guarda el PDF resultante en un archivo. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Establecer archivo de certificado y contraseña para la rutina de firma. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener el diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para sellar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Firma el documento con el tipo de firma dado. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener el diccionario de firma. Por lo tanto, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, se toman la página y el rectángulo correspondientes del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Hacer una firma en el documento pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Firma el documento con el tipo de firma dado. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Firme el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el documento pdf ya debe tener un campo de firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por nombre de firma (consulte el parámetro SigName) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Comprueba la validez de una firma. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Comprueba la validez de una firma. |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
