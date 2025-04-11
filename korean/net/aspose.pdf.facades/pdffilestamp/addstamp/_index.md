---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 메서드. 파일에 스탬프 추가
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp 메서드

파일에 스탬프를 추가합니다.

```csharp
public void AddStamp(Stamp stamp)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stamp | Stamp | 스탬프 객체입니다. |

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

### 참조

* 클래스 [Stamp](../../stamp/)
* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)