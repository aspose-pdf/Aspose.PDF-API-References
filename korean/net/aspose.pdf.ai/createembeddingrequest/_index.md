---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest 클래스. Create Embeddings 엔드포인트에 대한 요청을 나타냅니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest 클래스

Create Embeddings 엔드포인트에 대한 요청을 나타냅니다.

```csharp
public class CreateEmbeddingRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 결과 출력 임베딩이 가져야 하는 차원의 수를 가져오거나 설정합니다. 텍스트 임베딩-3 및 이후 모델에서만 지원됩니다. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 임베딩을 반환할 형식을 가져오거나 설정합니다. float 또는 base64일 수 있습니다. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 임베드할 입력 텍스트를 가져오거나 설정합니다. 문자열 또는 토큰 배열로 인코딩됩니다. 단일 요청에서 여러 입력을 임베드하려면 문자열 배열 또는 토큰 배열의 배열을 전달하십시오. 입력은 모델의 최대 입력 토큰(텍스트 임베딩-ada-002의 경우 8192 토큰)을 초과할 수 없으며, 빈 문자열일 수 없고, 모든 배열은 2048 차원 이하이어야 합니다. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 임베딩을 생성할 모델을 가져오거나 설정합니다. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | OpenAI가 남용을 모니터링하고 감지하는 데 도움이 될 수 있는 최종 사용자를 나타내는 고유 식별자를 가져오거나 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)