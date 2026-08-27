---
title: "클래스 AssistantListQueryParameters"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.AssistantListQueryParameters 클래스. 어시스턴트를 나열하기 위한 쿼리 매개변수 객체를 나타냅니다"
type: docs
weight: 110
url: /ko/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## AssistantListQueryParameters class

어시스턴트 목록을 가져오기 위한 쿼리 매개변수 객체를 나타냅니다.

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | 페이지네이션에 사용할 커서를 설정하거나 가져옵니다. after는 목록에서 현재 위치를 정의하는 객체 ID이며, 예를 들어 100개의 객체를 반환하고 마지막이 obj_foo인 목록 요청을 수행한 경우, 다음 호출에 after=obj_foo를 포함하여 다음 페이지를 가져올 수 있습니다. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | 페이지네이션에 사용할 커서를 설정하거나 가져옵니다. before는 목록에서 현재 위치를 정의하는 객체 ID이며, 예를 들어 100개의 객체를 반환하고 마지막이 obj_foo인 목록 요청을 수행한 경우, 다음 호출에 before=obj_foo를 포함하여 이전 페이지를 가져올 수 있습니다. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | 반환될 객체 수에 대한 제한을 가져오거나 설정합니다. 제한은 1에서 100 사이이며, 기본값은 20입니다. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | 객체의 created_at 타임스탬프를 기준으로 정렬 순서를 가져오거나 설정합니다. asc는 오름차순, desc는 내림차순을 의미합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | 어시스턴트를 나열하기 위한 쿼리 매개변수를 가져옵니다. |

### 또 보기

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


