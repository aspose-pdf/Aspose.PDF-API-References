---
title: "Stamp.Pages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Stamp 속성. 스탬프가 적용될 페이지 번호 배열을 가져오거나 설정합니다. Pages가 null이면 문서의 모든 페이지에 적용됩니다"
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

스탬프에 의해 영향을 받을 페이지 번호 배열을 가져오거나 설정합니다. Pages가 null인 경우 문서의 모든 페이지가 영향을 받습니다.

```csharp
public int[] Pages { get; set; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//스탬프를 1번째, 4번째 및 6번째 페이지에만 적용합니다.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


