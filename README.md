# GameBoy-Flipper-Zero

**A pure Flipper Zero Game Boy emulator written from scratch (no external dev board required). Open-source, educational, and designed for the Flipper’s internal hardware!**

---

## Goals

- Run original Game Boy ROMs (no copyrighted ROMs distributed)
- Map Game Boy controls to Flipper buttons:
  - D-Pad: Up/Down/Left/Right = Game Boy D-Pad
  - OK: A
  - Back: B
  - Long-press Back: Exit emulator
- Load `.gb` files from SD card
- Optimize for performance and low memory

---

## Getting Started

1. **Clone this repo:**
    ```bash
    git clone https://github.com/HermeticCode/GameBoy-Flipper-Zero.git
    ```
2. **Set up the Flipper Zero SDK:**  
   [Flipper Zero Developer Documentation](https://docs.flipperzero.one/devtools/dev-qflipper/installation)

3. **Build and flash to Flipper:**
    ```bash
    ./fbt
    ./fbt launch_app APPSRC=applications_user/GameBoy-Flipper-Zero
    ```

4. **Load ROM:**  
   Copy a legal Game Boy `.gb` file to your SD card. Launch emulator from Flipper menu.

---

## Contributing

- Contributions are welcome!
- Please file issues or pull requests for any improvements, bugs, or ideas.
- Check the [`TODO`](#todo) section for things to work on.

---

## TODO

- [ ] Core CPU emulation (Z80/LR35902)
- [ ] Memory mapping (ROM, RAM, IO)
- [ ] LCD display integration (downscale or crop to Flipper’s screen)
- [ ] SD card ROM selector
- [ ] Sound support (if feasible)
- [ ] Save states

---

## License

This project is licensed under the terms of the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

---

**Note:**  
No copyrighted ROMs are distributed or accepted.


**Note:**  
No copyrighted ROMs are distributed or accepted.

