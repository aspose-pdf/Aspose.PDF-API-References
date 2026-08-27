---
title: "open_with_password"
second_title: "Aspose.PDF für Rust über C++"
description: "Öffne ein passwortgeschütztes PDF-Dokument."
type: docs
url: /de/rust-cpp/security/open_with_password/
---

_Öffnen Sie ein passwortgeschütztes PDF-Dokument._

```rust
pub fn open_with_password(filename: &str, password: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open
  * **password** - user/owner password of the password-protected PDF-document

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffnen Sie ein passwortgeschütztes PDF-Dokument
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // arbeitet...

    Ok(())
}

```