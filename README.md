# openclaw-drf
Django REST Framework skill for Openclaw


## Dev

When uploading to Clawhub, you may need to provide a folder without `git`-related files. Use this to easily generate the folder in your home directory:

```bash
UNGIT_PREFIX=$(basename "$(git rev-parse --show-toplevel)") git archive --worktree-attributes --prefix "$UNGIT_PREFIX-export/" -o /tmp/$UNGIT_PREFIX.zip HEAD && unzip -o /tmp/$UNGIT_PREFIX.zip -d ~/
```

The folder to upload to Clawhub will now be available in `~/openclaw-drf-export`.
