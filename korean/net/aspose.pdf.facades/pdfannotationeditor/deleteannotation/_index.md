---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAnnotationEditor 메서드. 지정된 주석 이름으로 주석을 삭제합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

지정된 주석 이름을 가진 주석을 삭제합니다.

```csharp
public void DeleteAnnotation(string annotName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| annotName | String | 주석 이름 |

## 예제

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


