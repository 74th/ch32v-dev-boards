# RVSWDIO Programmer

- Semantics [kicanvas](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2F74th%2Fch32v-dev-boards%2Fblob%2Frvswdio-programmer%2F1.0.1%2Frvswdio-programmer%2Frvswdio-programmer.kicad_sch)
- PCB [kicanvas](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2F74th%2Fch32v-dev-boards%2Fblob%2Frvswdio-programmer%2F1.0.1%2Frvswdio-programmer%2Frvswdio-programmer.kicad_pcb)

firmware

https://github.com/cnlohr/rv003usb/tree/master/rvswdio_programmer


The on/off levels of the power switch pin need to be swapped.

```h
#define POWER_ON 0
#define POWER_OFF 1
```