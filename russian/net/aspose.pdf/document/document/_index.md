---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: Конструктор документа. Инициализируйте новый экземпляр документа из входного потока
type: docs
weight: 10
url: /ru/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

Инициализируйте новый экземпляр документа из *входного* потока.

```csharp
public Document(Stream input)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | Stream | Поток с pdf документом. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

Инициализируйте новый экземпляр документа из *входного* потока.

```csharp
public Document(Stream input, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | Stream | Поток с pdf документом. |
| isManagedStream | Boolean | Если установлено в `true`, внутренний поток закрывается перед выходом; в противном случае - нет. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

Инициализируйте новый экземпляр документа из *входного* потока.

```csharp
public Document(Stream input, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | Stream | Объект входного потока, соответствующий pdf, защищен паролем. |
| password | String | Пароль пользователя или владельца. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

Инициализируйте новый экземпляр документа из *входного* потока.

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | Stream | Поток с pdf документом. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | Если установлено в `true`, внутренний поток закрывается перед выходом; в противном случае - нет. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

Просто инициализируйте Document, используя *имя файла*. То же самое, что и `Document`.

```csharp
public Document(string filename)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла pdf документа. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

Просто инициализируйте Document, используя *имя файла*. То же самое, что и `Document`.

```csharp
public Document(string filename, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла pdf документа. |
| isManagedStream | Boolean | Если установлено в `true`, внутренний поток закрывается перед выходом; в противном случае - нет. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла документа. |
| password | String | Пароль пользователя или владельца. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

Инициализирует новый экземпляр класса [`Document`](../) для работы с зашифрованным документом.

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла документа. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | Если установлено в `true`, внутренний поток закрывается перед выходом; в противном случае - нет. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

Инициализирует пустой документ.

```csharp
public Document()
```

### See Also

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
| version | PdfVersion | Версия PDF. |

### See Also

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

Открывает существующий документ из файла, предоставляя необходимые параметры конвертации для получения pdf документа.

```csharp
public Document(string filename, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Входной файл для конвертации в pdf документ. |
| options | LoadOptions | Представляет свойства для конвертации *filename* в pdf документ. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

Открывает существующий документ из потока, предоставляя необходимые параметры конвертации для получения pdf документа.

```csharp
public Document(Stream input, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | Stream | Входной поток для конвертации в pdf документ. |
| options | LoadOptions | Представляет свойства для конвертации *input* в pdf документ. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)