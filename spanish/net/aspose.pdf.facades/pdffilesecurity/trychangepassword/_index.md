---
title: TryChangePassword
second_title: Referencia de API de Aspose.PDF para .NET
description: Cambia la contraseña de usuario y contraseña de propietario por contraseña de propietario mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario será reemplazada No arroja una excepción si el proceso falló. con una cadena aleatoria si la nueva contraseña del propietario es nula o está vacía.
type: docs
weight: 90
url: /es/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Cambia la contraseña de usuario y contraseña de propietario por contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña del propietario será reemplazada No arroja una excepción si el proceso falló. con una cadena aleatoria si la nueva contraseña del propietario es nula o está vacía.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
 string outFile = "D:\\output.pdf";	//El TestPath puede reasignarse.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Ver también

* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario se reemplazará con una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. No arroja una excepción si el proceso falla.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |
| privilege | DocumentPrivilege | Restablecer seguridad. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf";	//El TestPath puede reasignarse.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Ver también

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Cambia la contraseña de usuario y contraseña por contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o estar vacías. La contraseña de propietario se reemplazará con una cadena aleatoria si la nueva contraseña de propietario es nula o está vacía. Hay 6 combinaciones posibles de valores KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) no son válidos y se generará la excepción correspondiente si el kit encuentra esta combinación. No arroja una excepción si el proceso falla.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| ownerPassword | String | Contraseña de propietario original. |
| newUserPassword | String | Nueva contraseña de usuario. |
| newOwnerPassword | String | Nueva contraseña de propietario. |
| privilege | DocumentPrivilege | Restablecer seguridad. |
| keySize | KeySize | KeySize.x40 para cifrado de 40 bits, KeySize.x128 para cifrado de 128 bits y KeySize.x256 para cifrado de 256 bits. |
| cipher | Algorithm | Algorithm.AES para cifrar utilizando el algoritmo AES o Algorithm.RC4 para el cifrado RC4. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //El TestPath puede reasignarse.
string outFile = "D:\\output.pdf";	//El TestPath puede reasignarse.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ver también

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilesecurity)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
