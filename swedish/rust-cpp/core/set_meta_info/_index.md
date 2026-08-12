---
title: "set_meta_info"
second_title: "Aspose.PDF för Rust via C++"
description: "Ställer in metainformationsvärde för PDF-dokument."
type: docs
url: /sv/rust-cpp/core/set_meta_info/
---

_Ställer in metainformationsvärde för PDF-dokument._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ställ in metainformationsvärde för PDF-dokument
    pdf.set_meta_info("Author", "Aspose")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```