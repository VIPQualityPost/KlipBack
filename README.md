# KlipBack
Klipper backplane for accessory development and flexible electronic configuration

Designed to provide USB connection over a hub to the Klipper host, along with inter-card bus and board-provided power.
May change next design to remove a slot, but add a USB out port so that the cards can be daisy chained.

The board is intended to create a platform for developing accessories for Klipper-controlled motion systems, so that you can take care of basic needs (steppers, endstops, GPIO, etc) without needing to include those in board spinup while trying new configurations or designs.

!(render1.png)
!(render2.png)
