---
title: "расшифровать"
second_title: "Aspose.PDF для Rust через C++"
description: "Расшифровать PDF-документ."
type: docs
url: /ru/rust-cpp/security/decrypt/
---

_Расшифровать PDF‑документ._

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Открыть PDF‑документ, защищённый паролем
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Расшифровать PDF‑документ
    pdf.decrypt()?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```