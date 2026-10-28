---
title: "클래스 VectorStoreResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.VectorStoreResponse 클래스. 벡터 저장소 객체"
type: docs
weight: 1480
url: /ko/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

벡터 저장소 객체.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | 벡터 저장소가 생성된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | 벡터 저장소의 만료 정책을 가져오거나 설정합니다. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | 벡터 저장소가 만료되는 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | 처리된 파일 수를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | 벡터 저장소가 마지막으로 활성화된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | 벡터 저장소의 이름을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 vector_store입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | 벡터 저장소의 상태를 가져오거나 설정합니다. 상태는 expired, in_progress, completed 중 하나일 수 있습니다. completed 상태는 벡터 저장소가 사용 준비가 되었음을 나타냅니다. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | 벡터 저장소의 파일이 사용한 총 바이트 수를 가져오거나 설정합니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


