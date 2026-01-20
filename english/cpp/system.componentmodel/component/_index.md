---
title: System::ComponentModel::Component class
linktitle: Component
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::Component class. Dummy class to make translated code using Component class compilable. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.componentmodel/component/
---
## Component class


Dummy class to make translated code using [Component](./) class compilable. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Component : public System::MarshalByRefObject,
                  public System::ComponentModel::IComponent
```

## Methods

| Method | Description |
| --- | --- |
| [Component](./component/)() | RTTI information. |
| [Dispose](./dispose/)(bool) | Disposable pattern support; does nothing. |
| [get_DesignMode](./get_designmode/)() | Checks if component is in design mode. |
## See Also

* Class [MarshalByRefObject](../../system/marshalbyrefobject/)
* Class [IComponent](../icomponent/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
