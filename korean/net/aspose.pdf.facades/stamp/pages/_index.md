---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: 스탬프 속성. 스탬프에 영향을 받을 페이지 번호의 배열을 가져오거나 설정합니다. Pages가 null이면 문서의 모든 페이지에 영향을 미칩니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages 속성

스탬프에 영향을 받을 페이지 번호의 배열을 가져오거나 설정합니다. Pages = null이면 문서의 모든 페이지에 영향을 미칩니다.

```csharp
public int[] Pages { get; set; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 참조

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)