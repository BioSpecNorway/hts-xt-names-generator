# hts-xt-names-generator
The macros which helps to generate all permutations for given experiment parameters for Opus Software (HTS-XT)

## How to use

In order to use HTS-XT unit you need to give names for each cell. Usually your experimental setup has different parameters, for example, different bacterias, grown with different temperatures and different amout of some substance.

For example you have 3 bacteria, 3 temperatures (15C, 25C, 40C) and 3 amounts (5mm, 10mm, 15mm).
Now you need to produce 3x3x3 = 27 names for each experiment: 

* Bacteria1_15C_5mm
* Bacteria1_15C_10mm
* ...
* Bacteria3_40C_15mm

That's what this macros does. It helps you to produce all permutations of all your parameters.

### 1. Run macros

![Run macros](/../images/01_run_macros.png)

### 2. Enter how many attributes you have 

![Run macros](/../images/02_sections_number.png)

### 3. Enter values for each attribute

* You should put each option in a new line
* All whitespaces at the start and end of option will be trimmed (removed)
* Empty lines will be skipped

![Run macros](/../images/03_section1.png)
![Run macros](/../images/04_section2.png)
![Run macros](/../images/05_section3.png)

# Warning: After last step active sheet will be fully cleared
### 4. Your results are ready

![Run macros](/../images/06_result.png)
