---
title: "OptimizedMemoryStream 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.OptimizedMemoryStream 클래스. 표준 용량보다 더 큰 MemoryStream을 정의합니다."
type: docs
weight: 8130
url: /ko/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

보다 표준적인 용량을 포함할 수 있는 MemoryStream을 정의합니다.

```csharp
public class OptimizedMemoryStream : Stream
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | 새 `OptimizedMemoryStream` 클래스 인스턴스를 초기화합니다. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | 지정된 바이트 배열을 기반으로 새 `OptimizedMemoryStream` 클래스 인스턴스를 초기화합니다. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | 새 `OptimizedMemoryStream` 클래스 인스턴스를 초기화합니다. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | 지정된 바이트 배열을 기반으로 새 `OptimizedMemoryStream` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | 기본 버퍼의 크기를 가져오거나 설정합니다. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | 파생 클래스에서 재정의될 때, 현재 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | 파생 클래스에서 재정의될 때, 현재 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | 파생 클래스에서 재정의될 때, 현재 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Dispose 시 기본 버퍼를 해제할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | 파생 클래스에서 재정의될 때, 스트림의 바이트 단위 길이를 가져옵니다. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | 파생 클래스에서 재정의될 때, 현재 스트림 내 위치를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | 함수가 재정의되었습니다. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | 파생 클래스에서 재정의될 때, 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | 스트림에서 한 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동합니다. 스트림 끝에 도달하면 -1을 반환합니다. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | 파생 클래스에서 재정의될 때, 현재 스트림 내 위치를 설정합니다. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | 파생 클래스에서 재정의될 때, 현재 스트림의 길이를 설정합니다. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | 현재 스트림을 바이트 배열로 변환합니다. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | 파생 클래스에서 재정의될 때, 현재 스트림에 바이트 시퀀스를 쓰고 쓰여진 바이트 수만큼 이 스트림 내 현재 위치를 이동합니다. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | 스트림의 현재 위치에 한 바이트를 쓰고 스트림 내 위치를 한 바이트만큼 이동합니다. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | 지정된 스트림에 씁니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | 바이트 단위 기본 버퍼 크기 값. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


