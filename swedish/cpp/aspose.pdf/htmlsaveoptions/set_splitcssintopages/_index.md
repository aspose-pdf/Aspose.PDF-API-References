---
title: "Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages metod"
linktitle: "set_SplitCssIntoPages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages‑metod. När flersidigt läge är valt (dvs. ''SplitIntoPages'' är ''true''), definierar detta attribut om en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är detta attribut falskt, så en stor gemensam CSS skapas för alla skapade sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en stor CSS‑fil, eftersom i det första fallet CSS‑klasser dupliceras i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida oberoende, och därför är storleken på CSS för varje enskild sida det mest kritiska problemet i C++."
type: docs
weight: 4200
url: /sv/cpp/aspose.pdf/htmlsaveoptions/set_splitcssintopages/
---
## HtmlSaveOptions::set_SplitCssIntoPages method


När flersidigt läge är valt (dvs. 'SplitIntoPages' är true) definierar detta attribut om en separat CSS‑fil ska skapas för varje resulterande HTML‑sida. Som standard är detta attribut false, så en stor gemensam CSS‑fil skapas för alla sidor. Den sammanlagda storleken på alla CSS‑filer som genereras i detta läge (en CSS per sida) är vanligtvis mycket större än storleken på en enda stor CSS‑fil, eftersom i det första fallet dupliceras CSS‑klasser i flera CSS‑filer för varje sida. Därför bör denna inställning endast användas när du är intresserad av framtida bearbetning av varje HTML‑sida separat, och därmed är storleken på CSS för varje enskild sida det mest kritiska.

```cpp
void Aspose::Pdf::HtmlSaveOptions::set_SplitCssIntoPages(bool value)
```

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
