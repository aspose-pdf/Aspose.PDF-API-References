---
title: "Método System::Nullable::operator-="
linktitle: "operator-="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::operator-=. Aplica operator-=() al valor representado por el objeto actual usando el valor representado por el objeto Nullable especificado como argumento del lado derecho en C++."
type: docs
weight: 1500
url: /es/cpp/system/nullable/operator-=/
---
## Nullable::operator-=(const Nullable\<T1\>\&) method


Aplica [operator-=()](./) al valor representado por el objeto actual usando el valor representado por el objeto [Nullable](../) especificado como argumento del lado derecho.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente de un objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho de [operator-=()](./) |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Una referencia constante a un objeto [Nullable](../) cuyo valor representado se usa como argumento del lado derecho del [operator-=()](./) aplicado al valor representado por el objeto actual. |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(const T1\&) method


Aplica [operator-=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo del valor usado como valor del lado derecho de [operator-=()](./) |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Una referencia constante al valor que se usa como valor del lado derecho del [operator-=()](./) aplicado al valor representado por el objeto actual. |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator-=(T1) method


Devuelve una instancia de la clase [Nullable](../) que representa un valor nulo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Ver también

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
