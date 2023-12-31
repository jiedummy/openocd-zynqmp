# openocd-zynqmp
use openocd with boards: avnet zub_1cg, xilinx kv260_starter and xilinx zcu104.
#
invoke openocd with zynqmp.cfg

![openocd_sc](https://github.com/jiedummy/openocd-zynqmp/assets/110552912/befd8484-f37b-45ee-a65d-73ebc115df8f)
#
use gdb to load platform/zynqm_fsbl/fsbl_a53.elf

![gdb_sc1](https://github.com/jiedummy/openocd-zynqmp/assets/110552912/54264743-cfce-4fac-870c-b8b39877e6b1)
#
use gdb to load hello_world/Debug/hello_world.elf

![gdb_sc2](https://github.com/jiedummy/openocd-zynqmp/assets/110552912/5d540b4f-445e-4140-bec1-b2a2144bb277)
