# X210Ai NixOS Config

Backup and reproducible config for my personal [NixOS](https://nixos.org) system, currently configured for an [X210Ai](https://macdat.net/laptops/jxtech/x210ai.php). Also some notes.

![Desktop Screenshot](./.desktop.png)
![X210Ai](./.X210Ai.png)

---

## X210Ai To-do List (hardware):
- reverse engineer fan control (EC) and make it less stupid
- !!NEW!! get an [Arrow Lake X210Ai mobo](https://www.tpart.net/newsfiles/x210ai-new-batch-now-available-for-pre-order/)
- T420 touchpad transplant
- [coreboot port](https://github.com/WheeledCord/coreboot-x210ai) testing
- X220 keyboard improvements
  - ThinkLight/power button wiring
  - interposer/translator board to use native EC
  - better mechanical retention
- undervolting + fine-tune PLs
- heatsink issues

## Completed stuff
- X220 keyboard retrofit
  - palmrest modifications
  - keyboard shimming
  - SK-8855 board on internal USB port
  - temporary power switch piggybacked off original keyboard cable
- epoxy reinforce headphone/mic TRS + optical port
- eGPU: passive M.2->OCuLink adapter, 3DP HDD bay bezel adapter
- thermals: exhaust baffle trimming, heat pipe + VRM insulation, PTM7950, RAM + NVMe heatsinks
- lid reinforcement
