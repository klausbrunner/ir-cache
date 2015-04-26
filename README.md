# ir-cache

Schematics and source code for a device that waits for a trigger signal and sends back a response in morse code. The trigger signal is an IR transmission as generated by pressing a button on a TV remote (the TSOP18xx conveniently filters out anything else). The response is flashed back by an IR LED (an additional LED is also there to give visual feedback).

The whole setup is intented to be used for geocaching. It can be built using any low-cost Arduino (I used a LilyPad) and put into a clear, waterproof box. With standard AA cells, battery lifetime should be several months.
