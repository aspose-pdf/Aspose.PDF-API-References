---
title: Class BaseListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.BaseListQueryParameters 클래스. 객체 목록을 위한 기본 쿼리 매개변수
type: docs
weight: 160
url: /ko/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters 클래스

객체 목록을 위한 기본 쿼리 매개변수입니다.

```csharp
public class BaseListQueryParameters
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 페이지 매김에 사용할 커서를 가져오거나 설정합니다. after는 목록에서의 위치를 정의하는 객체 ID입니다. 예를 들어, 목록 요청을 하고 100개의 객체를 받아서 obj_foo로 끝난다면, 이후 호출에서 after=obj_foo를 포함하여 목록의 다음 페이지를 가져올 수 있습니다. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 페이지 매김에 사용할 커서를 가져오거나 설정합니다. before는 목록에서의 위치를 정의하는 객체 ID입니다. 예를 들어, 목록 요청을 하고 100개의 객체를 받아서 obj_foo로 끝난다면, 이후 호출에서 before=obj_foo를 포함하여 목록의 이전 페이지를 가져올 수 있습니다. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 반환될 객체 수에 대한 제한을 가져오거나 설정합니다. Limit는 1에서 100 사이의 값을 가질 수 있으며, 기본값은 20입니다. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 객체의 created_at 타임스탬프에 따라 정렬 순서를 가져오거나 설정합니다. asc는 오름차순, desc는 내림차순입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)