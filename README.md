# Working with DataFrames.jl beyond CSV files

This is an introductory part of the workshop
prepared for [JuliaCon2023](https://juliacon.org/2023/).

In order to run the tutorial make sure that you have Julia executable installed.
The tutorial was developed under Julia 1.9.2.

The simplest way to run it is to proceed as follows:
1. Clone the
   [tutorial repository](https://github.com/bkamins/JuliaCon2023-Tutorial)
   to a local folder on your computer.
2. Start Julia in your local folder using the `julia --project` command.
3. Run the following commands (this step needs to be run only once per installation and is made to double check that you have proper versions of packages downloaded):
```
using Pkg
Pkg.instantiate()
Pkg.status()
```
4. Start Jupyter Notebook with:
```
using IJulia
notebook(dir=pwd())
```
5. In the Jupyter Notebook open and run the *ipynb* files with the tutorial material.

---

*Preparation of this workshop has been supported by the Polish National Agency for Academic Exchange under the Strategic Partnerships programme, grant number BPI/PST/2021/1/00069/U/00001.*

![SGH & NAWA](logo.png)
