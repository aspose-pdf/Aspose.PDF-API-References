---
title: "Document.Document"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор Document. Инициализирует новый экземпляр Document из входного потока"
type: docs
weight: 10
url: /ru/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Поток с pdf‑документом. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Поток с pdf‑документом. |
| isManagedStream | Boolean | если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Объект входного потока, соответствующий pdf защищён паролем. |
| password | String | Пароль пользователя или владельца. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Объект входного потока, соответствующий pdf защищён паролем. |
| certOptions | CertificateEncryptionOptions | Параметры шифрования сертификата. |

### См. также

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Поток с pdf‑документом. |
| certOptions | CertificateEncryptionOptions | Параметры шифрования сертификата. |
| isManagedStream | Boolean | Если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| certOptions | CertificateEncryptionOptions | Параметры шифрования сертификата. |

### См. также

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| certOptions | CertificateEncryptionOptions | Параметры шифрования сертификата. |
| isManagedStream | Boolean | если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Объект входного потока, соответствующий pdf защищён паролем. |
| password | String | Пароль пользователя или владельца. |
| customSecurityHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

### См. также

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Поток с pdf‑документом. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | Если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

Инициализирует новый экземпляр Document из *input* потока.

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Поток с pdf‑документом. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | Если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |
| customSecurityHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

### См. также

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

Просто инициализируйте Document, используя *filename*. То же самое, что `Document`.

```csharp
public Document(string filename)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла pdf‑документа. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

Просто инициализируйте Document, используя *filename*. То же самое, что `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла pdf‑документа. |
| isManagedStream | Boolean | Если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |
| customSecurityHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

### См. также

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Имя файла Document. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | если установлено `true`, внутренний поток закрывается перед выходом; иначе — нет. |
| customSecurityHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

### См. также

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Инициализирует пустой документ.

```csharp
public Document()
```

### См. также

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

Инициализирует пустой документ по версии.

```csharp
public Document(PdfVersion version)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| версия | PdfVersion | Версия PDF. |

### См. также

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

Открывает существующий документ из файла, предоставляя необходимые параметры преобразования для получения pdf‑документа.

```csharp
public Document(string filename, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имя файла | String | Входной файл для преобразования в pdf‑документ. |
| options | LoadOptions | Представляет свойства для преобразования *filename* в PDF‑документ. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Открывает существующий документ из потока, предоставляя необходимые преобразования для получения pdf‑документа.

```csharp
public Document(Stream input, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ввод | Stream | Входной поток для преобразования в pdf‑документ. |
| options | LoadOptions | Представляет свойства для преобразования *input* в pdf‑документ. |

### См. также

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


