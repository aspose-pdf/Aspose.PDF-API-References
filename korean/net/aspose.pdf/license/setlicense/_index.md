---
title: "License.SetLicense"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "License 메서드. 구성 요소에 라이선스를 적용합니다"
type: docs
weight: 40
url: /ko/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(string licenseName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseName | String | 전체 파일 이름이거나 짧은 파일 이름, 혹은 포함된 리소스의 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

## 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적인 경로.

2. Aspose 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트 호출 어셈블리를 포함하는 폴더.

4. 엔트리(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트 호출 어셈블리의 포함된 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적인 경로.

2. 클라이언트 호출 어셈블리의 포함된 리소스.

[Java]

2. Aspose 구성 요소 JAR 파일을 포함하는 폴더.

3. 클라이언트 호출 JAR 파일을 포함하는 폴더.

### 또 보기

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 라이선스를 포함하는 스트림. |

## 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

### 또 보기

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


