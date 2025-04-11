---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfFileInfo. Retorna verdadeiro se uma senha for necessária para modificar permissões ou a propriedade de segurança do documento. Preste atenção que esta propriedade só pode ser lida se uma senha válida foi fornecida no construtor de PdfFileInfo. No caso de PasswordType ser Inaccessible, significa que uma senha inválida foi fornecida, e a leitura desta propriedade falhará com InvalidPasswordException.
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## Propriedade PdfFileInfo.HasEditPassword

Retorna verdadeiro se uma senha for necessária para modificar permissões ou a propriedade de segurança do documento. Preste atenção que esta propriedade só pode ser lida se uma senha válida foi fornecida no [`PdfFileInfo`](../) construtor. No caso de PasswordType ser Inaccessible (significa que uma senha inválida foi fornecida), a leitura desta propriedade falhará com [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### Veja Também

* classe [PdfFileInfo](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)