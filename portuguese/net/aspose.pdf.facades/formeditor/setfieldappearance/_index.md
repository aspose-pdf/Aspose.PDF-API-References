---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Definir flags do campo
type: docs
weight: 280
url: /pt/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## Método FormEditor.SetFieldAppearance

Definir flags do campo

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo cujas flags devem ser atualizadas. |
| flags | AnnotationFlags | Flag do campo. |

### Valor de Retorno

true se as flags foram atualizadas com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Veja Também

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)