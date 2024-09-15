# project path

## [setup](https://docs.rs/plotters/latest/plotters/#trying-with-jupyter-evcxr-kernel-interactively)

```bash
sudo apt update
sudo apt upgrade
sudo apt install libzmq3-dev jupyter-notebook
mkdir <project path> && cd $_
cargo init .
cargo install evcxr_jupyter
evcxr_jupyter --install
```
