---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el cifrado o descifrado de un archivo PDF con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña."
type: docs
weight: 520
url: /es/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Representa el cifrado o descifrado de un archivo PDF con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Inicializa el objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Inicializa el objeto de PdfFileSecurity. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | Inicializa la fachada. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, mantiene la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. </p> <p> Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // El TestPath puede ser // reasignado. string outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Hay 6 combinaciones posibles de los valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // El TestPath puede ser // reasignado. string outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Cierra la fachada. |
| [decryptFile](#decryptFile-java.lang.String-) | Desencripta un documento Pdf cifrado mediante la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. Lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Cierra la fachada. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Encripta un archivo Pdf con contraseña de usuario y contraseña de propietario y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Lanza una excepción si el proceso falla. </p> <hr> <pre> String inFile = "input.pdf"; // El TestPath puede ser // reasignado. String outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Encripta el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios del documento para acceder. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. </p> <hr> <pre> String inFile = "input.pdf"; // La ruta de prueba puede ser // reasignada. String outFile = "output.pdf"; // La ruta de prueba puede ser // reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de fallo y la última excepción se puede comprobar con la propiedad LastException. |
| [getLastException](#getLastException--) | Devuelve la excepción que fue lanzada por la última operación. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de fallo y la última excepción se puede comprobar con la propiedad LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Establece el archivo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Establece el flujo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Establece el archivo de salida. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Establece el flujo de salida. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña de propietario será añadida mediante una cadena aleatoria. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Establece la seguridad del archivo Pdf con la contraseña original. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Cambia la contraseña de usuario y la contraseña de propietario mediante la contraseña de propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "D:\\\\output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. No lanza una excepción si el proceso falla. string inFile = ".D:\\\\input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "D:\\\\output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. Hay 6 combinaciones posibles de los valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará la excepción correspondiente si el kit encuentra esta combinación. No lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Descifra un documento Pdf cifrado mediante la contraseña del propietario. Si el documento no tiene contraseña del propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Encripta un archivo Pdf con la contraseña de usuario y la contraseña del propietario y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la contraseña del propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Inicializa el objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Inicializa el objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Inicializa el objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Inicializa el objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Inicializa el objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Inicializa el objeto de PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-}
Inicializa la fachada.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Cambia la contraseña de usuario y la contraseña del propietario mediante la contraseña del propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. Lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. </p> <p> Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // El TestPath puede ser // reasignado. string outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Cambia la contraseña de usuario y la contraseña mediante la contraseña de propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la nueva contraseña de propietario es nula o vacía. Hay 6 combinaciones posibles de los valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // El TestPath puede ser // reasignado. string outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Cierra la fachada.

### decryptFile {#decryptFile-java.lang.String-}
Desencripta un documento Pdf cifrado mediante la contraseña de propietario. Si el documento no tiene contraseña de propietario, se permite usar la contraseña de usuario. Lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Cierra la fachada.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Encripta un archivo Pdf con contraseña de usuario y contraseña de propietario y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Lanza una excepción si el proceso falla. </p> <hr> <pre> String inFile = "input.pdf"; // El TestPath puede ser // reasignado. String outFile = "output.pdf"; // El TestPath puede ser // reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Encripta el archivo Pdf con la contraseña de usuario y la contraseña de propietario y establece los privilegios del documento para acceder. La contraseña de usuario y la contraseña de propietario pueden ser nulas o vacías. La contraseña de propietario será reemplazada por una cadena aleatoria si la contraseña de propietario de entrada es nula o vacía. Hay 6 combinaciones posibles de valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidos y se lanzará una excepción correspondiente si el kit encuentra esta combinación. Lanza una excepción si el proceso falla. </p> <hr> <pre> String inFile = "input.pdf"; // La ruta de prueba puede ser // reasignada. String outFile = "output.pdf"; // La ruta de prueba puede ser // reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de fallo y la última excepción se puede comprobar con la propiedad LastException.

**Returns:**
valor booleano @deprecated Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Devuelve la excepción que fue lanzada por la última operación.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Si este valor se establece en true, se lanzará una excepción al fallar la operación. De lo contrario, el método devuelve false en caso de fallo y la última excepción se puede comprobar con la propiedad LastException.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano @deprecated Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones. |

### setInputFile {#setInputFile-java.lang.String-}
Establece el archivo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Establece el flujo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Establece el archivo de salida. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Establece el flujo de salida. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Establece la seguridad del archivo Pdf con contraseñas de usuario/propietario vacías. La contraseña de propietario será añadida mediante una cadena aleatoria. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Establece la seguridad del archivo Pdf con la contraseña original. Lanza una excepción si el proceso falla. </p> <hr> <pre> string inFile = "input.pdf"; // La ruta de prueba puede ser reasignada. string outFile = "output.pdf"; // La ruta de prueba puede ser reasignada. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Cambia la contraseña de usuario y la contraseña del propietario mediante la contraseña del propietario, manteniendo la configuración de seguridad original. La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. No lanza una excepción si el proceso falla. string inFile = "D:\\\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. No lanza una excepción si el proceso falla. string inFile = ".D:\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Cambia la contraseña de usuario y la contraseña mediante la contraseña del propietario, permite restablecer la seguridad del documento Pdf. La nueva contraseña de usuario y la nueva contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la nueva contraseña del propietario es nula o vacía. Existen 6 combinaciones posibles de los valores de KeySize y Algorithm. Sin embargo, (KeySize.x40, Algorithm.AES) y (KeySize.x256, Algorithm.RC4) son inválidas y se lanzará una excepción correspondiente si el kit encuentra esta combinación. No lanza una excepción si el proceso falla. string inFile = "D:\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Descifra un documento Pdf cifrado mediante la contraseña del propietario. Si el documento no tiene contraseña del propietario, se permite usar la contraseña de usuario. No lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Encripta un archivo Pdf con la contraseña de usuario y la contraseña del propietario y establece los privilegios del documento para el acceso. La contraseña de usuario y la contraseña del propietario pueden ser nulas o vacías. La contraseña del propietario será reemplazada por una cadena aleatoria si la contraseña del propietario de entrada es nula o vacía. No lanza una excepción si el proceso falla. string inFile = "input.pdf"; //El TestPath puede ser reasignado. string outFile = "output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Establece la seguridad del archivo Pdf con la contraseña original. No lanza una excepción si el proceso falla. string inFile = "D:\\input.pdf"; //El TestPath puede ser reasignado. string outFile = "D:\\output.pdf"; //El TestPath puede ser reasignado. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
