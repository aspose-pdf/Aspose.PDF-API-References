---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSecurity. Cripta il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la password proprietario in input è null o vuota. Non genera un'eccezione se il processo fallisce.
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Metodo PdfFileSecurity.TryEncryptFile

Cripta il file Pdf con userpassword e ownerpassword e imposta i privilegi di accesso del documento. La password utente e la password proprietario possono essere null o vuote. La password proprietario sarà sostituita con una stringa casuale se la password proprietario in input è null o vuota. Non genera un'eccezione se il processo fallisce.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password proprietario. |
| privilege | DocumentPrivilege | Imposta privilegio. |
| keySize | KeySize | KeySize.x40 per crittografia a 40 bit, KeySize.x128 per crittografia a 128 bit e KeySize.x256 per crittografia a 256 bit. |

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

### Vedi Anche

* classe [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* classe [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)