---
title: "open_with_password"
second_title: "Aspose.PDF для Rust через C++"
description: "Открыть защищённый паролем PDF-документ."
type: docs
url: /ru/rust-cpp/security/open_with_password/
---

_Открыть PDF‑документ, защищённый паролем._

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
    // Открыть PDF‑документ, защищённый паролем
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // выполняется...

    Ok(())
}

```