---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Lanza una excepción si el proceso falla.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Lanza una excepción si el proceso falla.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para encriptación de 40 bits, KeySize.x128 para encriptación de 128 bits y KeySize.x256 para encriptación de 256 bits. |

### Valor de Retorno

Verdadero para éxito.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ver También

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Encripta el archivo Pdf con userpassword y ownerpassword y establece los privilegios de acceso del documento. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| privilege | DocumentPrivilege | Establecer privilegio. |
| keySize | KeySize | KeySize.x40 para encriptación de 40 bits, KeySize.x128 para encriptación de 128 bits y KeySize.x256 para encriptación de 256 bits. |
| cipher | Algorithm | Algorithm.AES para encriptar usando el algoritmo AES o Algorithm.RC4 para encriptación RC4. |

### Valor de Retorno

Verdadero para éxito.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ver También

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)