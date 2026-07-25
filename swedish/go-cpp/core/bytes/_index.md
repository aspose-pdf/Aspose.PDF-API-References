---
title: "Bytes"
second_title: "Aspose.PDF för Go via C++"
description: "Returnera innehållet i PDF-dokumentet som en byte-slice."
type: docs
url: /sv/go-cpp/core/bytes/
---

_Returnera innehållet i PDF-dokumentet som en byte slice._

```go
func (document *Document) Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **\[\]byte** - raw bytes of the PDF-document
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
        // New skapar ett nytt PDF-dokument
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes returnerar innehållet i PDF-dokumentet som en byte slice
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Spara byte‑slice:n till en fil.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
