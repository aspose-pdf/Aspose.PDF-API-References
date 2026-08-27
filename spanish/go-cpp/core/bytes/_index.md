---
title: "Bytes"
second_title: "Aspose.PDF para Go vía C++"
description: "Devolver el contenido del documento PDF como una porción de bytes."
type: docs
url: /es/go-cpp/core/bytes/
---

_Devuelve el contenido del documento PDF como una porción de bytes._

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
        // New crea un nuevo PDF-documento
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes devuelve el contenido del documento PDF como una porción de bytes
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Guarda la porción de bytes en un archivo.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
