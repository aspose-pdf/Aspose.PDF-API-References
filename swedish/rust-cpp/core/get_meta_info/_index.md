---
title: "get_meta_info"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämtar metainformationsvärde för PDF-document."
type: docs
url: /sv/rust-cpp/core/get_meta_info/
---

_Hämtar metainformationsvärde för PDF-document._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Hämta metainformationsvärde för PDF-document
    let author = pdf.get_meta_info("Author")?;

    // Skriv ut resultatet
    println!("Author: {}", author);

    Ok(())
}

```