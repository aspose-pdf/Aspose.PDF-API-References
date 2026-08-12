---
title: "add_text_footer"
second_title: "Aspose.PDF för Rust via C++"
description: "Lägger till text i sidfot på ett PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/add_text_footer/
---

_Lägger till text i sidfot på ett PDF-dokument._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Lägg till text i sidfoten på ett PDF-dokument
    pdf.add_text_footer("FOOTER")?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```