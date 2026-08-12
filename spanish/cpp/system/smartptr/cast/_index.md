---
title: "Método System::SmartPtr::Cast"
linktitle: "Cast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::SmartPtr::Cast. Convierte el puntero a su propio tipo en C++."
type: docs
weight: 400
url: /es/cpp/system/smartptr/cast/
---
## SmartPtr::Cast() const method


Convierte el puntero a su propio tipo.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar una excepción si no hay conversión disponible. |

### ReturnValue

Puntero de tipo cambiado que siempre está en modo compartido.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Convierte el puntero al tipo base usando static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar una excepción si no hay conversión disponible. |

### ReturnValue

Puntero de tipo cambiado que siempre está en modo compartido.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Convierte el puntero al tipo derivado usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar una excepción si no hay conversión disponible. |

### ReturnValue

Puntero de tipo cambiado que siempre está en modo compartido. Lanza InvalidCastException si no hay conversión disponible.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Convierte el puntero al tipo derivado usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parámetro | Descripción |
| --- | --- |
| Y | Tipo objetivo del objeto apuntado. |
| Check | Indicadores para lanzar una excepción si no hay conversión disponible. |

### ReturnValue

Puntero de tipo cambiado que siempre está en modo compartido. Devuelve nullptr si no hay conversión disponible.

## Ver también

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
