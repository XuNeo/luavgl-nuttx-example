# luavgl-nuttx-example
This repo contains `nuttx` and `apps` submodules ready to build luavgl on nuttx.

## Get the code
```bash
git clone --recursive https://github.com/XuNeo/luavgl-nuttx-example.git
```

## Build nuttx simulator

```bash
cd nuttx
tools/configure.sh boards/sim/sim/sim/configs/luavgl
make -j8
```

### Run simulator

```bash
./nuttx

NuttShell (NSH) NuttX-10.1.0
nsh> luavgl &

```

## Build for stm32f429-disc1 board

WIP
