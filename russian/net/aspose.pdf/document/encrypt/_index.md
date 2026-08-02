---
title: "Document.Encrypt"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Document method. Шифрует документ"
type: docs
weight: 640
url: /ru/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Шифрует документ.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| permissions | Permissions | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для подробностей. |
| publicCertificates | IList`1 | Публичные сертификаты, используемые для шифрования — по одному на получателя. |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Шифрует документ.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privileges | DocumentPrivilege | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| customHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Шифрует документ.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | Permissions | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| customHandler | ICustomSecurityHandler | Пользовательский обработчик безопасности. |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Шифрует документ.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| privileges | DocumentPrivilege | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для подробностей. |
| usePdf20 | Boolean | Поддержка ревизии 6 (расширение 8). |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Шифрует документ.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | Permissions | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для подробностей. |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Шифрует документ.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | Permissions | Document permissions, см. [`Permissions`](../permissions/) для подробностей. |
| cryptoAlgorithm | CryptoAlgorithm | Криптографический алгоритм, см. [`CryptoAlgorithm`](../cryptoalgorithm/) для подробностей. |
| usePdf20 | Boolean | Поддержка ревизии 6 (расширение 8). |

## Примечания

Этот метод подготавливает шифрование. Чтобы зашифровать документ, необходимо вызвать метод Save для его сохранения.

### См. также

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


