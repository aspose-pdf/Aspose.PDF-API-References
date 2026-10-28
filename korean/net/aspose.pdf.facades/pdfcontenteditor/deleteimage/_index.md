---
title: "PdfContentEditor.DeleteImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 지정된 페이지에서 지정된 이미지를 삭제합니다."
type: docs
weight: 320
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

지정된 페이지의 지정된 이미지를 삭제합니다.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 이미지를 삭제해야 할 페이지 번호. |
| index | Int32[] | 이미지 인덱스를 나타내는 배열입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


