---
title: "is_linearized"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämtar ett värde som indikerar om dokumentet är lineariserat."
type: docs
url: /sv/rust-cpp/core/is_linearized/
---

_Hämtar ett värde som indikerar om dokumentet är lineariserat._

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
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Hämta ett värde som indikerar om dokumentet är lineariserat
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```