---
title: "System::MakeObject método"
linktitle: "CrearObjeto"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MakeObject método. Crea un objeto en el heap y devuelve un puntero compartido a él en C++."
type: docs
weight: 25300
url: /es/cpp/system/makeobject/
---
## System::MakeObject(Args\&&...) method


Crea un objeto en el heap y devuelve un puntero compartido a él.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


| Parámetro | Descripción |
| --- | --- |
| T | Clase para instanciar. |
| Args | Tipos de los argumentos del constructor. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos del constructor. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeObject(Args\&&...) method


Crea un objeto en el heap y devuelve un puntero compartido a él.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


| Parámetro | Descripción |
| --- | --- |
| T | [SmartPtr](../smartptr/) a la clase para instanciar. |
| Args | Tipos de los argumentos del constructor. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | Args\&&... | Argumentos del constructor. |

### ReturnValue

[SmartPtr](../smartptr/) to newly created object, always in shared mode.

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
