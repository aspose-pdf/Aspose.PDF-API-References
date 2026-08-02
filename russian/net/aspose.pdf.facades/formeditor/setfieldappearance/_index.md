---
title: "FormEditor.SetFieldAppearance"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод FormEditor. Установить флаги поля"
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Установить флаги поля

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, флаги которого должны быть обновлены. |
| flags | AnnotationFlags | Флаг поля. |

### Возвращаемое значение

true если флаги были успешно обновлены.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### См. также

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


