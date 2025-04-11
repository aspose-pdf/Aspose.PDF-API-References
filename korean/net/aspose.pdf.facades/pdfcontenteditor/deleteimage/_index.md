---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 지정된 페이지에서 지정된 이미지를 삭제합니다.
type: docs
weight: 320
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

지정된 페이지에서 지정된 이미지를 삭제합니다.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 이미지를 삭제해야 하는 페이지 번호입니다. |
| index | Int32[] | 이미지의 인덱스를 나타내는 배열입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

PDF 문서에서 모든 이미지를 삭제합니다.

```csharp
public void DeleteImage()
```

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)