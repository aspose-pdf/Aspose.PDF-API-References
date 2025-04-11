---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact 메서드. 지연 업데이트를 시작합니다. 성능을 개선하기 위해 동일한 아티팩트에 여러 변경을 해야 하는 경우 이 기능을 사용하십시오. 일반적으로 아티팩트 속성이 변경될 때마다 아티팩트 연산자가 변경됩니다. 이로 인해 아티팩트가 변경될 때마다 페이지 내용이 변경됩니다. 이러한 효과를 피하려면 모든 아티팩트 업데이트를 StartUpdates/SaveUpdates 호출 사이에 배치하십시오. 이렇게 하면 페이지 내용을 한 번만 변경할 수 있습니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates 메서드

지연 업데이트를 시작합니다. 성능을 개선하기 위해 동일한 아티팩트에 여러 변경을 해야 하는 경우 이 기능을 사용하십시오. 일반적으로 아티팩트 속성이 변경될 때마다 아티팩트 연산자가 변경됩니다. 이로 인해 아티팩트가 변경될 때마다 페이지 내용이 변경됩니다. 이러한 효과를 피하려면 모든 아티팩트 업데이트를 StartUpdates/SaveUpdates 호출 사이에 배치하십시오. 이렇게 하면 페이지 내용을 한 번만 변경할 수 있습니다.

```csharp
public void BeginUpdates()
```

## 예제

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### 참조

* 클래스 [Artifact](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)