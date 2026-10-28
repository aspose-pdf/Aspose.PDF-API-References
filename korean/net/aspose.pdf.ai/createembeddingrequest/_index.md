---
title: "클래스 CreateEmbeddingRequest"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.CreateEmbeddingRequest 클래스. Create Embeddings 엔드포인트에 대한 요청을 나타냅니다."
type: docs
weight: 270
url: /ko/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Create Embeddings 엔드포인트에 대한 요청을 나타냅니다.

```csharp
public class CreateEmbeddingRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 결과 출력 임베딩이 가져야 할 차원 수를 가져오거나 설정합니다. text-embedding-3 및 이후 모델에서만 지원됩니다. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 임베딩을 반환할 형식을 가져오거나 설정합니다. float 또는 base64 중 하나일 수 있습니다. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 임베딩할 입력 텍스트를 가져오거나 설정합니다. 문자열이나 토큰 배열로 인코딩됩니다. 단일 요청에서 여러 입력을 임베딩하려면 문자열 배열 또는 토큰 배열의 배열을 전달합니다. 입력은 모델의 최대 입력 토큰(텍스트-embedding-ada-002의 경우 8192 토큰)을 초과해서는 안 되며, 빈 문자열일 수 없고, 모든 배열은 2048 차원 이하이어야 합니다. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 임베딩을 생성할 모델을 가져오거나 설정합니다. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | 엔드 유저를 나타내는 고유 식별자를 가져오거나 설정합니다. 이는 OpenAI가 남용을 모니터링하고 감지하는 데 도움이 될 수 있습니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


