---
title: "System::Security::Cryptography::ECDsa::SignData método"
linktitle: "SignData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::ECDsa::SignData método. Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado en C++."
type: docs
weight: 700
url: /es/cpp/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Arreglo de datos de entrada. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo hash. Devuelve la firma ECDSA para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado, y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | const ByteArrayPtr\& | Arreglo de datos de entrada. |
| desplazamiento | int32_t | Desplazamiento en **data**. |
| count | int32_t | Número de bytes a usar como datos de entrada. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo hash. Devuelve la firma ECDSA para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Calcula el valor hash del flujo binario especificado usando el algoritmo hash especificado, y firma el resultado.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | const StreamPtr\& | Flujo binario. |
| hash_algorithm | const HashAlgorithmName\& | Algoritmo hash. Devuelve la firma ECDSA para los datos de entrada. |

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
