---
title: "Stamp.Rotation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Stamp 속성. 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation property

스탬프의 회전을 도 단위로 가져오거나 설정합니다.

```csharp
public float Rotation { get; set; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


