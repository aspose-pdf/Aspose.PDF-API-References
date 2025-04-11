---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Construtor ExternalSignature. Cria uma assinatura PKCS7 destacada usando um X509Certificate2. Suporta tokens de cartões inteligentes usb sem chaves privadas exportáveis
type: docs
weight: 10
url: /pt/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Cria uma assinatura PKCS#7 `(detached)` usando um X509Certificate2. Suporta cartões inteligentes usb, tokens sem chaves privadas exportáveis.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| certificate | X509Certificate2 | O certificado com a chave privada. |

## Observações

O algoritmo de digestão será selecionado automaticamente com base nos dados da chave do certificado.

### Veja Também

* classe [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Cria uma assinatura PKCS#7 `(detached)` usando um X509Certificate2. Suporta cartões inteligentes usb, tokens sem chaves privadas exportáveis.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| certificate | X509Certificate2 | O certificado com a chave privada. |
| digestHashAlgorithm | DigestHashAlgorithm | O algoritmo de digestão para assinar um documento. |

### Veja Também

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* classe [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Cria uma assinatura PKCS#7 usando um X509Certificate2. Suporta cartões inteligentes usb, tokens sem chaves privadas exportáveis.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| certificate | X509Certificate2 | O certificado com a chave privada. |
| detached | Boolean | Verdadeiro se a assinatura deve ser destacada, caso contrário, falso. |

## Observações

Para destacado definido como falso, o algoritmo de digestão será sempre `SHA1`. Caso contrário, o algoritmo de digestão será selecionado automaticamente com base nos dados da chave do certificado (veja Auto).

### Veja Também

* classe [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Cria uma assinatura PKCS#7 usando um X509Certificate2 como string base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| base64 | String | X509Certificate2 como string base64. |
| detached | Boolean | Verdadeiro se a assinatura deve ser destacada, caso contrário, falso. |

## Observações

Para destacado definido como falso, o algoritmo de digestão será sempre `SHA1`. Caso contrário, o algoritmo de digestão será selecionado automaticamente com base nos dados da chave do certificado (veja Auto).

### Veja Também

* classe [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Cria uma assinatura PKCS#7 `(detached)` usando um X509Certificate2 como string base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| base64 | String | X509Certificate2 como string base64. |
| digestHashAlgorithm | DigestHashAlgorithm | O algoritmo de digestão para assinar um documento. |

### Veja Também

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* classe [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)