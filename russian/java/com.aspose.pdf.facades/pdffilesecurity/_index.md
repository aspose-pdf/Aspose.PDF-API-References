---
title: PdfFileSecurity
second_title: Aspose.PDF для справки по Java API
description: Представляет шифрование или расшифровку файла Pdf с использованием пароля владельца или пользователя, изменяющего параметр безопасности и пароль.
type: docs
weight: 44
url: /ru/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable
```
public final class PdfFileSecurity extends SaveableFacade implements System.IDisposable
```

Представляет собой шифрование или расшифровку файла Pdf с использованием пароля владельца или пользователя, изменение параметра безопасности и пароля.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileSecurity(InputStream inputStream, OutputStream outputStream)](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Инициализируйте объект PdfFileSecurity с потоком ввода и вывода. |
| [PdfFileSecurity(String inputFile, String outputFile)](#PdfFileSecurity-java.lang.String-java.lang.String-) | Инициализирует объект PdfFileSecurity входным и выходным файлом. |
| [PdfFileSecurity()](#PdfFileSecurity--) | Инициализируйте объект PdfFileSecurity. |
| [PdfFileSecurity(IDocument document)](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfFileSecurity на основе документа. |
| [PdfFileSecurity(IDocument document, String outputFile)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект PdfFileSecurity на основе документа. |
| [PdfFileSecurity(IDocument document, OutputStream outputStream)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Инициализирует новый объект PdfFileSecurity на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Изменяет пароль пользователя и пароль владельца на пароль владельца, сохраняя исходные настройки безопасности. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. |
| [close()](#close--) | Закрывает фасад. |
| [decryptFile(String ownerPassword)](#decryptFile-java.lang.String-) | Расшифровывает зашифрованный документ Pdf по паролю владельца. |
| [dispose()](#dispose--) | Закрывает фасад. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowExceptions()](#getAllowExceptions--) | Если для этого значения установлено значение true, при сбое операции будет выдано исключение. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getLastException()](#getLastException--) | Возвращает исключение, сгенерированное последней операцией. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [setAllowExceptions(boolean value)](#setAllowExceptions-boolean-) | Если для этого значения установлено значение true, при сбое операции будет выдано исключение. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Устанавливает входной файл. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Устанавливает входной поток. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Устанавливает выходной файл. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Устанавливает выходной поток. |
| [setPrivilege(DocumentPrivilege privilege)](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. |
| [setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Устанавливает безопасность файла Pdf с исходным паролем. |
| [toString()](#toString--) |  |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Изменяет пароль пользователя и пароль владельца на пароль владельца, сохраняя исходные настройки безопасности. |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. |
| [tryDecryptFile(String ownerPassword)](#tryDecryptFile-java.lang.String-) | Расшифровывает зашифрованный документ Pdf по паролю владельца. |
| [tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. |
| [trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Устанавливает безопасность файла Pdf с исходным паролем. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSecurity(InputStream inputStream, OutputStream outputStream) {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileSecurity(InputStream inputStream, OutputStream outputStream)
```


Инициализируйте объект PdfFileSecurity с потоком ввода и вывода.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

### PdfFileSecurity(String inputFile, String outputFile) {#PdfFileSecurity-java.lang.String-java.lang.String-}
```
public PdfFileSecurity(String inputFile, String outputFile)
```


Инициализирует объект PdfFileSecurity входным и выходным файлом.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Исходный входной файл Pdf. |
| outputFile | java.lang.String | Выходной PDF-файл. |

### PdfFileSecurity() {#PdfFileSecurity--}
```
public PdfFileSecurity()
```


Инициализируйте объект PdfFileSecurity.

### PdfFileSecurity(IDocument document) {#PdfFileSecurity-com.aspose.pdf.IDocument-}
```
public PdfFileSecurity(IDocument document)
```


Инициализирует новый объект PdfFileSecurity на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### PdfFileSecurity(IDocument document, String outputFile) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSecurity(IDocument document, String outputFile)
```


Инициализирует новый объект PdfFileSecurity на основе документа.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputFile | java.lang.String | Выходной PDF-файл. |

### PdfFileSecurity(IDocument document, OutputStream outputStream) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public PdfFileSecurity(IDocument document, OutputStream outputStream)
```


Инициализирует новый объект PdfFileSecurity на основе документа.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

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

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

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

### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public final boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Изменяет пароль пользователя и пароль владельца на пароль владельца, сохраняя исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца недействителен или пуст. Выдает исключение, если процесс завершился неудачно.

```
string inFile = "D:\\input.pdf"; //TestPath может быть переназначен.
  string outFile = "D:\\output.pdf";	//TestPath может быть переназначен.
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  fileSecurity.changePassword("owner","newuser","newowner");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |

**Возвращает:**
boolean - True для успеха.
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца недействителен или пуст. Выдает исключение, если процесс завершился неудачно.

--------------------

```
string inFile = "input.pdf"; // TestPath может быть
 														// переназначен.
 string outFile = "output.pdf"; // TestPath может быть
 															// переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Сбросить безопасность. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

**Возвращает:**
boolean - True для успеха.
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца недействителен или пуст. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и если комплект встретит эту комбинацию, будет возбуждено соответствующее исключение. Выдает исключение, если процесс завершился неудачно.

--------------------

```
string inFile = "input.pdf"; // TestPath может быть
 														// переназначен.
 string outFile = "output.pdf"; // TestPath может быть
 															// переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256, Algorithm.AES);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Сбросить безопасность. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |
| cipher | int | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

**Возвращает:**
boolean - True для успеха.
### close() {#close--}
```
public void close()
```


Закрывает фасад.

### decryptFile(String ownerPassword) {#decryptFile-java.lang.String-}
```
public final boolean decryptFile(String ownerPassword)
```


Расшифровывает зашифрованный документ Pdf по паролю владельца. Если документ не имеет пароля владельца, можно использовать пароль пользователя. Выдает исключение, если процесс завершился неудачно.

```
string inFile = "input.pdf"; //TestPath может быть переназначен.
 string outFile = "output.pdf"; //TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 fileSecurity.decryptFile("ownerpass");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Пароль владельца. |

**Возвращает:**
boolean - True для успеха.
### dispose() {#dispose--}
```
public void dispose()
```


Закрывает фасад.

### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Выдает исключение, если процесс завершился неудачно.

--------------------

```
String inFile = "input.pdf"; // TestPath может быть
 															// переназначен.
 String outFile = "output.pdf"; // TestPath может быть
 															// переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

**Возвращает:**
boolean - True для успеха.
### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и если комплект встретит эту комбинацию, будет возбуждено соответствующее исключение. Выдает исключение, если процесс завершился неудачно.

--------------------

```
String inFile = "input.pdf"; // TestPath может быть
 															// переназначен.
 String outFile = "output.pdf"; // TestPath может быть
 															// переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256, Algorithm.AES);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |
| cipher | int | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

**Возвращает:**
boolean - True для успеха или false.
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
### getAllowExceptions() {#getAllowExceptions--}
```
public final boolean getAllowExceptions()
```


Если для этого значения установлено значение true, при сбое операции будет выдано исключение. В противном случае метод возвращает false в случае сбоя, и последнее исключение можно проверить с помощью свойства LastException.

**Возвращает:**
boolean - логическое значение
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
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


Возвращает исключение, сгенерированное последней операцией.

**Возвращает:**
java.lang.RuntimeException — java.lang.RuntimeException
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




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Целевой поток. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл назначения. |

### setAllowExceptions(boolean value) {#setAllowExceptions-boolean-}
```
public final void setAllowExceptions(boolean value)
```


Если для этого значения установлено значение true, при сбое операции будет выдано исключение. В противном случае метод возвращает false в случае сбоя, и последнее исключение можно проверить с помощью свойства LastException.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


Устанавливает входной файл.

Obsolete("Используйте метод bindPdf(inputStream) для инициализации фасада.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Устанавливает входной поток.

Obsolete("Используйте метод bindPdf(inputStream) для инициализации фасада.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Устанавливает выходной файл.

Obsolete("Используйте метод save(outputStream) для получения фасадных результатов.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


Устанавливает выходной поток.

Obsolete("Используйте метод save(outputStream) для получения фасадных результатов.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setPrivilege(DocumentPrivilege privilege) {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(DocumentPrivilege privilege)
```


Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выдает исключение, если процесс завершился неудачно.

--------------------

```
string inFile = "input.pdf"; // TestPath может быть переназначен.
 string outFile = "output.pdf"; // TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(DocumentPrivilege.Print);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |

**Возвращает:**
boolean - True для успеха.
### setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


Устанавливает безопасность файла Pdf с исходным паролем. Выдает исключение, если процесс завершился неудачно.

--------------------

```
string inFile = "input.pdf"; // TestPath может быть переназначен.
 string outFile = "output.pdf"; // TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Оригинальный пароль пользователя. |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |

**Возвращает:**
boolean - True для успеха.
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Изменяет пароль пользователя и пароль владельца на пароль владельца, сохраняя исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен. Не генерирует исключение в случае сбоя процесса. со случайной строкой, если пароль нового владельца нулевой или пустой.

```
string inFile = "D:\\input.pdf"; //TestPath может быть переназначен.
  string outFile = "D:\\output.pdf";	//TestPath может быть переназначен.
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |

**Возвращает:**
boolean - True для успеха или false.
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца недействителен или пуст. Не генерирует исключение, если процесс завершился неудачно.

```
string inFile = ".D:\\input.pdf"; //TestPath может быть переназначен.
 string outFile = "D:\\output.pdf";	//TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Сбросить безопасность. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

**Возвращает:**
boolean - True для успеха или false.
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца недействителен или пуст. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и если комплект встретит эту комбинацию, будет возбуждено соответствующее исключение. Не генерирует исключение, если процесс завершился неудачно.

```
string inFile = "D:\\input.pdf"; //TestPath может быть переназначен.
 string outFile = "D:\\output.pdf";	//TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| newUserPassword | java.lang.String | Новый пароль пользователя. |
| newOwnerPassword | java.lang.String | Новый пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Сбросить безопасность. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |
| cipher | int | Algorithm.AES для шифрования с использованием алгоритма AES или Algorithm.RC4 для шифрования RC4. |

**Возвращает:**
boolean - True для успеха или false.
### tryDecryptFile(String ownerPassword) {#tryDecryptFile-java.lang.String-}
```
public final boolean tryDecryptFile(String ownerPassword)
```


Расшифровывает зашифрованный документ Pdf по паролю владельца. Если документ не имеет пароля владельца, можно использовать пароль пользователя. Не генерирует исключение, если процесс завершился неудачно.

```
string inFile = "input.pdf"; //TestPath может быть переназначен.
 string outFile = "output.pdf"; //TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.TryDecryptFile("ownerpass");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ownerPassword | java.lang.String | Пароль владельца. |

**Возвращает:**
boolean - True для успеха или false.
### tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


Шифрует файл Pdf с помощью пароля пользователя и пароля владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Не генерирует исключение, если процесс завершился неудачно.

```
string inFile = "input.pdf"; //TestPath может быть переназначен.
 string outFile = "output.pdf"; //TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Пользовательский пароль. |
| ownerPassword | java.lang.String | Пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |
| keySize | int | KeySize.x40 для 40-битного шифрования, KeySize.x128 для 128-битного шифрования и KeySize.x256 для 256-битного шифрования. |

**Возвращает:**
boolean - True для успеха или false.
### trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public final boolean trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


Устанавливает безопасность файла Pdf с исходным паролем. Не генерирует исключение, если процесс завершился неудачно.

```
string inFile = "D:\\input.pdf"; //TestPath может быть переназначен.
 string outFile = "D:\\output.pdf"; //TestPath может быть переназначен.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | java.lang.String | Оригинальный пароль пользователя. |
| ownerPassword | java.lang.String | Оригинальный пароль владельца. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Установить привилегию. |

**Возвращает:**
boolean - True для успеха или false.
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
