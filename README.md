DexedBreakout is a small Raspberry Pi Hat that fits into of the shelf RPI cases with small modifications. The connections are aligned to RPI connectors so that the assmebly can be enclosed easily.

It includes a PCM5102 DAC, a 0.96 inch OLED and a rotary encoder. The PCB is arranged so that the OLED centers the Raspberry. It offers TRS type MIDI IN, a true hardware TRS type MIDI THRU and a stereo audio output jack.

The MIDI IN is connected to RX pin of the Raspberry PI I/O. MIDI THRU port replicates the MIDI IN signal via a buffer chip.

PCM5102 is configured to run in I2S mode and configuration pins are hardwired.

The Encoder is KY-040 type encoder. A/CLK is connected to GPIO9, B/DAT is connected to GPIO10 and switch is connected to GPIO11.

The 40 pin I/O header is designed to be a female regular input. A passthrough type would be much nicer to lower the position of the card however neither SMT nor THT pass-through connectors fit since the I/O is very close to the edge. It is possible not to populate the female header and directly solder the card to the RPI to lower the height and fit the assembly in to a case.
