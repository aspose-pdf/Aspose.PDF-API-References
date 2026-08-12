---
title: "Método System::With"
linktitle: "With"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::With. Clona el registro de referencia y le aplica el functor inicializador en C++."
type: docs
weight: 44900
url: /es/cpp/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) method


Clona el registro de referencia y le aplica el functor inicializador.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de registro a clonar. |
| A | Tipo de functor de inicialización. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| registro | const SharedPtr\<T\>\& | Puntero compartido al objeto a clonar e inicializar. |
| inicializador | const A\& | Functor de inicialización aplicado al clon del registro. |

### ReturnValue

Puntero compartido al registro clonado.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::With(const T\&, const A\&) method


Copia el registro struct y le aplica el functor inicializador.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de registro a copiar. |
| A | Tipo de functor de inicialización. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| registro | const T\& | Registro a copiar e inicializar. |
| inicializador | const A\& | Functor de inicialización aplicado a la copia del registro. |

### ReturnValue

Registro copiado.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
