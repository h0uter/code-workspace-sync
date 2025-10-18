# VS Code Workspace Synchronizer

A script to synchronize a VS Code workspace with directories in a source repositories folder.
It can add new directories and optionally remove directories that no longer exist.

```bash
uv tool install code-workspace-sync
```

For help and available commands, run: `code-workspace-sync --help`:

<!-- [[[cog
    import subprocess as sp
    out = sp.check_output(["code-workspace-sync", "--help"], stderr=sp.DEVNULL).decode()
    cog.out("```text\n" + out + "```\n")
]]] -->
<!-- [[[end]]] -->
