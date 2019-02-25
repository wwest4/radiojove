# Overview

This re-implements some/all of the [radiojove receiver](https://radiojove.gsfc.nasa.gov/telescope/rcvr_manual.pdf).

For on-board components I try as much as possible to source via Digi-Key's regularly stocked items. When other vendors are used, it's indicated.

# Stages

## RF Input Bandpass
This is a 20.1 MHz bandpass filter that is applied to the input signal prior to amplification. It's based on a LC/tank filter, tunable with a variable capacitor.

### Input:
antenna in from 50-ohm coax

### Output:
filtered unamplified signal

### Parts:
| ID            | Description   | Vendor        | Part Number  |
|:------------- |:--------------|:--------------|:-------------|
| C1 | 39pF ceramic cap | Digi-Key | 399-4238-ND
| C2 | 3-40 pF trimmer cap | Digi-Key | SG3008-ND |
| C3 | 56 pF ceramic cap | Digi-Key | 399-14047-ND |
| C4 | 22 pF ceramic cap | Digi-Key | BC5148-ND |
| C5 | 10000 pF ceramic cap | Digi-Key | BC5213CT-ND |
| J2 | (wire leads for a bulkhead coax jack) | n/a | n/a |
| L1 | 470 nH inductor | Digi-Key | 495-6935-1-ND |
| L2 | 1 uH inductor | Digi-Key | M10137-ND |
| R1 | 68 ohm resistor | Digi-Key | CF14JT68R0CT-ND |




