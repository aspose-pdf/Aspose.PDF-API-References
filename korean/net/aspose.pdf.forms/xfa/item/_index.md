---
title: "XFA.Item"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "XFA 속성. 경로에 따라 데이터 노드 값을 가져오거나 설정"
type: docs
weight: 50
url: /ko/net/aspose.pdf.forms/xfa/item/
---
## XFA indexer

*path*에 따라 데이터 노드 값을 가져오거나 설정합니다.

```csharp
public string this[string path] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| 경로 | 데이터 노드 경로, 예: form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. 각 노드가 단일 발생만 있더라도 인덱스를 포함해야 합니다. 즉 node1[0].node2[0]... 와 같이 작성하고 node1.node2... 로 쓰지 마세요. |

### 반환 값

데이터 노드 값.

### 또 보기

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


