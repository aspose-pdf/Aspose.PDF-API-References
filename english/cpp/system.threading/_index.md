---
title: System::Threading namespace
linktitle: System::Threading
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Threading namespace in C++.'
type: docs
weight: 7200
url: /cpp/system.threading/
---



## Classes

| Class | Description |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | [Event](../system/event/) to notify waiting thread that resets automatically. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [CancellationToken](./cancellationtoken/) | Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Represents a registration for a cancellation token callback. |
| [CancellationTokenSource](./cancellationtokensource/) | A cancellation token source that can be used to trigger cancellation notifications. |
| [EventWaitHandle](./eventwaithandle/) | [Event](../system/event/) that can be sent to waiting thread. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Interlocked](./interlocked/) | Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means. |
| [ManualResetEvent](./manualresetevent/) | [Event](../system/event/) to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Monitor](./monitor/) | Class [Monitor](./monitor/) provides a mechanism that synchronizes access to objects. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implemnetation. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementation. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SynchronizationContext](./synchronizationcontext/) | Provides the basic functionality for propagating a synchronization context across various synchronization operations. |
| [Thread](./thread/) | [Thread](./thread/) implementation. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool API allowing it pushing jobs into queue to be read by pool of worker threads. This is a static type with no instance services. You should never create instances of it by any means. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly. |
| [Timer](./timer/) | [Timer](./timer/) class that executes job item in separate thread after delay. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [TimerQueue](./timerqueue/) | Queue that handles [Timer](./timer/) objects. This is just an implementation. [Timer](./timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](./timer/) class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly. |
| [WaitHandle](./waithandle/) | Waiting primitive base class. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Enums

| Enum | Description |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Sets apartment state of the thread. |
| [EventResetMode](./eventresetmode/) | Indicates how event state resets. |
| [ThreadState](./threadstate/) | State of the thread. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) function with single parameter. |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ThreadStart](./threadstart/) | [Thread](./thread/) function with no parameters. |
| [TimerCallback](./timercallback/) | Callback function to be called by timer. |
| [wait_handle_t](./wait_handle_t/) | Handle type. |
| [WaitCallback](./waitcallback/) | Callback item to be executed once there is a spot. |
