---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: 라이센스 메서드. 구성 요소에 라이센스를 부여합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

구성 요소에 라이센스를 부여합니다.

```csharp
public void SetLicense(string licenseName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseName | String | 전체 또는 짧은 파일 이름 또는 포함된 리소스의 이름일 수 있습니다. 빈 문자열을 사용하여 평가 모드로 전환합니다. |

## 비고

다음 위치에서 라이센스를 찾으려고 시도합니다:

1. 명시적 경로.

2. Aspose 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트의 호출 어셈블리를 포함하는 폴더.

4. 진입(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리에 포함된 리소스.

**참고:** .NET Compact Framework에서는 다음 위치에서만 라이센스를 찾으려고 시도합니다:

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리에 포함된 리소스.

[Java]

2. Aspose 구성 요소 JAR 파일을 포함하는 폴더.

3. 클라이언트의 호출 JAR 파일을 포함하는 폴더.

### 참조

* 클래스 [License](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

구성 요소에 라이센스를 부여합니다.

```csharp
public void SetLicense(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 라이센스가 포함된 스트림입니다. |

## 비고

이 메서드를 사용하여 스트림에서 라이센스를 로드합니다.

### 참조

* 클래스 [License](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)