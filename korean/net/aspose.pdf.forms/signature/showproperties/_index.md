---
title: Signature.ShowProperties
second_title: Aspose.PDF for .NET API Reference
description: 서명 속성. 서명 속성을 표시/숨기도록 강제합니다. ShowProperties가 true인 경우 서명 필드는 디지털 서명된 인증서 주체 날짜 서명.Date 이유 서명.Reason 위치 서명.Location을 나타내는 미리 정의된 형식의 문자열을 가집니다. 여기서 X는 X 값의 자리 표시자입니다. 또한 서명에는 이미지가 있을 수 있으며, 이 경우 나열된 문자열은 이미지 위에 배치됩니다. 기본적으로 ShowProperties는 true입니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.forms/signature/showproperties/
---
## Signature.ShowProperties 속성

서명 속성을 표시/숨기도록 강제합니다. ShowProperties가 true인 경우 서명 필드는 다음을 나타내는 미리 정의된 형식의 문자열을 가집니다: ------------------------------------------- 디지털 서명된 {certificate subject} 날짜: {signature.Date} 이유: {signature.Reason} 위치: {signature.Location} ------------------------------------------- 여기서 {X}는 X 값의 자리 표시자입니다. 또한 서명에는 이미지가 있을 수 있으며, 이 경우 나열된 문자열은 이미지 위에 배치됩니다. 기본적으로 ShowProperties는 true입니다.

```csharp
public bool ShowProperties { get; set; }
```

### 참조

* 클래스 [Signature](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)