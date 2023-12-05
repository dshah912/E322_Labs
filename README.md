# CPE-322-A 
___________________________________
## Deven Shah 
## Project Team Name: Contaxt
_________________________________
# Engineering Design 6
### Assignments
     Assignment 0: GitHub Repository
     Assignment 1: Project Site
     Assignment 2: Needs Assessment
     Assignment 3: Problem Formulation
     Assignment 4: Solution Development
     Assignment 5: Intellectual Properties
     Assignment 6: Abstraction and Modeling
     Assignment 7: Synthesis
     Assignment 8.1 and 9.1: Ethical Issues
     Assignment 8.2 and 9.2: Product Liability
     Assignment 8.3 and 9.3: Social Impacts
     Assignment 10: Design Analysis
     Assignment 11.1: Design Diagrams
     Assignment 11.2: Gantt Chart
     Assignment 11.3: Senior Design Plan
### Labs
     Lab 1: GHDL GTKWave
_______________________________________
# Lab 1 - GHDL and GTKWave
## Instructions:
     .Go to the GHDL folder
     .Install GHDL and GTKWave
     .Run the Half Adder example
     .Run another example such as D Flip-Flop or 4-to-1 Multiplexer
     .Document the results on your GitHub repository
## Half-Adder Example Code:
     $ ghdl -a ha.vhdl
     $ ghdl -a ha_tb.vhdl
     $ ghdl -e ha_tb
     $ ghdl -r ha_tb --vcd=ha.vcd
     ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
     $ export DISPLAY=:0
     $ gtkwave ha.vcd
![215637050-99fff18b-db58-4818-96e1-9f6105d51d07](https://github.com/dshah912/E322_Labs/assets/144179870/50f3c059-64bc-4bb3-bb5f-58a4942ae31a)
## D Flip Flop Example Code:
     $ ghdl -a dff.vhdl
     $ ghdl -a dff_tb.vhdl
     $ ghdl -e dff_tb
     $ ghdl -r dff_tb --vcd=dff.vcd
     $ export DISPLAY =:0
     $ gtkwave dff.vcd
![215637314-429526d2-4dd4-4ef8-bcc6-df8d55c6983e](https://github.com/dshah912/E322_Labs/assets/144179870/0c41e1e1-b149-4ffe-879c-4275c5b9cd4f)
## 4-to-1 Multiplexer
     $ ghdl -a mux.vhdl
     $ ghdl -a mux_tb.vhdl
     $ ghdl -e mux_tb
     $ ghdl -r mux_tb --vcd=mux.vcd
     $ export DISPLAY=:0
     $ gtkwave mux.vcd
![215922535-51b057cb-b620-4328-a0d8-d7ac483074b9](https://github.com/dshah912/E322_Labs/assets/144179870/a5bff104-2e0a-49cf-87e5-280988f0b8b4)



