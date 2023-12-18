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
     Lab 2 - Command Line
     Lab 6 - Node.js and Pystache
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
# Lab 2 - Command Line
##### . I used WSL in Windows PowerShell to execute these commands (virtual box used first then I switched) 
     $ hostname 
     $ env
![Screenshot 2023-12-14 201254](https://github.com/dshah912/E322_Labs/assets/144179870/cbc0e6f1-dde9-438c-92a5-f58e24c4d719)

     $ ps
     $ pwd 
     $ git clone https://github.com/kevinwlu/iot.git
     $ cd iot
     $ ls
     $ cd
![Screenshot 2023-12-14 202839](https://github.com/dshah912/E322_Labs/assets/144179870/b6db055c-c109-4718-9ae0-71f1922f218a)

     $ df
     $ mkdir demo
     $ cd demo
     $ nano file
     $ cat file
     $ cp file file1
     $ mv file file2
     $ rm file2
![Screenshot 2023-12-15 132659](https://github.com/dshah912/E322_Labs/assets/144179870/c44495e7-43d9-4aba-8f12-a6de9c1144b6)
     
     $ clear
![Screenshot 2023-12-15 132904](https://github.com/dshah912/E322_Labs/assets/144179870/6dc9b848-f9eb-4dd0-b038-fcdbd7eafdb5)

     $ man uname 
![Screenshot 2023-12-15 133037](https://github.com/dshah912/E322_Labs/assets/144179870/8b7e629b-9597-4636-8359-a7ef5e89b380)

     $ uname -a
     $ ifconfig
![Screenshot 2023-12-15 133254](https://github.com/dshah912/E322_Labs/assets/144179870/885cf262-b58f-489d-8a3c-9cb8f9aac5e5)

     $ ping localhost
     $ netstat
![Screenshot 2023-12-15 153522](https://github.com/dshah912/E322_Labs/assets/144179870/5a9e2c2d-ba86-4480-9223-1c92a60c5418)

# Lab 6 - Node.js and Pystache
##### .Install Node.js and run hello-world.js, hello.js, and http.js
##### .Install Pystache and run say_hello.py that uses the template in say_hello.mustache
#### First install Node.js
![Screenshot 2023-12-18 122713](https://github.com/dshah912/E322_Labs/assets/144179870/be4626b2-2782-4b98-8c5a-5d3142cee341)
#### Once installed I ran the below code to create a server
     $ node hello-world.js
![Screenshot 2023-12-18 123111](https://github.com/dshah912/E322_Labs/assets/144179870/c883a512-90c6-425a-bdf6-2f87ce4234e5)
![Screenshot 2023-12-18 123122](https://github.com/dshah912/E322_Labs/assets/144179870/ed7efa6a-00c1-4ae0-b5e9-fad9ce9cb6a4)
#### Next I ran hello.js    
     $ node hello.js
![Screenshot 2023-12-18 123914](https://github.com/dshah912/E322_Labs/assets/144179870/28c7d9e6-4913-4acf-b52f-9b6a7d726768)
##### The server ran but received an error preventing us from seeing the file contents
![Screenshot 2023-12-18 124904](https://github.com/dshah912/E322_Labs/assets/144179870/11697af2-7c9a-4ce5-a1ec-d7fa4a1d4c57)
##### Next I ran http.js
     $ node http.js
###### The server ran once again but this time no output was produced (no url address)
![Screenshot 2023-12-18 124731](https://github.com/dshah912/E322_Labs/assets/144179870/99a123b8-f078-4623-8b67-e99d6fce0dcc)
#### Installed Pystatche
![Screenshot 2023-12-18 125832](https://github.com/dshah912/E322_Labs/assets/144179870/caf80716-6ef3-42d7-9a6c-b5842974e925)
#### Then ran 
     $ py say_hello.py
![Screenshot 2023-12-18 125807](https://github.com/dshah912/E322_Labs/assets/144179870/5a534b5f-bf7a-446c-add4-06def059baaf)
