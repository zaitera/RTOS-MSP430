## Example Summary

This example is intended to be a starting point for new development where
a minimal footprint is needed.

## Peripherals Exercised

* `Board_LED0` - Indicates that the board was initialized within `main()`

## Example Usage

* The example lights `Board_LED0` as part of the initialization in `main()`.
Then a heartBeat task toggles the LED at a rate determined by the `arg0`
parameter for the constructed Task instance in the .c file.

## Application Design Details

This examples is the same as the __Empty__ example except many development
and debug features are disabled. For example:

* No logging is enabled
* No assert checking is enabled
* No Kernel Idle task
* Non-Instrumented driver modules are used
* No stack overflow checking

> Please refer to the __Memory Footprint Reduction__ section in the
TI-RTOS User Guide *spruhd4.pdf* for a complete and detailed list of the
differences between the empty minimal and empty projects.

## References
* For GNU and IAR users, please read the following website for details
  about enabling [semi-hosting](http://processors.wiki.ti.com/index.php/TI-RTOS_Examples_SemiHosting)
  in order to view console output.

* For more help, search either the SYS/BIOS User Guide or the TI-RTOS
Getting Started Guide within your TI-RTOS installation.