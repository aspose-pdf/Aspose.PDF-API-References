---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: 스탬프 속성. 스탬프의 회전을 도 단위로 가져오거나 설정합니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/stamp/rotation/
---
## Stamp.Rotation 속성

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

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)