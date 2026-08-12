---
title: "is_signed"
second_title: "Aspose.PDF для Rust через C++"
description: "Получить статус подписания PDF-документа."
type: docs
url: /ru/rust-cpp/security/is_signed/
---

_Получить статус подписи PDF-документа._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Открыть PDF‑документ с именем "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Получить статус подписи PDF-документа
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```