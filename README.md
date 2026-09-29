# vibepage CLI

Install:

```bash
curl -fsSL https://github.com/dayzero-run/cli/releases/latest/download/install.sh | bash
```

Releases and binaries are published here. The hosting control plane stays in a private repository.

## Manual download

Grab the binary for your OS/arch from [Releases](https://github.com/dayzero-run/cli/releases), then:

```bash
chmod +x dayzero-run-*
mv dayzero-run-* ~/.local/bin/dayzero-run
```

## After install

```bash
d0 login you@email.com
d0 init --name my-app
d0 deploy
```
