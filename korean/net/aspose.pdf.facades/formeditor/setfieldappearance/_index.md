---
title: "FormEditor.SetFieldAppearance"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormEditor method. 필드 플래그를 설정합니다."
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

필드 플래그를 설정합니다.

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldName | String | 플래그를 업데이트해야 하는 필드의 이름. |
| flags | AnnotationFlags | 필드의 플래그. |

### 반환 값

플래그가 성공적으로 업데이트된 경우 true.

## 예제

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### 또 보기

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


