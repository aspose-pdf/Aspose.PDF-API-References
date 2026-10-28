---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageEditor 메서드. 원점을 0 0에서 지정된 점으로 이동합니다. 원점은 왼쪽 아래이며 단위는 1인치당 72포인트입니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

원점을 (0, 0)에서 지정된 점으로 이동합니다. 원점은 왼쪽 하단이며 단위는 포인트(1인치 = 72포인트)입니다.

```csharp
public void MovePosition(float moveX, float moveY)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| moveX | Single | X좌표. |
| moveY | Single | Y좌표. |

## 예제

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### 또 보기

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


