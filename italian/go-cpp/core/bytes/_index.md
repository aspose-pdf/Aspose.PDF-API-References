---
title: "Bytes"
second_title: "Aspose.PDF per Go via C++"
description: "Restituisce il contenuto del documento PDF come una slice di byte."
type: docs
url: /it/go-cpp/core/bytes/
---

_Restituisci il contenuto del documento PDF come slice di byte._

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
        // New crea un nuovo PDF-document
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes restituisce il contenuto del documento PDF come slice di byte
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Salva lo slice di byte in un file.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
