---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp 속성. 배경 상태를 가져오거나 설정합니다. true인 경우 스탬프는 스탬프된 페이지의 배경으로 배치됩니다. 기본값은 false로 설정됩니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground 속성

배경 상태를 가져오거나 설정합니다. true인 경우 스탬프는 스탬프된 페이지의 배경으로 배치됩니다. 기본값은 false로 설정됩니다.

```csharp
public bool IsBackground { get; set; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 참조

* 클래스 [Stamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)