---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Bir metin alanının dikey hizalama stilini ayarlayın
type: docs
weight: 270
url: /tr/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV metodu

Bir metin alanının dikey hizalama stilini ayarlayın.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |
| alignment | Int32 | FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle ve FormFieldFacade.AlignRight dahil olmak üzere hizalama stil tanımı. |

### Dönüş Değeri

Alan bulunduysa ve hizalama başarıyla doldurulduysa true döner.

## Örnekler

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)