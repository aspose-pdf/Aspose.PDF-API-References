---
title: PdfFileStamp.Close
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 메서드. 열린 파일을 닫고 변경 사항을 저장합니다. 경고. 입력 또는 출력 스트림이 지정된 경우 Close 메서드에 의해 닫히지 않습니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/pdffilestamp/close/
---
## PdfFileStamp.Close 메서드

열린 파일을 닫고 변경 사항을 저장합니다. 경고. 입력 또는 출력 스트림이 지정된 경우 Close() 메서드에 의해 닫히지 않습니다.

```csharp
public override void Close()
```

## 예제

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
//do some work... 
stamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)