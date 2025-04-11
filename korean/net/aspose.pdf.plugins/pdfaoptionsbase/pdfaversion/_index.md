---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase 속성. 검증 또는 변환에 사용할 PDF/A 표준의 버전을 가져오거나 설정합니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion 속성

검증 또는 변환에 사용할 PDF/A 표준의 버전을 가져오거나 설정합니다.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### 속성 값

PDF/A 표준의 버전. 이는 [`PdfAStandardVersion`](../../pdfastandardversion/) 열거형의 값 중 하나일 수 있습니다.

## 비고

PDF/A 표준 버전은 PDF/A 검증 및 변환의 준수 수준을 결정하는 데 사용됩니다. 버전이 자동으로 설정되면 시스템은 문서 메타데이터를 기반으로 검증에 적합한 PDF/A 표준 버전을 자동으로 결정합니다. PDF/A 변환 프로세스의 경우 자동은 PDF/A-1b 표준 버전으로 기본 설정됩니다.

### 참조

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)