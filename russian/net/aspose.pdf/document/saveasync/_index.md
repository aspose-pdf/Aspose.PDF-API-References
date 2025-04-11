---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод документа. Сохраняет документ в поток
type: docs
weight: 840
url: /ru/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

Сохраняет документ в поток.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | Stream | Поток, в который будет сохранен документ. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

Сохраняет документ в указанный файл.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

Сохраняет документ инкрементально (т.е. с использованием техники инкрементального обновления).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

## Примечания

Для того чтобы сохранить документ инкрементально, мы должны открыть файл документа для записи. Поэтому Document должен быть инициализирован с помощью записываемого потока, как в следующем фрагменте кода: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите изменения и сохраните документ инкрементально doc.Save();

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

Сохраняет документ с параметрами сохранения.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

Сохраняет документ с новым именем и форматом файла.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |
| format | SaveFormat | Параметры формата. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* enum [SaveFormat](../../saveformat/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

Сохраняет документ с новым именем и форматом файла.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будет сохранен документ. |
| format | SaveFormat | Параметры формата. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException, когда [`HtmlSaveOptions`](../../htmlsaveoptions/) передан в метод. Сохранение документа в html поток не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### См. также

* enum [SaveFormat](../../saveformat/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

Сохраняет документ с новым именем, устанавливая его параметры сохранения.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

Сохраняет документ в поток с параметрами сохранения.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будет сохранен документ. |
| options | SaveOptions | Параметры сохранения. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Асинхронная задача.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException, когда [`HtmlSaveOptions`](../../htmlsaveoptions/) передан в метод. Сохранение документа в html поток не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)