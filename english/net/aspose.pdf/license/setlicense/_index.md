---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: License method. Licenses the component
type: docs
weight: 40
url: /net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licenses the component.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |

## Remarks

Tries to find the license in the following locations:

1. Explicit path.

2. The folder that contains the Aspose component assembly.

3. The folder that contains the client's calling assembly.

4. The folder that contains the entry (startup) assembly.

5. An embedded resource in the client's calling assembly.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Explicit path.

2. An embedded resource in the client's calling assembly.

[Java]

2. The folder that contains the Aspose component JAR file.

3. The folder that contains the client's calling JAR file.

### See Also

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Licenses the component.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream that contains the license. |

## Remarks

Use this method to load a license from a stream.

### See Also

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


