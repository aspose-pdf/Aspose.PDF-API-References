---
title: "Bytes"
second_title: Aspose.PDF for Go via C++
description: "Return the contents of the PDF-document as a byte slice."
type: docs
url: /go-cpp/core/bytes/
---

_Return the contents of the PDF-document as a byte slice._

```go
func Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **[]byte** - raw bytes of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
        "github.com/aspose-pdf/aspose-pdf-go-cpp"
        "log"
        "os"
)

func main() {
        // New creates a new PDF-document
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes returns the contents of the PDF-document as a byte slice
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Save the byte slice to a file.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
