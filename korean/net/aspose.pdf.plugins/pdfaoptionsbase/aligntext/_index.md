---
title: "PdfAOptionsBase.AlignText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAOptionsBase 속성. PDF/A 변환 과정에서 텍스트 정렬을 유지하기 위해 추가적인 수단이 필요한지 여부를 나타내는 값을 가져오거나 설정합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

PDF/A 변환 과정에서 텍스트 정렬을 유지하기 위해 추가적인 수단이 필요한지를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true`는 텍스트 정렬이 변경되고 이를 복원하기 위해 추가 작업이 필요함을 의미합니다; 그렇지 않으면 `false`입니다.

## 비고

`true`로 설정하면 변환 과정에서 원래 텍스트 세그먼트 경계를 복원하려고 시도합니다. 대부분의 문서에서는 기본값인 `false`를 변경할 필요가 없으며, 기본 변환 과정에서 텍스트 정렬이 변경되지 않기 때문입니다.

### 또 보기

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


