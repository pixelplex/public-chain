# Public chain

General description of С++ implementation of the Public-coin project.

## Build

Pull submodules

```bash
git submodule update --init --recursive
```

Install required tools:

```bash
./scripts/init.sh
```

Build project:

```bash
mkdir build
cd build 
cmake ..
cmake --build .
```

## Run

### Single node development chain

You can start a development chain for tests with:

```bash
./scripts/run-node.sh
```

### Multi-node local testnet

TBD

## Contribution

Thank you for considering to help out with the source code! We welcome contributions from anyone on the internet, and are grateful for even the smallest of fixes!

How to contribute is described in [CONTRIBUTING.md](./CONTRIBUTING.md) file.

## License

The Public-chain project is licensed under the MIT license. Included in our repository in the [LICENSE](LICENSE) file.