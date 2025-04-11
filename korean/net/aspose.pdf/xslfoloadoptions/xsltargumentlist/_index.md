---
title: XslFoLoadOptions.XsltArgumentList
second_title: Aspose.PDF for .NET API Reference
description: XslFoLoadOptions 속성. 기존 xls 매개변수에 값을 삽입하기 위한 XsltArgumentList XLS 파일에는 값이 없는 animal 매개변수가 있습니다 XsltArgumentList args new XsltArgumentList args.AddParamanimal cat 이제 변환기는 XLS 파일에 값이 cat인 animal 매개변수가 있다고 가정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/
---
## XslFoLoadOptions.XsltArgumentList 속성

기존 xls 매개변수에 값을 삽입하기 위한 XsltArgumentList XLS 파일에는 값이 없는 'animal' 매개변수가 있습니다: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); 이제 변환기는 XLS 파일에 값이 'cat'인 'animal' 매개변수가 있다고 가정합니다.

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

### 참조

* 클래스 [XslFoLoadOptions](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)