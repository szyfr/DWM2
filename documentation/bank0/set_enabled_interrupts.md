# set_enabled_interrupts()

## Code
```
set_enabled_interrupts :: proc(B: flags) {
	[rIF] = 0;
	[rIE] = flags;
}
```
## Variables
##### Hardware
- [rIF](variables/hardware/rIF.md) [W]
- [rIE](variables/hardware/rIE.md) [W]