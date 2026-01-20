---
title: System::Net::Security::AuthenticatedStream class
linktitle: AuthenticatedStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::AuthenticatedStream class. Contains the methods for passing credentials across a stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net.security/authenticatedstream/
---
## AuthenticatedStream class


Contains the methods for passing credentials across a stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_IsAuthenticated](./get_isauthenticated/)() const | Returns a value that indicates if authentication is successfully passed. |
| virtual [get_IsEncrypted](./get_isencrypted/)() const | Returns a value that indicates if the data sent using this stream is encrypted. |
| virtual [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Returns a value that indicates if a server and a client are authenticated. |
| virtual [get_IsServer](./get_isserver/)() const | Returns a value that indicates if the local side of the connection is the server. |
| virtual [get_IsSigned](./get_issigned/)() const | Returns a value that indicates if the data sent using this stream is signed. |
| [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | RTTI information. |
## Fields

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | A stream with no underlying storage. |
## See Also

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
