---
title: "Bytes"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-dökümanının içeriğini bayt dilimi olarak döndür."
type: docs
url: /tr/go-cpp/core/bytes/
---

_PDF-belgesinin içeriğini bir bayt dilimi olarak döndür._

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
        // New yeni bir PDF belgesi oluşturur
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes PDF-belgesinin içeriğini bir bayt dilimi olarak döndürür
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Bayt dilimini bir dosyaya kaydet.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
