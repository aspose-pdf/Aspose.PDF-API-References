---
title: "DocumentDevice.Process"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод DocumentDevice. Каждый устройство представляет некоторую операцию над document, например, мы можем преобразовать pdf document в другой формат"
type: docs
weight: 10
url: /ru/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Каждое устройство представляет некоторую операцию над document, например, мы можем преобразовать pdf document в другой формат.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Document для обработки. |
| fromPage | Int32 | Определяет Page, с которой начинать обработку. |
| toPage | Int32 | Определяет последнюю Page для обработки. |
| output | Stream | Определяет поток, в котором сохраняются результаты обработки. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Обрабатывает весь документ и сохраняет результаты в поток.

```csharp
public void Process(Document document, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Document для обработки. |
| output | Stream | Определяет поток, в котором сохраняются результаты обработки. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Обрабатывает весь документ и сохраняет результаты в файл.

```csharp
public void Process(Document document, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Document для обработки. |
| outputFileName | String | Определяет файл, в котором сохраняются результаты обработки. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Обрабатывает определённые страницы документа и сохраняет результаты в файл.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Document | Document для обработки. |
| fromPage | Int32 | Первая Page для начала обработки. |
| toPage | Int32 | Последняя Page обработки. |
| outputFileName | String | Определяет файл, в котором сохраняются результаты обработки. |

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


