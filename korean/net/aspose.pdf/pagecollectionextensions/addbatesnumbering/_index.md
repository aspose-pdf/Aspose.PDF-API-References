---
title: PageCollectionExtensions.AddBatesNumbering
second_title: Aspose.PDF for .NET API Reference
description: PageCollectionExtensions 메서드. 주어진 페이지 컬렉션의 각 페이지에 Bates 번호 매기기를 추가하고 BatesNArtifact를 구성하는 데 사용할 지정된 작업을 사용합니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf/pagecollectionextensions/addbatesnumbering/
---
## AddBatesNumbering(this PageCollection, Action&lt;BatesNArtifact&gt;) {#addbatesnumbering_1}

주어진 페이지 컬렉션의 각 페이지에 Bates 번호 매기기를 추가하고 BatesNArtifact를 구성하는 데 사용할 지정된 작업을 사용합니다.

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, 
    Action<BatesNArtifact> action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageCollection | PageCollection | Bates 번호 매기기가 추가될 페이지 컬렉션입니다. |
| action | Action`1 | 각 페이지에 추가하기 전에 BatesNArtifact를 구성하는 작업입니다. |

### See Also

* class [PageCollection](../../pagecollection/)
* class [BatesNArtifact](../../batesnartifact/)
* class [PageCollectionExtensions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddBatesNumbering(this PageCollection, BatesNArtifact) {#addbatesnumbering}

지정된 Bates 번호 매기기 아티팩트를 주어진 페이지 컬렉션의 각 페이지에 추가합니다.

```csharp
public static void AddBatesNumbering(this PageCollection pageCollection, BatesNArtifact artifact)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageCollection | PageCollection | Bates 번호 매기기 아티팩트가 추가될 페이지 컬렉션입니다. |
| artifact | BatesNArtifact | 각 페이지에 추가될 BatesNArtifact 인스턴스입니다. |

### See Also

* class [PageCollection](../../pagecollection/)
* class [BatesNArtifact](../../batesnartifact/)
* class [PageCollectionExtensions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)