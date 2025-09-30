The alarm register is a bit field where each bit represents a certain alarm condition. The alarm register is read only.

| Bit | Description       |
| --- | ----------------- |
| 0   | Protection timer elapsed. One of the protection timers has elapsed. |
| 1   | High alarm. An input bit has gone high and the alarm condition for it is enabled.  |
| 2   | Low alarm. An input bit has gone low and the alarm condition for it is enabled.  |
| 3   | Reserved. |
| 4   | Reserved. |
| 5   | Reserved. |
| 6   | Reserved. |
| 7   | Reserved. |

Alarm bits are cleared when read.

  
[filename](./bottom-copyright.md ':include')
