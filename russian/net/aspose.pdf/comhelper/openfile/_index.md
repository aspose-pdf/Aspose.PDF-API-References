---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: Метод ComHelper. Просто создайте и верните документ, используя имя файла. То же самое, что и Document
type: docs
weight: 20
url: /ru/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Просто создайте и верните документ, используя *имя файла*. То же самое, что и [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла pdf документа. |

### Возвращаемое значение

Объект Document

### См. также

* класс [Document](../../document/)
* класс [ComHelper](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Инициализируйте и верните новый экземпляр класса [`Document`](../../document/) для работы с зашифрованным документом.

```csharp
public Document OpenFile(string filename, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла документа. |
| password | String | Пароль пользователя или владельца. |

### Возвращаемое значение

Объект Document

### См. также

* класс [Document](../../document/)
* класс [ComHelper](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Инициализируйте новый экземпляр класса [`Document`](../../document/) для работы с зашифрованным документом.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Имя файла документа. |
| password | String | Пароль пользователя или владельца. |
| isManagedStream | Boolean | если установлено в `true`, внутренний поток закрывается перед выходом; в противном случае - нет. |

### Возвращаемое значение

Объект Document

### См. также

* класс [Document](../../document/)
* класс [ComHelper](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Откройте существующий документ из файла, предоставив необходимые параметры преобразования для получения pdf документа.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | String | Входной файл для преобразования в pdf документ. |
| options | LoadOptions | Представляет свойства для преобразования *имя файла* в pdf документ. |

### Возвращаемое значение

Объект Document

### См. также

* класс [Document](../../document/)
* класс [LoadOptions](../../loadoptions/)
* класс [ComHelper](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)