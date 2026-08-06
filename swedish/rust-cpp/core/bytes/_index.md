---
title: "bytes"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar innehållet i PDF-dokumentet som en bytevektor."
type: docs
url: /sv/rust-cpp/core/bytes/
---

_Returnerar innehållet i PDF-dokumentet som en bytevektor._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Skapa ett nytt PDF-dokument
    let pdf = Document::new()?;

    // Returnera innehållet i PDF-dokumentet som en bytevektor
    let data = pdf.bytes()?;

    // Skriv ut längden på bytevektorn
    println!("Length: {}", data.len());

    Ok(())
}

```