---
title: "PageCollectionExtensions.AddBatesNumbering"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PageCollectionExtensions 메서드. 지정된 PageCollection의 각 Page에 Bates 번호 매기기를 추가하며, 지정된 작업을 사용해 BatesNArtifact를 구성합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## AddBatesNumbering(this PageCollection, Action&lt;BatesNArtifact&gt;) {#addbatesnumbering_1}

지정된 작업을 사용하여 BatesNArtifact를 구성하면서 주어진 page collection의 각 page에 Bates 번호 매기기를 추가합니다.

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, 
    Action<BatesNArtifact> action)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageCollection | PageCollection | Bates 번호 매기기가 추가될 PageCollection. |
| 작업 | Action`1 | 각 Page에 추가하기 전에 BatesNArtifact를 구성하는 작업. |

### 또 보기

* class [PageCollection](../../pagecollection/)
* class [BatesNArtifact](../../batesnartifact/)
* class [PageCollectionExtensions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddBatesNumbering(this PageCollection, BatesNArtifact) {#addbatesnumbering}

주어진 page collection의 각 page에 지정된 Bates 번호 매기기 artifact를 추가합니다.

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, BatesNArtifact artifact)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageCollection | PageCollection | Bates 번호 매기기 아티팩트가 추가될 PageCollection. |
| 아티팩트 | BatesNArtifact | 각 Page에 추가될 BatesNArtifact 인스턴스. |

### 또 보기

* class [PageCollection](../../pagecollection/)
* class [BatesNArtifact](../../batesnartifact/)
* class [PageCollectionExtensions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


