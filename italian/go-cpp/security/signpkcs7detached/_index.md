---
title: "SignPKCS7Detached"
second_title: "Aspose.PDF per Go via C++"
description: "Firma un documento PDF usando firme digitali PKCS#7 separate."
type: docs
url: /it/go-cpp/security/signpkcs7detached/
---

_Firma un documento PDF usando firme digitali PKCS#7 Detached._

```go
func (document *Document) SignPKCS7Detached(num int32, signData []byte, pswSign string, setXIndent, setYIndent, setHeight, setWidth int32, reason, contact, location string, isVisible bool, appearanceData []byte, filename string) error
```

**Parameters**: 
  * **num** - the page number of the PDF-document
  * **signData** - the raw bytes of the signature (PKCS#7 specification in Internet RFC 2315)
  * **pswSign** - the password of the signature
  * **setXIndent** - the x indent of the signature
  * **setYIndent** - the y indent of the signature
  * **setHeight** - the height of the signature
  * **setWidth** - the width of the signature
  * **reason** - the reason of a signature
  * **contact** - the contact of a signature
  * **location** -  the location of a signature
  * **isVisible** - the visiblity of signature
  * **appearanceData** - the raw bytes of the graphic appearance for the signature
  * **filename** - the new filename, with signature

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "os"

func main() {
	cert, _ := os.ReadFile("sign.pfx")
	img, _ := os.ReadFile("sign.png")

	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()

	// SignPKCS7Detached firma un documento PDF usando firme digitali PKCS#7 Detached
	err = pdf.SignPKCS7Detached(1, cert, "Pa$$w0rd2023", 100, 100, 70, 100, "Reason", "Contact", "Location", true, img, "sample_SignPKCS7Detached.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
