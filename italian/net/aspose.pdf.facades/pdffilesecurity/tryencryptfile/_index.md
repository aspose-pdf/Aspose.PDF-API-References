---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSecurity. Cifra il file Pdf con password utente e password del proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password del proprietario possono essere null o vuote. La password del proprietario sarà sostituita con una stringa casuale se la password del proprietario in ingresso è null o vuota. Non lancia un'eccezione se l'operazione fallisce"
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Cifra un file Pdf con password utente e password del proprietario e imposta i privilegi del documento per l'accesso. La password utente e la password del proprietario possono essere null o vuote. La password del proprietario verrà sostituita con una stringa casuale se la password del proprietario fornita è null o vuota. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| privilegio | DocumentPrivilege | Imposta privilegio. |
| keySize | KeySize | KeySize.x40 per la crittografia a 40 bit, KeySize.x128 per la crittografia a 128 bit e KeySize.x256 per la crittografia a 256 bit. |

### Valore di ritorno

True per successo, o false.

## Esempi

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

### Vedi anche

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


