---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: OptimizedMemoryStream 메서드. 파생 클래스에서 재정의될 때 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내에서 위치를 이동합니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read 메서드

파생 클래스에서 재정의될 때 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내에서 위치를 이동합니다.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | Byte[] | 바이트 배열입니다. 이 메서드가 반환될 때, 버퍼는 지정된 바이트 배열과 값을 포함합니다. |
| offset | Int32 | 현재 스트림에서 읽은 데이터를 저장하기 시작할 제로 기반 바이트 오프셋입니다. |
| count | Int32 | 현재 스트림에서 읽을 최대 바이트 수입니다. |

### 반환 값

버퍼에 읽힌 총 바이트 수입니다. 현재 사용 가능한 바이트 수가 요청된 바이트 수보다 적거나 스트림의 끝에 도달한 경우 0(0)이 될 수 있습니다.

### 참조

* 클래스 [OptimizedMemoryStream](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)