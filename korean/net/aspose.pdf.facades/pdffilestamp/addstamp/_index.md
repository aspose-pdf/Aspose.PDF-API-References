---
title: "PdfFileStamp.AddStamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileStamp 메서드. 파일에 스탬프를 추가합니다"
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

파일에 스탬프를 추가합니다.

```csharp
public void AddStamp(Stamp stamp)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스탬프 | 스탬프 | 스탬프 객체 |

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


