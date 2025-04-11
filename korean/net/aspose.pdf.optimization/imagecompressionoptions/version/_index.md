---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: ImageCompressionOptions 속성. 압축 알고리즘의 버전. 가능한 값은 1. 표준 압축 2. 빠른 개선된 압축(표준보다 빠르지만 모든 이미지에 적용되지 않을 수 있음) 3. 혼합(빠른 알고리즘으로 압축할 수 없는 이미지에 표준 압축이 적용되며, 이는 최상의 압축을 제공할 수 있지만 "빠른" 알고리즘보다 느림). "빠른" 버전은 이미지 크기 조정에 적용되지 않으며 표준 방법이 사용됩니다. 기본값은 표준입니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## ImageCompressionOptions.Version 속성

압축 알고리즘의 버전. 가능한 값은: 1. 표준 압축, 2. 빠른(표준보다 빠르지만 모든 이미지에 적용되지 않을 수 있는 개선된 압축), 3. 혼합(빠른 알고리즘으로 압축할 수 없는 이미지에 표준 압축이 적용되며, 이는 최상의 압축을 제공할 수 있지만 "빠른" 알고리즘보다 느림). "빠른" 버전은 이미지 크기 조정에 적용되지 않으며(표준 방법이 사용됩니다). 기본값은 "표준"입니다.

```csharp
public ImageCompressionVersion Version { get; set; }
```

### 참조

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)