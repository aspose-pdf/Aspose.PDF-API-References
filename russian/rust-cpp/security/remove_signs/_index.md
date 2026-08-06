---
title: "remove_signs"
second_title: "Aspose.PDF для Rust через C++"
description: "Удалить подписи из PDF-документа."
type: docs
url: /ru/rust-cpp/security/remove_signs/
---

_Удалить подписи из PDF‑документа._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Открыть PDF‑документ с именем "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Удалить подписи из PDF‑документа
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```