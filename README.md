# zmk-sweep

Steps to flash:
1. First build the firmware via github actions (push or trigger rebuild)
2. Download firmware and unzip
3. Connect and reset the left pcb, you will see it under `lsblk`
4. Mount and copy the `cradio_left-nice_nano_v2-zmk.uf2` into it
5. Repeat the step for the right half.
6. Enjoy!
