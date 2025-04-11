---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 메서드. 필드 플래그 설정
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance 메서드

필드 플래그 설정

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 플래그를 업데이트해야 하는 필드의 이름. |
| flags | AnnotationFlags | 필드의 플래그. |

### 반환 값

플래그가 성공적으로 업데이트되면 true.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### 참조

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)