---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Bir metin alanının hizalama stilini ayarlayın
type: docs
weight: 260
url: /tr/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment metodu

Bir metin alanının hizalama stilini ayarlayın.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |
| alignment | Int32 | FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter ve FormFieldFacade.AlignRight dahil olmak üzere hizalama stil tanımı. |

### Dönüş Değeri

Alan bulunduysa ve hizalama ayarlandıysa true döner.

## Örnekler

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)