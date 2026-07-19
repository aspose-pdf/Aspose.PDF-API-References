---
title: "Конструктор System::SmartPtr::SmartPtr"
linktitle: "SmartPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::SmartPtr::SmartPtr. Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# есть приведение типа массива, которое не поддерживается в C++."
type: docs
weight: 100
url: /ru/cpp/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# есть приведение типа массива, которое не поддерживается в C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Описание |
| --- | --- |
| Y | Тип исходного массива. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const SmartPtr\<Array\<Y\>\>\& | Указатель на массив, копию которого нужно создать, но с элементами другого типа. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Class [SmartPtr](../)
* Class [Array](../../array/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Создаёт [SmartPtr](../), который разделяет информацию о владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const SmartPtr\<P\>\& | Другой умный указатель для совместного владения с исходным указателем. |
| p | Pointee_ * | Указатель на объект для управления. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Class [SmartPtr](../)
* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Создаёт копию объекта [SmartPtr](../). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типа, если это разрешено.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Описание |
| --- | --- |
| Q | Тип объекта, на который указывает x. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Указатель для копирования. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Class [SmartPtr](../)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Создаёт копию объекта [SmartPtr](../). Оба указателя после этого указывают на один и тот же объект.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Указатель для копирования. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const Y\&) constructor


Инициализирует пустой массив. Используется для преобразования некоторых конструкций кода C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


| Параметр | Описание |
| --- | --- |
| Y | Заполнитель типа EmptyArrayInitializer. |

## См. также

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Создаёт [SmartPtr](../), указывающий на указанный объект, или преобразует необработанный указатель в [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | Pointee_ * | Pointee. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Перемещающая конструкция объекта [SmartPtr](../). По сути, меняет местами два указателя, если они находятся в одинаковом режиме. После вызова x может стать недоступным.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr_\&& | Указатель для перемещения. |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Создаёт объект [SmartPtr](../) требуемого режима.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | SmartPtrMode | Режим указателя. |

## См. также

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Создаёт объект [SmartPtr](../) с нулевым указателем требуемого режима.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| режим | std::nullptr_t | Режим указателя. |

## См. также

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
