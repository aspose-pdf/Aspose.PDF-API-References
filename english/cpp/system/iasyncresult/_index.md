---
title: System::IAsyncResult class
linktitle: IAsyncResult
second_title: Aspose.PDF for C++ API Reference
description: 'System::IAsyncResult class. Represents the status of asynchronous operation. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3100
url: /cpp/system/iasyncresult/
---
## IAsyncResult class


Represents the status of asynchronous operation. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IAsyncResult : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_AsyncState](./get_asyncstate/)() | Returns an object that contains the information about asyrchronous operation. |
| virtual [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Returns an instance of WaitHandle that can be used to wait for the completion of the asynchronous operation. |
| virtual [get_CompletedSynchronously](./get_completedsynchronously/)() | Returns a value that indicates whether the asynchronous operation completed synchronously. |
| virtual [get_IsCompleted](./get_iscompleted/)() | Returns a value that indicates whether the asynchronous operation has completed. |
| virtual [~IAsyncResult](./~iasyncresult/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Shared pointer to [IAsyncResult](./). |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
