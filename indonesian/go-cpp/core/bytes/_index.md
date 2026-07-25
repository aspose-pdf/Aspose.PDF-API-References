---
title: "Bytes"
second_title: "Aspose.PDF untuk Go via C++"
description: "Kembalikan isi dokumen PDF sebagai potongan byte."
type: docs
url: /id/go-cpp/core/bytes/
---

_Kembalikan isi dokumen PDF sebagai potongan byte._

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
        // New membuat PDF-document baru
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes mengembalikan isi dokumen PDF sebagai potongan byte
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Simpan potongan byte ke sebuah file.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
