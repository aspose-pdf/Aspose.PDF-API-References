---
title: PdfFileSecurity
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa el cifrado o descifrado de un archivo PDF con propietario o contraseña de usuario cambiando la configuración de seguridad y la contraseña.
type: docs
weight: 2560
url: /es/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Representa el cifrado o descifrado de un archivo PDF con propietario o contraseña de usuario, cambiando la configuración de seguridad y la contraseña.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Inicializar el objeto de PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Inicializa nuevo[`PdfFileSecurity`](../pdffilesecurity) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Devuelve la excepción lanzada por la última operación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Inicializa la fachada. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Cambia la contraseña de usuario y contraseña de propietario por contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la nueva contraseña del propietario es nula o está vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la nueva contraseña del propietario es nula o está vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario se reemplazará con una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Hay 6 combinaciones posibles de valores KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) no son válidos y se generará la excepción correspondiente si el kit encuentra esta combinación. Genera una excepción si el proceso falla. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Cierra la fachada. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Descifra un documento PDF cifrado por contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar contraseña de usuario. Lanza una excepción si el proceso falla. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. Lanza una excepción si el proceso falla. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. Hay 6 combinaciones posibles de valores KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) no son válidos y se generará la excepción correspondiente si el kit encuentra esta combinación. Genera una excepción si el proceso falla. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Guarda el documento PDF en el archivo especificado. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Establece la seguridad del archivo PDF con contraseñas de usuario/propietario vacías. La contraseña del propietario se agregará mediante una cadena aleatoria. Lanza una excepción si el proceso falla. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Establece la seguridad del archivo PDF con la contraseña original. Lanza una excepción si falla el proceso. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Cambia la contraseña de usuario y contraseña de propietario por contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario será reemplazada No arroja una excepción si el proceso falló. con una cadena aleatoria si la nueva contraseña del propietario es nula o está vacía. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario se reemplazará con una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. No arroja una excepción si el proceso falla. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario se reemplazará con una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Hay 6 combinaciones posibles de valores KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) no son válidos y se generará la excepción correspondiente si el kit encuentra esta combinación. No arroja una excepción si el proceso falla. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Descifra un documento PDF cifrado por contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar contraseña de usuario. No lanza una excepción si el proceso falla. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. No genera una excepción si el proceso falla. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Establece la seguridad del archivo PDF con la contraseña original. No lanza una excepción si falla el proceso. |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
