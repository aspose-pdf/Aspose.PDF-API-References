---
title: EncryptFile
second_title: Referencia de API de Aspose.PDF para .NET
description: Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. Lanza una excepción si el proceso falla.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. Lanza una excepción si el proceso falla.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |

### Valor_devuelto

Cierto para el éxito.

### Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf"; //El TestPath puede reasignarse.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ver también

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Cifra el archivo PDF con contraseña de usuario y contraseña de propietario y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario se reemplazará con una cadena aleatoria si la contraseña del propietario ingresada es nula o está vacía. Hay 6 combinaciones posibles de valores KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) no son válidos y se generará la excepción correspondiente si el kit encuentra esta combinación. Genera una excepción si el proceso falla.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |
| cipher | Algorithm | Algorithm.AES para cifrar utilizando el algoritmo AES o Algorithm.RC4 para el cifrado RC4. |

### Valor_devuelto

Cierto para el éxito.

### Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf"; //El TestPath puede reasignarse.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ver también

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->