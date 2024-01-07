# hapax

- squarp hapax
- 2024-01-06: updated firmware

## firmware update

```mermaid
graph LR
laptop --> sd_card
sd_card -- copy .bin file to root --> bin_file
bin_file -- hold main encoder power on --> hapax
```
