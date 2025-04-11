---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Cambia la contraseña de usuario y la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla.
type: docs
weight: 40
url: /es/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## CambiarContraseña(string, string, string) {#changepassword}

Cambia la contraseña de usuario y la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |

### Valor de Retorno

Verdadero en caso de éxito.

## Ejemplos

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Ver También

* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CambiarContraseña(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Cambia la contraseña de usuario y la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |
| privilege | DocumentPrivilege | Restablecer seguridad. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |

### Valor de Retorno

Verdadero en caso de éxito.

## Ejemplos

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CambiarContraseña(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Cambia la contraseña de usuario y la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |
| privilege | DocumentPrivilege | Restablecer seguridad. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |
| cipher | Algorithm | Algorithm.AES para cifrar usando el algoritmo AES o Algorithm.RC4 para cifrado RC4. |

### Valor de Retorno

Verdadero en caso de éxito.

## Ejemplos

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)