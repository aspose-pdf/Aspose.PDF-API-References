---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: ComHelper 메서드. 파일 이름을 사용하여 문서를 생성하고 반환합니다. Document와 동일합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

*filename*을 사용하여 문서를 생성하고 반환합니다. [`Document`](../../document/document/)와 동일합니다.

```csharp
public Document OpenFile(string filename)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | 문자열 | PDF 문서 파일의 이름입니다. |

### 반환 값

문서 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

암호화된 문서 작업을 위한 [`Document`](../../document/) 클래스의 새 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenFile(string filename, string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | 문자열 | 문서 파일 이름입니다. |
| password | 문자열 | 사용자 또는 소유자 비밀번호입니다. |

### 반환 값

문서 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

암호화된 문서 작업을 위한 [`Document`](../../document/) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | 문자열 | 문서 파일 이름입니다. |
| password | 문자열 | 사용자 또는 소유자 비밀번호입니다. |
| isManagedStream | 부울 | `true`로 설정하면 종료 전에 내부 스트림이 닫힙니다. 그렇지 않으면 닫히지 않습니다. |

### 반환 값

문서 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

필요한 변환 옵션을 제공하여 파일에서 기존 문서를 엽니다. PDF 문서를 얻기 위해.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filename | 문자열 | PDF 문서로 변환할 입력 파일입니다. |
| options | LoadOptions | *filename*을 PDF 문서로 변환하기 위한 속성을 나타냅니다. |

### 반환 값

문서 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [LoadOptions](../../loadoptions/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)