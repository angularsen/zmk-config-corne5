Corne5 ZMK config by angularsen
---

## Modifications to urob defaults
### Combos
- Move `~` from LM0 LB0 to LT4 LM4
- Move `|` from RM3 RB3 to LM4 LB4
- Move `/` from RM2 RB2 to RB4, shift for `?` as default
- Move `=` from LM1 LB1 to RT4 RM4
- Move `!` from shift RB4 to RM4 RB4
- Move `{}` to RM0 RM1 and RM3 RM4, `[]` on shift (previously shift for `[]`, inverted since braces are more frequently used in c# coding)
- Move `<>` to RB1 RB2 and RB2 RB3, previously shift `()`
- Add context menu to LM0 LB0
- Add macro `!=` to RT2 RT3 RT4

### Layouts
#### Num layer
- Add +-*/. to right hand (could not type dot '.' with sticky/word num layer)
- Add , to left hand

#### Function layer
- Add print screen to RM4

### Other
- Disable `spc_morph` so `shift+space` no longer sends dot, space and sticky shift. It conflicts with Rider key bindings like `shift+ctrl+space` for smart completion.

[Keymap drawer](https://caksoylar.github.io/keymap-drawer?keymap_yaml=H4sIAAAAAAAC_91Y_XbbNBT_v08hTiECmi6z06-FMkhTpy1L05CkW8cYnuKojU9sy_hjWVrCY_A2vAxPgiz5K7Zs94SdwyDnVEp_-t3fvZLuVWxtg-5Frwcu-mCCDbIAtzo2pmChezOAwHtk-BgY-hyDh1_NuTrHywlBzrQFbrHj6G7DXWBsr7a2AXHAA3G8GVENtCS-1wIPrm3otPccH9eBQxZuCzTrQCOGb1r0-34deDPfnNCv8iqQcDEGM8-z3VajcUf9-5MnGjEbGpq7ZGkgp0G9m8jenTpogZ3GxCCThol0q_FCeX3ZHqijgdJ5Yk63eQBbYd_aigOirl2V-1Qt4iFPJxaNKfjsNAH9Cz6rgI8dt7UFwAS5OOh3wY-sfcXaLmsHrD1j7Q-s7bH2mrWvWQvph315oO7bdTBrgd7Z9cUqxoYca_fGCTbi2Oi8mwLHHOyMhz0OnrL2PCb0s4QAVBg4XJe6EPi8ysT2E2tvWNth7UvWnrD2BWsvY2tYh3VAt_GbRPAJA2ALJhD8jrPgZyEYuEtmPWh3eLgWes95tSnxVNfWUhpDhS_ErZXSrVm-qU6RpWHIBXwzGWXryGDX07X5MpTWkO2qC-JMQ3FYc03keKpJfBcHe0ajaMUif_3xJ03WpY2DbEaWu6oYGd16O2DcPomkF8i2sQMrrAZn4HoQc05Ggw6Lu-MZO-y_xOv1IBk5v7pUkpFTpZcM0X9Wj5hDsA-pFUoN0BwRD2QWNTUSJKBwpHDOp_3EWgllM5O6etVPZqX0T1MJcXF2zk1imObIxhv3cUcu-iPWR5lwzPPheVUipAqDDc3oibx5FJ12v6P0xFl-a_Ek70oy7w95d8S7Zxs7HQwVfmK8vOpFWd1XbsZhGAvdUl2D_nQkS9GVJMEB2d0TnFbdfdER2T0QHYGb7OaZr--wVIvzMSMaTOq0LzpcY9MkMddjF3vtSk_DnnfhbjQrzCJv7Lxp5yH-q9U26Nd3G6_I2jFdZJzJ08vrscLzYFBwvPpm1fEKD3lywKOwfwY_kbouH4FPoSCR4R4UZAPch6JUhgfwY-XyvzsCpXDv5LBvfvp7-Kh8f3QllKxNtibcpZvUxAk_PGgyrXKYJMBkAdYMsZMx6PSG_-E02ij1ahNCPIOgafTklUf-f3OmOaQ62MUeFAOfVBHlSmXz2vG1xzytwxo2VGLiO6TSV12aBeHbQIz67Dk9Y2DP9Bw9wMRkAbeAOsFePg4GZukVMzKQOZnmpUKYi0X266vLeL7t6gaxcvYRLp6nK5ioq1d4m2IVu_fY89ZtE1joCxn2LD89jgoNnOAaIkMPMCHZ1e_MvDpHhQYe8nP0ABOS75ApUOeo0MDMi5sF2laeahVQccEe47I91okgQRkopBNTnzsCHxEuNLoXFcE9LvLxIZ91HwrKSxOUrVZUtlNsCOLgqDgJZqLAOSo0mCPbzhtwVLxlAn2xOi0fhHMVRSEhleSppIDq56n-OvUfPixt9BOXPvk1Yk4IfWzaBXYLvKFvkPJbSpu3gDIK7q0MCgaXeHV-q0TfOt6GVLkOmiF1qIyvh_1StpSwcz89JVbUTIoCYrd47RP2ZMZezqI3gRJ7GqTUTNnD2hwv6c-5jZEHU0rRa0LJdIOliaTYC-pNNV9O8_llRomFnPLAwqqyoO_rhyE_uN4q5R7WwVHIPWWXGSWrRnWlw9SqfZlZKZbMx5n1StlTX9JRyv6r9T3jtfAcFgukAzgOWTRKoQN-G5RhyFRBjhTgG1jkSaZKcqz0tpi3pvcg8rimtBIwDpIdCBbF1zK3fOX7vG4Ma76mujP9Nszix6gEtSRFAX4Pq4o7rju4Xc5tpmrs81LmHmXuRapfVJe-HIf7DlbWeVxsP5dTm6kqg99W6NKI5Tji38vJ-3R2-yH3l6r9lA5C5k5V1caFAL8u93-ULopaxcRosHIUrFp5GshRtHC3QvcwVSeNcupRumB-K9L9G7wYGw1eGwAA)