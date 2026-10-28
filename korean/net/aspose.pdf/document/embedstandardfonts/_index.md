---
title: "Document.EmbedStandardFonts"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document property. 문서가 모든 표준 Type1 폰트를 포함해야 함을 선언하는 속성으로, 해당 폰트의 IsEmbedded 플래그가 true로 설정됩니다. 모든 PDF 폰트는 IsEmbedded 플래그를 true로 설정하면 문서에 포함시킬 수 있지만, PDF 표준 Type1 폰트는 이 규칙의 예외입니다. 표준 Type1 폰트 포함에는 많은 시간이 소요되므로, 이러한 폰트를 포함하려면 지정된 폰트에 대해 IsEmbedded 플래그를 true로 설정할 뿐만 아니라 문서 수준에서 추가 플래그인 EmbedStandardFonts를 true로 설정해야 합니다. 이 속성은 모든 폰트에 대해 한 번만 설정할 수 있습니다. 기본값은 false입니다."
type: docs
weight: 160
url: /ko/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts property

문서가 IsEmbedded 플래그가 true로 설정된 모든 표준 Type1 폰트를 임베드해야 함을 선언하는 속성입니다. 모든 PDF 폰트는 IsEmbedded 플래그를 true로 설정하면 간단히 문서에 임베드할 수 있지만, PDF 표준 Type1 폰트는 이 규칙의 예외입니다. 표준 Type1 폰트를 임베드하려면 시간이 많이 소요되므로, 해당 폰트에 대해 IsEmbedded 플래그를 true로 설정할 뿐만 아니라 문서 수준에서 추가 플래그인 EmbedStandardFonts = true; 를 설정해야 합니다. 이 속성은 모든 폰트에 대해 한 번만 설정할 수 있습니다. 기본값은 false입니다.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


