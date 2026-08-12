---
title: "Método HashData de System::Security::Cryptography::ECDsaBotan"
linktitle: "HashData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::ECDsaBotan::HashData method. Calcula el valor hash del arreglo de datos especificado usando el algoritmo hash especificado en C++."
type: docs
weight: 700
url: /es/cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Calcula el valor hash del arreglo de datos especificado usando el algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | ByteArrayPtr | [Data](../../../system.data/) para generar hash. |
| desplazamiento | int32_t | Desplazamiento en **data**. |
| count | int32_t | Número de bytes para hash. |
| hash_algorithm | HashAlgorithmName | Algoritmo de hash. |

### ReturnValue

Datos hash.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Calcula el valor hash del flujo binario especificado usando el algoritmo de hash especificado.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | StreamPtr | Flujo binario para hash. |
| hash_algorithm | HashAlgorithmName | Algoritmo de hash. |

### ReturnValue

Datos hash.

## Ver también

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
