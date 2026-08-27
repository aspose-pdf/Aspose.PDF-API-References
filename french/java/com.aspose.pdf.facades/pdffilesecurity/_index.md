---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le chiffrement ou le déchiffrement d'un fichier PDF avec le mot de passe propriétaire ou utilisateur, ainsi que la modification des paramètres de sécurité et du mot de passe."
type: docs
weight: 520
url: /fr/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Représente le chiffrement ou le déchiffrement d'un fichier PDF avec le mot de passe propriétaire ou utilisateur, ainsi que la modification des paramètres de sécurité et du mot de passe.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Initialisez l'objet de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Initialisez l'objet de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initialisez l'objet de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Initialisez l'objet de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Initialisez l'objet de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Initialisez l'objet de PdfFileSecurity. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initialise la façade. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, en conservant les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Lance une exception si le processus échoue. string inFile = \"D:\\\\\\\\input.pdf\"; //Le TestPath peut être réassigné. string outFile = \"D:\\\\\\\\output.pdf\"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword(\"owner\",\"newuser\",\"newowner\"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. </p> <p> Lance une exception si le processus échoue. </p> <hr> <pre> string inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. string outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant, (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Lance une exception si le processus échoue. </p> <hr> <pre> string inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. string outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Ferme la façade. |
| [decryptFile](#decryptFile-java.lang.String-) | Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Lance une exception si le processus échoue. string inFile = \"input.pdf\"; //Le TestPath peut être réassigné. string outFile = \"output.pdf\"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\"); |
| [dispose](#dispose--) | Ferme la façade. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Lance une exception si le processus échoue. </p> <hr> <pre> String inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. String outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Crypte le fichier PDF avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et une exception correspondante sera levée si le kit rencontre cette combinaison. Lance une exception si le processus a échoué. </p> <hr> <pre> String inFile = "input.pdf"; // Le TestPath peut être // réassigné. String outFile = "output.pdf"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Si cette valeur est définie sur true, une exception sera levée en cas d'échec de l'opération. Sinon, la méthode renvoie false en cas d'échec et la dernière exception peut être vérifiée avec la propriété LastException. |
| [getLastException](#getLastException--) | Renvoie l'exception qui a été levée par la dernière opération. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Si cette valeur est définie sur true, une exception sera levée en cas d'échec de l'opération. Sinon, la méthode renvoie false en cas d'échec et la dernière exception peut être vérifiée avec la propriété LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Définit le fichier d'entrée. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Définit le flux d'entrée. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Définit le fichier de sortie. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Définit le flux de sortie. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Définit la sécurité du fichier PDF avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté par une chaîne aléatoire. Lance une exception si le processus a échoué. </p> <hr> <pre> string inFile = "input.pdf"; // Le TestPath peut être réassigné. string outFile = "output.pdf"; // Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Définit la sécurité du fichier PDF avec le mot de passe original. Lance une exception si le processus a échoué. </p> <hr> <pre> string inFile = "input.pdf"; // Le TestPath peut être réassigné. string outFile = "output.pdf"; // Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Modifie le mot de passe utilisateur et le mot de passe propriétaire à l'aide du mot de passe propriétaire, en conservant les paramètres de sécurité originaux. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lance pas d'exception si le processus échoue. string inFile = "D:\\\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Modifie le mot de passe utilisateur et le mot de passe à l'aide du mot de passe propriétaire, permettant de réinitialiser la sécurité du document PDF. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lance pas d'exception si le processus échoue. string inFile = ".D:\\\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles des valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus échoue. string inFile = "D:\\\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Décrypte un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est autorisé à utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus échoue. string inFile = "input.pdf"; //Le TestPath peut être réassigné. string outFile = "output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Chiffre le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est null ou vide. Ne lève pas d'exception si le processus échoue. string inFile = "input.pdf"; //Le TestPath peut être réassigné. string outFile = "output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Définit la sécurité du fichier Pdf avec le mot de passe original. Ne lève pas d'exception si le processus échoue. string inFile = "D:\\\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Initialisez l'objet de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Initialisez l'objet de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Initialisez l'objet de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Initialisez l'objet de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Initialisez l'objet de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Initialisez l'objet de PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-}
Initialise la façade.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Modifie le mot de passe utilisateur et le mot de passe propriétaire avec le mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Lève une exception si le processus échoue. string inFile = "D:\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. </p> <p> Lance une exception si le processus échoue. </p> <hr> <pre> string inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. string outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Modifie le mot de passe utilisateur et le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant, (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Lance une exception si le processus échoue. </p> <hr> <pre> string inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. string outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Ferme la façade.

### decryptFile {#decryptFile-java.lang.String-}
Déchiffre un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est possible d'utiliser le mot de passe utilisateur. Lance une exception si le processus échoue. string inFile = \"input.pdf\"; //Le TestPath peut être réassigné. string outFile = \"output.pdf\"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\");

### dispose {#dispose--}
```
public void dispose()
```

Ferme la façade.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Crypte le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Lance une exception si le processus échoue. </p> <hr> <pre> String inFile = \"input.pdf\"; // Le TestPath peut être // réassigné. String outFile = \"output.pdf\"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Crypte le fichier PDF avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire fourni est null ou vide. Il existe 6 combinaisons possibles de valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et une exception correspondante sera levée si le kit rencontre cette combinaison. Lance une exception si le processus a échoué. </p> <hr> <pre> String inFile = "input.pdf"; // Le TestPath peut être // réassigné. String outFile = "output.pdf"; // Le TestPath peut être // réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Si cette valeur est définie sur true, une exception sera levée en cas d'échec de l'opération. Sinon, la méthode renvoie false en cas d'échec et la dernière exception peut être vérifiée avec la propriété LastException.

**Returns:**
valeur booléenne @deprecated Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Renvoie l'exception qui a été levée par la dernière opération.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Si cette valeur est définie sur true, une exception sera levée en cas d'échec de l'opération. Sinon, la méthode renvoie false en cas d'échec et la dernière exception peut être vérifiée avec la propriété LastException.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne @deprecated Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions. |

### setInputFile {#setInputFile-java.lang.String-}
Définit le fichier d'entrée. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Définit le flux d'entrée. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Définit le fichier de sortie. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Définit le flux de sortie. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Définit la sécurité du fichier PDF avec des mots de passe utilisateur/propriétaire vides. Le mot de passe propriétaire sera ajouté par une chaîne aléatoire. Lance une exception si le processus a échoué. </p> <hr> <pre> string inFile = "input.pdf"; // Le TestPath peut être réassigné. string outFile = "output.pdf"; // Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Définit la sécurité du fichier PDF avec le mot de passe original. Lance une exception si le processus a échoué. </p> <hr> <pre> string inFile = "input.pdf"; // Le TestPath peut être réassigné. string outFile = "output.pdf"; // Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Modifie le mot de passe utilisateur et le mot de passe propriétaire avec le mot de passe propriétaire, conserve les paramètres de sécurité d'origine. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue. string inFile = "D:\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Ne lève pas d'exception si le processus échoue. string inFile = ".D:\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Modifie le mot de passe utilisateur et le mot de passe par le mot de passe propriétaire, permet de réinitialiser la sécurité du document Pdf. Le nouveau mot de passe utilisateur et le nouveau mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le nouveau mot de passe propriétaire est null ou vide. Il existe 6 combinaisons possibles des valeurs KeySize et Algorithm. Cependant (KeySize.x40, Algorithm.AES) et (KeySize.x256, Algorithm.RC4) sont invalides et l'exception correspondante sera levée si le kit rencontre cette combinaison. Ne lève pas d'exception si le processus échoue. string inFile = "D:\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Décrypte un document Pdf chiffré avec le mot de passe propriétaire. Si le document n'a pas de mot de passe propriétaire, il est autorisé à utiliser le mot de passe utilisateur. Ne lève pas d'exception si le processus échoue. string inFile = "input.pdf"; //Le TestPath peut être réassigné. string outFile = "output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Chiffre le fichier Pdf avec le mot de passe utilisateur et le mot de passe propriétaire et définit les privilèges du document pour l'accès. Le mot de passe utilisateur et le mot de passe propriétaire peuvent être null ou vides. Le mot de passe propriétaire sera remplacé par une chaîne aléatoire si le mot de passe propriétaire d'entrée est null ou vide. Ne lève pas d'exception si le processus échoue. string inFile = "input.pdf"; //Le TestPath peut être réassigné. string outFile = "output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Définit la sécurité du fichier Pdf avec le mot de passe d'origine. Ne lève pas d'exception si le processus échoue. string inFile = "D:\\input.pdf"; //Le TestPath peut être réassigné. string outFile = "D:\\output.pdf"; //Le TestPath peut être réassigné. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
