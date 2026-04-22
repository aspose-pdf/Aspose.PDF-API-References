---
title: "sign_pkcs7"
second_title: Aspose.PDF for Rust via C++
description: "Sign a PDF-document using PKCS#7 digital signatures."
type: docs
url: /rust-cpp/security/sign_pkcs7/
---

_Sign a PDF-document using PKCS#7 digital signatures._

```rust
    pub fn sign_pkcs7(
        &self,
        num: i32,
        sign_data: &[u8],
        psw_sign: &str,
        set_x_indent: i32,
        set_y_indent: i32,
        set_height: i32,
        set_width: i32,
        reason: &str,
        contact: &str,
        location: &str,
        is_visible: bool,
        appearance_data: &[u8],
        filename: &str,
    ) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **sign_data** - the raw bytes of the signature (PKCS#7 specification in Internet RFC 2315)
  * **psw_sign** - the password of the signature
  * **set_x_indent** - the x indent of the signature
  * **set_y_indent** - the y indent of the signature
  * **set_height** - the height of the signature
  * **set_width** - the width of the signature
  * **reason** - the reason of a signature
  * **contact** - the contact of a signature
  * **location** - the location of a signature
  * **is_visible** - the visiblity of signature
  * **appearance_data** - the raw bytes of the graphic appearance for the signature
  * **filename** - the path to the resulting PDF-document with signature


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;
use std::fs;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Read certificate and image files into byte vectors
    let cert = fs::read("sign.pfx")?;
    let img = fs::read("sign.png")?;

    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Sign a PDF-document using PKCS#7 digital signatures
    pdf.sign_pkcs7(
        1,
        &cert,
        "Pa$$w0rd2023",
        100,
        100,
        70,
        100,
        "Reason",
        "Contact",
        "Location",
        true,
        &img,
        "sample_sign_pkcs7.pdf",
    )?;

    Ok(())
}

```