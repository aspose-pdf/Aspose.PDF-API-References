---
title: "Stamp.IsBackground"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Stamp 속성. 배경 상태를 가져오거나 설정합니다. true이면 스탬프가 해당 페이지의 배경으로 배치됩니다. 기본값은 false로 설정됩니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

배경 상태를 가져오거나 설정합니다. true인 경우 스탬프가 해당 페이지의 배경으로 배치됩니다. 기본값은 false입니다.

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

### 또 보기

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


