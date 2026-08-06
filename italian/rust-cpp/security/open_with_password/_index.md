---
title: "open_with_password"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Apri un PDF-document protetto da password."
type: docs
url: /it/rust-cpp/security/open_with_password/
---

_Apri un PDF-document protetto da password._

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
    // Apri un PDF-document protetto da password
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // elaborazione...

    Ok(())
}

```