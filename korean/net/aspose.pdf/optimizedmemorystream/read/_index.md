---
title: "OptimizedMemoryStream.Read"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OptimizedMemoryStream 메서드. 파생 클래스에서 재정의될 때 현재 스트림에서 바이트 시퀀스를 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동합니다."
type: docs
weight: 100
url: /ko/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

파생 클래스에서 재정의될 때, 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 버퍼 | Byte[] | 바이트 배열입니다. 이 메서드가 반환될 때, buffer에는 지정된 바이트 배열이 값과 함께 포함됩니다. |
| 오프셋 | Int32 | 현재 스트림에서 읽은 데이터를 저장하기 시작할 제로 기반 바이트 오프셋입니다. |
| 개수 | Int32 | 현재 스트림에서 읽을 최대 바이트 수입니다. |

### 반환 값

버퍼에 읽힌 전체 바이트 수입니다. 요청한 바이트 수보다 적을 수 있으며, 이는 해당 바이트가 현재 사용 가능하지 않거나 스트림 끝에 도달한 경우 0(0)이 될 수 있습니다.

### 또 보기

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


