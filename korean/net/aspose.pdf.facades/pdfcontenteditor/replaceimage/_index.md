---
title: "PdfContentEditor.ReplaceImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서의 지정된 페이지에 있는 지정된 이미지를 다른 이미지로 교체합니다."
type: docs
weight: 440
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

PDF 문서의 지정된 페이지에 있는 지정된 이미지를 다른 이미지로 교체합니다.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 이미지가 교체되는 페이지 번호. |
| index | Int32 | 교체해야 할 이미지 객체의 인덱스. |
| imageFile | String | 교체에 사용할 이미지 파일. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


