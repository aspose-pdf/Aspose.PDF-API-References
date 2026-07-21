---
title: "Constructor System::Guid::Guid"
linktitle: "Guid"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::Guid::Guid. Construye un objeto que representa un GUID compuesto únicamente por ceros en C++."
type: docs
weight: 100
url: /es/cpp/system/guid/guid/
---
## Guid::Guid() constructor


Construye un objeto que representa un GUID compuesto únicamente de ceros.

```cpp
System::Guid::Guid()
```

## Ver también

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructor


Construye un objeto que representa un GUID especificado como una matriz de valores enteros sin signo de 8 bits.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| b | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes que contiene los bytes separados del GUID |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const Guid\&) constructor


Construye un objeto que representa el mismo GUID que el objeto especificado.

```cpp
System::Guid::Guid(const Guid &guid)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| guid | const Guid\& | El objeto [Guid](../) del cual copiar el valor GUID |

## Ver también

* Class [Guid](../)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const String\&) constructor


Construye un objeto que representa un GUID especificado como una cadena.

```cpp
System::Guid::Guid(const String &g)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g | const String\& | La representación de cadena de un GUID que será representada por el objeto que se está construyendo |

## Ver también

* Class [String](../../string/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructor


Construye un objeto que representa un GUID especificado como una vista de matriz de valores enteros sin signo de 8 bits.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| b | const System::Details::ArrayView\<uint8_t\>\& | Una matriz de bytes que contiene los bytes separados del GUID |

## Ver también

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructor


Construye una instancia de la clase [Guid](../) a partir de los componentes de GUID especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | int32_t | Bits 0-31 del GUID |
| b | int16_t | Bits 32-47 del GUID |
| c | int16_t | Bits 48-63 del GUID |
| d | const ArrayPtr\<uint8_t\>\& | Una matriz de bytes que contiene los bits 64-127 del GUID |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructor


Construye una instancia de la clase [Guid](../) a partir de los componentes de GUID especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | int32_t | Bits 0-31 del GUID |
| b | int16_t | Bits 32-47 del GUID |
| c | int16_t | Bits 48-63 del GUID |
| d | const System::Details::ArrayView\<uint8_t\>\& | Una vista de matriz de bytes que contiene los bits 64-127 del GUID |

## Ver también

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Construye una instancia de la clase [Guid](../) a partir de los enteros sin signo y bytes especificados.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | int32_t | Bits 0-31 del GUID |
| b | int16_t | Bits 32-47 del GUID |
| c | int16_t | Bits 48-63 del GUID |
| d | uint8_t | Bits 64-71 del GUID |
| e | uint8_t | Bits 72-79 del GUID |
| f | uint8_t | Bits 80-87 del GUID |
| g | uint8_t | Bits 88-95 del GUID |
| h | uint8_t | Bits 96-103 del GUID |
| i | uint8_t | Bits 104-111 del GUID |
| j | uint8_t | Bits 112-119 del GUID |
| k | uint8_t | Bits 120-127 del GUID |

## Ver también

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Construye una instancia de la clase [Guid](../) a partir de los enteros sin signo y bytes especificados.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | uint32_t | Bits 0-31 del GUID |
| b | uint16_t | Bits 32-47 del GUID |
| c | uint16_t | Bits 48-63 del GUID |
| d | uint8_t | Bits 64-71 del GUID |
| e | uint8_t | Bits 72-79 del GUID |
| f | uint8_t | Bits 80-87 del GUID |
| g | uint8_t | Bits 88-95 del GUID |
| h | uint8_t | Bits 96-103 del GUID |
| i | uint8_t | Bits 104-111 del GUID |
| j | uint8_t | Bits 112-119 del GUID |
| k | uint8_t | Bits 120-127 del GUID |

## Ver también

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
