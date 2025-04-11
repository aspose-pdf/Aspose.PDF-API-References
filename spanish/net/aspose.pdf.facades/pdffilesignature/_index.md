---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileSignature. Representa una clase para firmar un archivo pdf con un certificado
type: docs
weight: 4560
url: /es/net/aspose.pdf.facades/pdffilesignature/
---
## Clase PdfFileSignature

Representa una clase para firmar un archivo pdf con un certificado.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | El constructor de la clase PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfFileSignature` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en la que se está trabajando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Obtiene la bandera que determina si un documento está certificado o no. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Obtiene la bandera de LTV habilitada. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el nombre del archivo de imagen. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Establece o obtiene una apariencia gráfica para la firma. El valor de la propiedad representa el flujo de imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Vincula un flujo Pdf para editar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Vincula un archivo Pdf para editar. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifica el documento con la firma MDP que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifica el documento con la firma MDP. Datos como el motivo de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Cierra la fachada. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Verifica si el pdf tiene una firma digital o no. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Verifica si el pdf tiene derechos de uso o no. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Verifica si la firma cubre todo el documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desecha la fachada. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extrae el único certificado X.509 de la firma como un flujo. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extrae la imagen de la firma. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Devuelve el valor de los permisos de acceso del documento certificado por el tipo de firma MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Obtiene los nombres de todos los campos de firma vacíos. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Obtiene la información de contacto de una firma. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Obtiene la fecha y hora de la firma. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Obtiene la ubicación de una firma. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Obtiene el motivo de una firma. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Obtiene la revisión de una firma. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Obtiene los nombres de todas las firmas no vacías. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Recupera información sobre todos los algoritmos de firma presentes en el documento PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Obtiene el nombre de la persona u organización que firma el documento pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Obtiene la revisión total. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Elimina la firma según el nombre de la firma. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Elimina la firma según el nombre de la firma. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Elimina todas las firmas. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Elimina la entrada de derechos de uso. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Guarda el PDF resultante en el flujo. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Guarda el PDF resultante en un archivo. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Establece el archivo de certificado y la contraseña para la rutina de firma. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Firma el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). Datos como el motivo de la firma, contacto y ubicación deben ser proporcionados por las propiedades correspondientes del objeto Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Firma el documento con el tipo de firma dado. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Firma el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Realiza una firma en el documento pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Firma el documento con el tipo de firma dado. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Firma el documento con el tipo de firma dado que se coloca en el campo de firma ya presentado. Antes de firmar, el documento pdf ya debe tener un campo de firma, la página y el rectángulo correspondientes se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Verifica la validez de una firma. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Verifica la validez de una firma. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)