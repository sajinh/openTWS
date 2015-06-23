## A low-power, low-cost integrated weather logger suitable developed as part of a research project on micro-scale weather processes in the Aizu basin.

Version 1 is an Atmega328p based data logger, connected to
an external board containing, one pressure (BMP180), one humidity (HIH-6031-001)
and two temperature sensors (TMP102, LM92). The Atmega is clocked internally
using a RC circuit. A 32.678KHz crystal is connected the TOSC1(2) pins to
provide a simple Real Time Clock. For logging, a microSD card is used. The
unit comes with a holder for a 3.7V cell battery, for limited period use such
as in a tethered balloon sounding. Two switches (slider and push button),
with associated debouncing hardware, can be used for setting the time, and
for sleep. The schematic is available in the doc folder.

Version 2 will include a single band GNSS reciever for
GNSS based water-vapor measurements and possibly a 2.4GHz radio 
for networking.

### The GNSS based water-vapour logger

This is being developed. Documentation during this development stage can be found at
http://climdyn.u-aizu.ac.jp/redmine/projects/low-cost-gnss-applications/wiki  and
http://climdyn.u-aizu.ac.jp/redmine/projects/opentws/wiki  The latter wiki page also hosts the
hardware design schematic
