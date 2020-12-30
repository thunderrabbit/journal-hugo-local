# journal-hugo-local
Allows me to test just journal entries on my local machine

This repo allows me to test edits of my journal entries before committing them to the repo.

To view journal entries, I run this script

```
#!/bin/bash
cd ~/journal-hugo-local

hugo server --watch=false
```

So it looks like I must have set up a symlink from the ~/journal directory which has my entries to ~/journal-hugo-local/content/journal
