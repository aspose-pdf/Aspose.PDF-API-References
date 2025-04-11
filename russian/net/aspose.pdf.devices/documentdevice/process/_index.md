---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Метод DocumentDevice. Каждое устройство представляет собой некоторую операцию с документом, например, мы можем конвертировать pdf документ в другой формат
type: docs
weight: 10
url: /ru/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Каждое устройство представляет собой некоторую операцию с документом, например, мы можем конвертировать pdf документ в другой формат.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ для обработки. |
| fromPage | Int32 | Определяет страницу, с которой начинается обработка. |
| toPage | Int32 | Определяет последнюю страницу для обработки. |
| output | Stream | Определяет поток, в котором хранятся результаты обработки. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [DocumentDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Обрабатывает весь документ и сохраняет результаты в поток.

```csharp
public void Process(Document document, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ для обработки. |
| output | Stream | Определяет поток, в котором хранятся результаты обработки. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [DocumentDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Обрабатывает весь документ и сохраняет результаты в файл.

```csharp
public void Process(Document document, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ для обработки. |
| outputFileName | String | Определяет файл, в котором хранятся результаты обработки. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [DocumentDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Обрабатывает определенные страницы документа и сохраняет результаты в файл.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ для обработки. |
| fromPage | Int32 | Первая страница для начала обработки. |
| toPage | Int32 | Последняя страница обработки. |
| outputFileName | String | Определяет файл, в котором хранятся результаты обработки. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [DocumentDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)