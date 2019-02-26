# Applied BioCode barcode encoder/decoder

This is a single-page Javascript tool I wrote for interactively encoding and
decoding Applied BioCode bead barcodes.

http://www.apbiocode.com/

Simply put, Applied BioCode (ABC) is a bead-based multiplexing assay
technology. Each 70 um x 40 um bead is printed with a barcode, allowing
multiple tests to be distinguished in the same biological sample.

The beads are read with a proprietary ABC reader. However, during development
it's often necessary to inspect the beads with a microscope---say, to investigate
a defect. Though ABC uses a simple binary scheme, it's difficult for most
people to decode the barcodes by inspection. I wrote this tool to help us
decode barcode patterns visually.


## Instructions

1. Open "ABC Barcode Decoder.html" in a browser (Chrome or Firefox). This is
what a "Barcode 0" bead looks like when magnified.

2. The barcode encodes a binary number between 0 and 4095, identifying beads
coated with the same analyte. Hover the mouse over the bead image. Regions that
turn gray represent the "bits" of the barcode. Click to "set" the bit; click
again to "clear" the bit. The decoded barcode number will automatically
display below the bead.

3. Alternatively, enter a number between 0 and 4095 in the text box, and it
will show what a bead of this barcode number looks like.

It's as simple as that!  Have fun!