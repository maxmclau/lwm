# LWM

Arduino port of [Atmel Lightweight Mesh](http://www.atmel.com/tools/lightweight_mesh.aspx).

#### Install

```Shell
$ git clone https://github.com/moa/lwm.git
```

#### Configuration

LWM requires a lwm.h file with configuration macros in order to compile correctly.

##### Configuration / Location

    ├── parent
    │   ├── lwm
    │   │   ├── hal
    │   │   ├── nwk
    │   │   ├── phy
    │   │   └── sys
    │   └── lwm.h

##### Configuration / Example

```Arduino
#ifndef _LWM_H_
#define _LWM_H_

#define HAL_ATMEGA256RFR2
#define PHY_ATMEGARFR2

#endif // _LWM_H_
```

#### License

[**`Atmel Limited License`**](LICENSE)
