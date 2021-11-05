# Stepper-Motor

This example demonstrates bidirectional operation of a
28BYJ-48, using a VMA401 - ULN2003 interface board to drive the stepper.
The 28BYJ-48 motor is a 4-phase, 8-beat motor, geared down by
a factor of 64. One bipolar winding is on motor pins 1 & 3 and
the other on motor pins 2 & 4. 

## Usage

A simple usage example.

```
import 28BYJ48

main:
  ...
```

See the `examples` folder for more examples.

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/nilwes/28BYJ-48/issues
