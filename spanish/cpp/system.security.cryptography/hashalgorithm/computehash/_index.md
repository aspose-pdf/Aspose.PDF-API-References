---
title: "System::Security::Cryptography::HashAlgorithm::ComputeHash method"
linktitle: "ComputeHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::HashAlgorithm::ComputeHash method. Genera el hash del búfer en C++."
type: docs
weight: 200
url: /es/cpp/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method


Búfer de hashes.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | Búfer de origen. |

### ReturnValue

Valor de hash calculado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method


Segmento del búfer de hashes.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | Búfer de origen. |
| desplazamiento | int | Desplazamiento en el búfer de origen. |
| count | int | Número de bytes a usar del búfer de origen. |

### ReturnValue

Valor de hash calculado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method


Lee el flujo hasta el final y calcula el hash de los datos leídos.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | SharedPtr\<IO::Stream\> const\& | Flujo para leer datos de. |

### ReturnValue

Valor de hash calculado para todos los datos del flujo.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
