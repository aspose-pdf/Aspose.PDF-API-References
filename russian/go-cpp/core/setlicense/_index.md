---
title: "SetLicense"
second_title: "Aspose.PDF для Go через C++"
description: "Установить лицензию с помощью имени файла."
type: docs
url: /ru/go-cpp/core/setlicense/
---

_Установить лицензию с именем файла._

```go
func (document *Document) SetLicense(filename string) error
```

**Parameters**: 
  * **filename** - full name of the license file

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// SetLicense(filename string) лицензирует с именем файла
	err = pdf.SetLicense("Aspose.PDF.GoViaCPP.lic")
	if err != nil {
		log.Fatal(err)
	}
	// Работа с PDF-документом
	// ...
}
```
