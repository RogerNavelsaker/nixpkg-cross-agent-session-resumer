# nixpkg-cross-agent-session-resumer

Thin Nix packaging repo for [`Dicklesworthstone/cross_agent_session_resumer`](https://github.com/Dicklesworthstone/cross_agent_session_resumer).

## Upstream

- Repo: `Dicklesworthstone/cross_agent_session_resumer`
- Source: fetched directly from the pinned upstream GitHub revision
- Upstream crate version: `0.1.1`
- Pinned upstream commit: `8e29029700de42ba38eefae125aaa425bce700f0`

## Usage

```bash
nix build
nix run
```

The package installs the `casr` binary from a narrowed Rust source stage built from the pinned upstream revision.
