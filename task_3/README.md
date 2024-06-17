# Реализовать БИХ фильтр вида yk+1 = a * yk+b * xk+1. Размерность x, a, b составляет 8 бит,знаковые целые числа. a, b известны заранее, в процессе работы не меняются.Данные на вход поступают каждый такт. Операция умножения занимает два такта.

* Clone the repo
* Open terminal into directory

### Verilog:
*sudo chmod 777 run*

*./run*

### C:
*./IIR*

## Description
* run - bash script for build project and start GTKWave
* IIR.v - source code on verilog
* tb_IIR.v - test branch for IIR.v
* tas and test.vcd - autogenerate files for GTKWave
* IIR.c - source code on C PL
* IIR - build of C source code 
* gtkwave_out.gtkw - file for GTKwave 

