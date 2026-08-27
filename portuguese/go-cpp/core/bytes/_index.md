---
title: "Bytes"
second_title: "Aspose.PDF para Go via C++"
description: "Retornar o conteúdo do documento PDF como um slice de bytes."
type: docs
url: /pt/go-cpp/core/bytes/
---

_Retornar o conteúdo do PDF-document como um slice de bytes._

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
        // New cria um novo PDF-document
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes retorna o conteúdo do PDF-document como um slice de bytes
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Salvar o slice de bytes em um arquivo.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
