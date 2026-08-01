---
title: "Document.IgnoreCorruptedObjects"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 속성. 소스 파일의 오류를 무시하는 플래그를 가져오거나 설정합니다. 이 플래그가 false인 경우, 소스 파일의 일부 객체가 손상되면 소스 문서의 페이지를 대상 문서로 복사할 때 복사 과정이 예외와 함께 중단됩니다. 예: dest.Pages.Addsrc.Pages. 플래그가 true로 설정되면 손상된 객체가 빈 값으로 대체됩니다. 기본값은 true입니다."
type: docs
weight: 290
url: /ko/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

소스 파일의 오류를 무시하는 플래그를 가져오거나 설정합니다. 소스 문서의 페이지를 대상 문서로 복사할 때, 이 플래그가 false이면 소스 파일의 일부 객체가 손상된 경우 예외가 발생하여 복사 과정이 중단됩니다. 예: dest.Pages.Add(src.Pages); 이 플래그가 true로 설정되면 손상된 객체가 빈 값으로 대체됩니다. 기본값: true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


