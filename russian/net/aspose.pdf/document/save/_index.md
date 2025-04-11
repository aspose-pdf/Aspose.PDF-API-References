---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Метод документа. Сохраняет документ в поток
type: docs
weight: 830
url: /ru/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

Сохраняет документ в поток.

```csharp
public void Save(Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | Stream | Поток, в который будет сохранен документ. |

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

Сохраняет документ в указанный файл.

```csharp
public void Save(string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save() {#save}

Сохраняет документ инкрементально (т.е. с использованием техники инкрементального обновления).

```csharp
public void Save()
```

## Замечания

Для того чтобы сохранить документ инкрементально, мы должны открыть файл документа для записи. Поэтому Document должен быть инициализирован с помощью записываемого потока, как в следующем фрагменте кода: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // внесите изменения и сохраните документ инкрементально doc.Save();

### См. также

* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

Сохраняет документ с параметрами сохранения.

```csharp
public void Save(SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Параметры сохранения. |

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

Сохраняет документ с новым именем и форматом файла.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |
| format | SaveFormat | Параметры формата. |

### См. также

* enum [SaveFormat](../../saveformat/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

Сохраняет документ с новым именем и форматом файла.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будет сохранен документ. |
| format | SaveFormat | Параметры формата. |

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

## Save(string, SaveOptions) {#save_7}

Сохраняет документ с новым именем, устанавливая его параметры сохранения.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFileName | String | Путь к файлу, в который будет сохранен документ. |
| options | SaveOptions | Параметры сохранения. |

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

Сохраняет документ в поток с параметрами сохранения.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток, в который будет сохранен документ. |
| options | SaveOptions | Параметры сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | ArgumentException, когда [`HtmlSaveOptions`](../../htmlsaveoptions/) передан в метод. Сохранение документа в html поток не поддерживается. Пожалуйста, используйте метод сохранения в файл. |

### См. также

* класс [SaveOptions](../../saveoptions/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)