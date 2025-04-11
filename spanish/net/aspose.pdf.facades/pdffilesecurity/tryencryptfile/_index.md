---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla.
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Método PdfFileSecurity.TryEncryptFile

Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para encriptación de 40 bits, KeySize.x128 para encriptación de 128 bits y KeySize.x256 para encriptación de 256 bits. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* clase [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)