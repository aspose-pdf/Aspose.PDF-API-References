---
title: "is_encrypted"
second_title: "Aspose.PDF для Rust через C++"
description: "Получить статус шифрования PDF-документа."
type: docs
url: /ru/rust-cpp/security/is_encrypted/
---

_Получить статус шифрования PDF‑документа._

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Открыть PDF‑документ, защищённый паролем
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Получить статус шифрования PDF‑документа
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```