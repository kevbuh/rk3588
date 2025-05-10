# rk3588

<!-- **Goal:** Rockchip RK3588 RKNN NPU backend passing all ops tests in [tinygrad](https://github.com/tinygrad/tinygrad) -->

## Notes
- Registers are set by issueing ioctls's and involvement of the rknpu drivers.

## Documents

- [Brief Datasheet](https://www.rock-chips.com/uploads/pdf/2022.8.26/192/RK3588%20Brief%20Datasheet.pdf)
- [Datasheet](https://www.boardcon.com/download/Rockchip_RK3588_Datasheet_V1.0-20211220.pdf)
- [Technical Reference Manual (TRM)](https://www.scs.stanford.edu/~zyedidia/docs/rockchip/rk3588_part1.pdf)
- [Reverse Engineering](https://github.com/mtx512/rk3588-npu/tree/main)
- [Reverse Engineering 2](https://jas-hacks.blogspot.com/2024/02/rk3588-reverse-engineering-rknn.html)

## Twitter

- The hardware is pretty well documented in the RK3588 datasheet.
- Rockchip RK3588 RKNN NPU backend passing all ops tests
- [Conv Flow](https://x.com/b0jle/status/1918290647502762343)

## TODO
- make a backup of opi-5 firmware and OS image to prevent bricking