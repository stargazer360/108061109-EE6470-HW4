# Homework 4
A 0cross-compile Gaussian blur filter to RISC-V VP platform
## Compile & RUN
1. Download the updated source code to the location of riscv-vp platform and software:
* `$ cd $EE6470`
* `$ git clone https://github.com/stargazer360/108061109-EE6470-HW4.git`
* `$ cp -r 108061109-EE6470-HW4/riscv-vp/vp/src/platform/* $EE6470/riscv-vp/vp/src/platform`
* `$ cp -r 108061109-EE6470-HW4/riscv-vp/sw/* $EE6470/riscv-vp/vp/sw`
2. Build the "basic-acc" platform of riscv-vp:
* `$ cd $EE6470`
* `$ cd riscv-vp/vp/build`
* `$ cmake ..`
* `$ make install`
3. Build the software for simulation:
* `$ cd $EE6470`
* `$ cd riscv-vp/sw/basic-blur`
* `$ make`
* `$ make install`
