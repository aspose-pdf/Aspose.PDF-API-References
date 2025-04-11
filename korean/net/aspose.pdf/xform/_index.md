---
title: Class XForm
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XForm 클래스. 클래스는 XForm을 나타냅니다.
type: docs
weight: 11330
url: /ko/net/aspose.pdf/xform/
---
## XForm 클래스

클래스는 XForm을 나타냅니다.

```csharp
public sealed class XForm : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BBox](../../aspose.pdf/xform/bbox/) { get; set; } | 폼 경계 상자를 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf/xform/contents/) { get; } | 폼의 연산자를 가져옵니다. |
| [IT](../../aspose.pdf/xform/it/) { get; } | 폼 IT를 가져옵니다. 폼 IT는 XObject의 의도를 설명하는 이름입니다. |
| [Matrix](../../aspose.pdf/xform/matrix/) { get; set; } | 폼의 행렬을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf/xform/name/) { get; set; } | 폼 이름을 가져오거나 설정합니다. 폼 이름은 페이지 리소스의 XObject 사전에서 폼을 참조하는 데 사용되는 이름입니다. |
| [Opi](../../aspose.pdf/xform/opi/) { get; } | Open Prepress Interface (OPI)를 가져옵니다. |
| [Rectangle](../../aspose.pdf/xform/rectangle/) { get; } | 폼의 사각형을 가져오거나 설정합니다. |
| [Resources](../../aspose.pdf/xform/resources/) { get; } | 폼 XObject 리소스를 가져옵니다. |
| [Subtype](../../aspose.pdf/xform/subtype/) { get; } | 폼 서브타입을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CreateNewForm](../../aspose.pdf/xform/createnewform/)(Page, Document) | 페이지의 내용을 복제하는 XForm을 생성합니다. |
| [Dispose](../../aspose.pdf/xform/dispose/)() | 메모리를 해제합니다. |
| [FreeMemory](../../aspose.pdf/xform/freememory/)() | 캐시된 데이터를 지웁니다. |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources)() | Form X-Object의 리소스를 반환합니다. 폼에 리소스가 없고 allowCreate가 true인 경우, 리소스는 폼을 위해 자동으로 생성됩니다. |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources_1)(bool) | Form X-Object의 리소스를 반환합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)