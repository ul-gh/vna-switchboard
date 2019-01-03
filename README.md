![Alt text](title.jpg?raw=true "Title Image")

![Alt text](VNA-Switchboard_TOP.jpg?raw=true "Image VNA-Switchboard TOP face")

# VNA-Switchboard FAN3241
KiCad project files for PCB driving a 12V...28V latching relay
from a single 5V voltage source, control is a high/low input signal.

Using an MT3608 step-up DCDC converter input current-limited
to less than 100 mA, timing and protection circuitry integrated
into FAN3241 driver IC and RF/EMC shielding provision for the
step-up coverter, this is designed for driving the direction
switch of a VNA S-parameter test set.

The input is a 6P6 western socket pinning compatible to the
DG8SAQ VNWA3. When this input is connected, no additional power
supply or control signals are required.

Schematic PDF: [VNA-Switchboard_FAN3241.pdf](VNA-Switchboard_FAN3241.pdf)

Additional instructions: Most if not all MT3608 DCDC converter boards sold
today require the following bug fix if medium output voltages are to be set:

![Alt text](MT3608-bugfix.jpg?raw=true "MT3608 bug fix")

