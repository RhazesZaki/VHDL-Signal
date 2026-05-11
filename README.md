# VHDL, GTKWave, and Yosys

Simple AND and OR gate using VHDL.

$A' + B' + CD'$

## fill in for coding
```bash
nano logic0.vhd
nano tb_logic0.vhd
nano logic0.dot
```

## Run
```bash
ghdl -a logic0.vhd
ghdl -a tb_logic0.vhd
ghdl -e tb_logic0
ghdl -r tb_logic0 --vcd=wave.vcd
```

## GTKWave
```bash
gtkwave wave.vcd
```

## Yosys
```bash
dot -Tpng logic0.dot -o logic0.png
open logic0.png
```

## Output
```bash
![logic0.png](https://github.com/RhazesZaki/VHDL-Signal/blob/d0f55f7e726de454c09f3a825b6423c8503b846d/logic0.png)
```
