---
title: System::ExceptionWrapper class
linktitle: ExceptionWrapper
second_title: Aspose.PDF for C++ API Reference
description: 'System::ExceptionWrapper class. Template that represents wrapper of exceptions that are derived from Exception class in C++.'
type: docs
weight: 2600
url: /cpp/system/exceptionwrapper/
---
## ExceptionWrapper class


Template that represents wrapper of exceptions that are derived from [Exception](../exception/) class.

```cpp
template<typename T>class ExceptionWrapper
```

## Methods

| Method | Description |
| --- | --- |
| [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Constructs a null-instance of [ExceptionWrapper](./) class that does not represent any exception. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionPtr\&) | Constructs a instance of [ExceptionWrapper](./) class that contains passed pointer. |
| [ExceptionWrapper](./exceptionwrapper/)(const ExceptionWrapper\&) | Copy constructor. |
| [ExceptionWrapper](./exceptionwrapper/)(ExceptionWrapper\&&) | Move constructor. |
| explicit [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructor that forwards parameters to the [Exception](../exception/) class constructors and creates smart pointer that holds new [Exception](../exception/) class instance. |
| static [operator new](./operatornew/)(std::size_t) |  |
| static [operator new[]](./operatornew[]/)(std::size_t) |  |
| [operator SharedPtr< Object >](./operatorsharedptr_object_/)() | Implicit cast operator to [SharedPtr<Object>](../sharedptr/) |
| [operator->](./operator-_/)() const | Allows to access members of the [Exception](../exception/) object. |
| [operator=](./operator=/)(const ExceptionWrapper\&) | Assignment operator. |
| [operator=](./operator=/)(ExceptionWrapper\&&) | Move assignment operator. |
| static [Type](./type/)() | Shortcut to get [System::TypeInfo](../typeinfo/) object for the [Exception](../exception/) type. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Used for casting functions. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
