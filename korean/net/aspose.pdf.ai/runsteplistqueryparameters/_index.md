---
title: Class RunStepListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepListQueryParameters 클래스. 실행 단계 목록을 나열하기 위한 쿼리 매개변수 객체
type: docs
weight: 1040
url: /ko/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## RunStepListQueryParameters 클래스

실행 단계 목록을 나열하기 위한 쿼리 매개변수 객체입니다.

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 페이지 매김에 사용되는 커서를 가져오거나 설정합니다. after는 목록에서의 위치를 정의하는 객체 ID입니다. 예를 들어, 목록 요청을 하고 100개의 객체를 수신하여 obj_foo로 끝나는 경우, 이후 호출에서 after=obj_foo를 포함하여 목록의 다음 페이지를 가져올 수 있습니다. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 페이지 매김에 사용되는 커서를 가져오거나 설정합니다. before는 목록에서의 위치를 정의하는 객체 ID입니다. 예를 들어, 목록 요청을 하고 100개의 객체를 수신하여 obj_foo로 끝나는 경우, 이후 호출에서 before=obj_foo를 포함하여 목록의 이전 페이지를 가져올 수 있습니다. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 반환될 객체 수에 대한 제한을 가져오거나 설정합니다. Limit은 1에서 100 사이의 값을 가질 수 있으며, 기본값은 20입니다. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 객체의 created_at 타임스탬프에 따라 정렬 순서를 가져오거나 설정합니다. asc는 오름차순, desc는 내림차순을 의미합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | 실행 단계 목록을 나열하기 위한 쿼리 매개변수를 가져옵니다. |

### 참조

* 클래스 [BaseListQueryParameters](../baselistqueryparameters/)
* 인터페이스 [IQueryParameters](../iqueryparameters/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)