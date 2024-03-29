---
title: TryEncryptFile
second_title: Referencia de API de Aspose.PDF para .NET
description: Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. No genera una excepción si el proceso falla.
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. No genera una excepción si el proceso falla.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf"; //El TestPath puede reasignarse.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ver también

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
