---
title: "is_linearized"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer alır."
type: docs
url: /tr/rust-cpp/core/is_linearized/
---

_Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer alır._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Belgenin lineerleştirilip lineerleştirilmediğini gösteren bir değer al
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```