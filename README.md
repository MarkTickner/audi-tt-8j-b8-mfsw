# Audi TT MK2 (8J) with B8 multifunction steering wheel controls

This project will add full compatibility to the multifunction steering wheel controls when a B8 steering wheel is retrofitted to the TT MK2. By default, the majority of the buttons do work correctly, but the 'Nav" button is inoperative, and instead the 'Mute' button performs the nav function.

Therefore, the nav function needs to be swapped to the 'Nav' button, and the 'Mute' button needs to send the correct signal so that it can be used by the head unit (an RNSE).

Some hardware changes will likely be required. This may also be compatible with other similar cars, e.g. A3 8P and gen 1 R8. Airbag and horn wiring is not in scope for this project.

## Background

The multifunction steering wheel controls (J453 in Audi terms) is a small control unit contained within the left and right sets of buttons. It communicates with the steering column control unit (J527) via a LIN bus connection (via the contact plate), which in itself comunicates with the rest of the car via CAN bus (powertrain and convenience).

The LIN bus signals will need to be intercepted between the contact plate and the steering column control unit, which unfortunately join together directly and therefore will require modification.

## LIN bus signals

## CAN bus signals

