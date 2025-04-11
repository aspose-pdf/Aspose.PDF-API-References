---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileSecurity. Representa la encriptación o desencriptación de un archivo Pdf con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña.
type: docs
weight: 4550
url: /es/net/aspose.pdf.facades/pdffilesecurity/
---
## Clase PdfFileSecurity

Representa la encriptación o desencriptación de un archivo Pdf con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfFileSecurity` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Devuelve la excepción que fue lanzada por la última operación. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Inicializa la fachada. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Cambia la contraseña de usuario y la contraseña de propietario por la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la contraseña de usuario y la contraseña por la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la contraseña de usuario y la contraseña por la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Cierra la fachada. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Desencripta un documento Pdf encriptado por la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. Lanza una excepción si el proceso falla. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Encripta el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Lanza una excepción si el proceso falla. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Encripta el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Guarda el documento PDF en el archivo especificado. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña de propietario será añadida por una cadena aleatoria. Lanza una excepción si el proceso falla. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Establece la seguridad del archivo Pdf con la contraseña original. Lanza una excepción si el proceso falla. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Cambia la contraseña de usuario y la contraseña de propietario por la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Cambia la contraseña de usuario y la contraseña por la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Cambia la contraseña de usuario y la contraseña por la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción si el kit encuentra esta combinación. No lanza una excepción si el proceso falla. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Desencripta un documento Pdf encriptado por la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Encripta el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)