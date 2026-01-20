---
title: System::Net::WebRequest::CreateHttp method
linktitle: CreateHttp
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::CreateHttp method. Creates a new instance of the WebRequest class using the specified URI in C++.'
type: docs
weight: 300
url: /cpp/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) method


Creates a new instance of the [WebRequest](../) class using the specified URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | String | The URI that is used to create a new instance of the [WebRequest](../) class. |

### ReturnValue

A newly created WebRequest-class instance.
## Remarks



NotSupportedException will be thrown when the specified URI begins with any scheme except for [http://](http://) or [https://](https://). 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) method


Creates a new instance of the [WebRequest](../) class using the specified URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | System::SharedPtr\<Uri\> | The URI that is used to create a new instance of the [WebRequest](../) class. |

### ReturnValue

A newly created WebRequest-class instance.
## Remarks



NotSupportedException will be thrown when the specified URI begins with any scheme except for [http://](http://) or [https://](https://). 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [Uri](../../../system/uri/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
