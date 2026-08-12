---
title: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method"
linktitle: "VerifyData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::DSACryptoServiceProvider::VerifyData method. Verifica la firma de los datos en C++."
type: docs
weight: 1700
url: /es/cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Comprueba la firma de los datos.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const ByteArrayPtr\& | [Data](../../../system.data/) para verificar la firma. |
| firma | const ByteArrayPtr\& | Firma tal como se recibió. |

### ReturnValue

Verdadero si la firma es válida, falso en caso contrario.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Datos firmados. |
| firma | const ByteArrayPtr\& | Datos de la firma. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifica que la firma de los datos especificados sea válida.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Datos firmados. |
| desplazamiento | int32_t | Desplazamiento en **data**. |
| count | int32_t | Número de bytes para hash. |
| firma | const ByteArrayPtr\& | Datos de la firma. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifica que la firma del flujo binario especificado sea válida.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const StreamPtr\& | Datos firmados. |
| firma | const ByteArrayPtr\& | Datos de la firma. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo de hash. devuelve true si la firma es válida, de lo contrario - false. |

## Ver también

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
