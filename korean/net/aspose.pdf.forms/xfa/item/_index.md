---
title: XFA.Item
second_title: Aspose.PDF for .NET API Reference
description: XFA 속성. 경로에 따라 데이터 노드 값을 가져오거나 설정합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.forms/xfa/item/
---
## XFA 인덱서

경로에 따라 데이터 노드 값을 가져오거나 설정합니다.

```csharp
public string this[string path] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| path | 데이터 노드 경로, 예: form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. 데이터에 각 노드의 단일 발생만 포함되어 있더라도 인덱스를 포함해야 합니다. 즉, node1[0].node2[0]... 대신 node1.node2...로 작성하십시오. |

### 반환 값

데이터 노드 값.

### 참조

* 클래스 [XFA](../)
* 네임스페이스 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 어셈블리 [Aspose.PDF](../../../)