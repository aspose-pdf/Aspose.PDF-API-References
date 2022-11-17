---
title: PdfFileSanitization
second_title: Aspose.PDF для справки по Java API
description: Представляет API очистки и восстановления.
type: docs
weight: 43
url: /ru/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**Все реализованные интерфейсы:**
[com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery](../../com.aspose.pdf.engine.security.impl.signatures.sanitization/irecovery)
```
public final class PdfFileSanitization extends SaveableFacade implements IRecovery
```

Представляет API очистки и восстановления. Используйте его, если вы не можете создавать/открывать документы каким-либо другим способом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileSanitization()](#PdfFileSanitization--) | Инициализирует новый экземпляр. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(Document srcDoc)](#bindPdf-com.aspose.pdf.Document-) | Инициализирует фасад. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Связывает поток PDF для Sanitize. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Связывает файл PDF для Sanitize. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает фасад. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getLog()](#getLog--) | После сохранения файла вы можете проверить, что было сделано с файлом. |
| [getUseRebuildXrefAndTrailer()](#getUseRebuildXrefAndTrailer--) | Позволяет генерировать новую внешнюю ссылку и трейлер для документа. |
| [getUseTrimBottom()](#getUseTrimBottom--) | Позволяет удалять данные после данных pdf |
| [getUseTrimTop()](#getUseTrimTop--) | Позволяет удалить данные перед данными PDF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rebuildXrefAndTrailer()](#rebuildXrefAndTrailer--) | Удаляет старую внешнюю ссылку с трейлером и создает новую внешнюю ссылку с трейлером. |
| [recover()](#recover--) | Восстанавливает документ. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет полученный PDF-файл в потоковом режиме. |
| [save(String outputFile)](#save-java.lang.String-) | Сохраняет результат PDF в файл. |
| [setUseRebuildXrefAndTrailer(boolean value)](#setUseRebuildXrefAndTrailer-boolean-) | Позволяет генерировать новую внешнюю ссылку и трейлер для документа. |
| [setUseTrimBottom(boolean value)](#setUseTrimBottom-boolean-) | Позволяет удалять данные после данных pdf |
| [setUseTrimTop(boolean value)](#setUseTrimTop-boolean-) | Позволяет удалить данные перед данными PDF. |
| [toString()](#toString--) |  |
| [trimBottom()](#trimBottom--) | Удаляет данные после последнего %%EOF. |
| [trimTop()](#trimTop--) | Удаляет данные перед %PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSanitization() {#PdfFileSanitization--}
```
public PdfFileSanitization()
```


Инициализирует новый экземпляр.

### bindPdf(Document srcDoc) {#bindPdf-com.aspose.pdf.Document-}
```
public void bindPdf(Document srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [Document](../../com.aspose.pdf/document) | Объект Документ. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Связывает поток PDF для Sanitize.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF для редактирования. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Связывает файл PDF для Sanitize.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | PDF-файл для редактирования. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Закрывает фасад.

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getLog() {#getLog--}
```
public final List<String> getLog()
```


После сохранения файла вы можете проверить, что было сделано с файлом.

**Возвращает:**
java.util.List<java.lang.String> — список элементов String
### getUseRebuildXrefAndTrailer() {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```


Позволяет генерировать новую внешнюю ссылку и трейлер для документа.

**Возвращает:**
boolean - логическое значение
### getUseTrimBottom() {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```


Позволяет удалять данные после данных pdf

**Возвращает:**
boolean - логическое значение
### getUseTrimTop() {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```


Позволяет удалить данные перед данными PDF.

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rebuildXrefAndTrailer() {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```


Удаляет старую внешнюю ссылку с трейлером и создает новую внешнюю ссылку с трейлером.

### recover() {#recover--}
```
public final void recover()
```


Восстанавливает документ. Используйте свойства для настройки.

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет полученный PDF-файл в потоковом режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | выходной pdf-поток |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Сохраняет результат PDF в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | выходной pdf-файл |

### setUseRebuildXrefAndTrailer(boolean value) {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```


Позволяет генерировать новую внешнюю ссылку и трейлер для документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUseTrimBottom(boolean value) {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```


Позволяет удалять данные после данных pdf

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUseTrimTop(boolean value) {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```


Позволяет удалить данные перед данными PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### trimBottom() {#trimBottom--}
```
public final void trimBottom()
```


Удаляет данные после последнего %%EOF.

### trimTop() {#trimTop--}
```
public final void trimTop()
```


Удаляет данные перед %PDF.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
