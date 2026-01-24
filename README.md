# GNNPCSAFT CLI

The GNNPCSAFT CLI is an implementation of [our project](https://github.com/wildsonbbl/gnnepcsaft/) that focuses on using Graph Neural Networks ([GNN](https://en.wikipedia.org/wiki/Graph_neural_network)) to estimate the pure-component parameters of the Equation of State [PC-SAFT](https://en.wikipedia.org/wiki/PC-SAFT). We developed this CLI so the scientific community can access the model's results easily.

Implementations with GNNPCSAFT:

- [GNNPCSAFT APP](https://github.com/wildsonbbl/gnnpcsaftapp)
- [GNNPCSAFT MCP](https://github.com/wildsonbbl/gnnepcsaft_mcp_server)
- [GNNPCSAFT Webapp](https://github.com/wildsonbbl/gnnepcsaftwebapp)
- [GNNPCSAFT Chat](https://github.com/wildsonbbl/gnnpcsaftchat)

## CLI

GNNPCSAFT CLI

**Usage**:

```console
gnnepcsaftcli [OPTIONS] COMMAND [ARGS]...
```

**Options**:

- `--install-completion`: Install completion for the current shell.
- `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
- `--help`: Show this message and exit.

**Commands**:

- `pred`: Predict PCSAFT parameters from SMILES...

## `pred`

Predict PCSAFT parameters from SMILES with a GNNPCSAFT model

**Usage**:

```console
pred [OPTIONS]
```

**Options**:

- `--help`: Show this message and exit.
