---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSecurity. Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña del propietario se añadirá mediante una cadena aleatoria. Lanza una excepción si el proceso falla.
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña del propietario se añadirá mediante una cadena aleatoria. Lanza una excepción si el proceso falla.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| privilege | DocumentPrivilege | Establecer privilegio. |

### Valor de Retorno

Verdadero para éxito.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Establece la seguridad del archivo Pdf con la contraseña original. Lanza una excepción si el proceso falla.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario original. |
| ownerPassword | String | Contraseña de propietario original. |
| privilege | DocumentPrivilege | Establecer privilegio. |

### Valor de Retorno

Verdadero para éxito.

## Ejemplos

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Ver También

* clase [DocumentPrivilege](../../documentprivilege/)
* clase [PdfFileSecurity](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)