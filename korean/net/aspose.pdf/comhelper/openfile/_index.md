---
title: "ComHelper.OpenFile"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ComHelper 메서드. 파일 이름을 사용하여 Document를 생성하고 반환합니다. Document와 동일합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

파일 이름 *filename* 을 사용하여 Document를 생성하고 반환합니다. [`Document`](../../document/document/)와 동일합니다.

```csharp
public Document OpenFile(string filename)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | pdf 문서 파일의 이름. |

### 반환 값

Document 객체

### 또 보기

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

암호화된 문서를 작업하기 위해 [`Document`](../../document/) 클래스의 새 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenFile(string filename, string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |

### 반환 값

Document 객체

### 또 보기

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

암호화된 문서를 작업하기 위해 [`Document`](../../document/) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | Document 파일 이름. |
| password | String | 사용자 또는 소유자 비밀번호. |
| isManagedStream | Boolean | 만약 `true` 로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 반환 값

Document 객체

### 또 보기

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

필요한 변환 옵션을 제공하여 파일에서 기존 문서를 열어 PDF 문서를 얻습니다.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 파일 이름 | String | pdf 문서로 변환할 입력 파일. |
| 옵션 | LoadOptions | *filename* 을 pdf 문서로 변환하기 위한 속성을 나타냅니다. |

### 반환 값

Document 객체

### 또 보기

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


