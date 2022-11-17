---
title: IFacade
second_title: Aspose.PDF для справки по Java API
description: Общий интерфейс фасада, который определяет общие методы фасадов.
type: docs
weight: 67
url: /ru/java/com.aspose.pdf.facades/ifacade/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IFacade extends System.IDisposable, Closeable
```

Общий интерфейс фасада, который определяет общие методы фасадов.
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Связывает PDF-документ для редактирования. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Связывает PDF-документ для редактирования. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Связывает PDF-документ для редактирования. |
| [close()](#close--) | Освобождает любые ресурсы, связанные с текущим фасадом. |
### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public abstract void bindPdf(IDocument srcDoc)
```


Связывает PDF-документ для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Введите PDF-документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public abstract void bindPdf(InputStream srcStream)
```


Связывает PDF-документ для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток входного PDF-документа. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public abstract void bindPdf(String srcFile)
```


Связывает PDF-документ для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | Путь входного документа PDF. |

### close() {#close--}
```
public abstract void close()
```


Освобождает любые ресурсы, связанные с текущим фасадом.
