# Convert Name to Elements
**Program Author:** Lachlan Xiu  
**Program Language:** Python  
**Program Interpreter:** Python 3.11  
**Program Reviewer:** PerryPerrySauce  
**Date Created:** 04/06/2025  
  
## Run Instructions:
Clone the repo into any directory accessible by a python interpreter >3 and run main.py.  
Input any string of characters, case insensitive, and the program will return that string spelled out of elemental shorthands, if such a spelling exists.  
  
## Description:
This is a very simple python program that spells out your name from the shortened versions of the elements of the periodic table.  
In the case that no spelling of the name exists, the program will inform you. In the case that multiple different spellings of the same name exist (due to some elements having single-letter shorthands), the program will output each. The program also gives you the numbers and names of the elements.  
**Reviewers Note:** This program runs in O(n<sup>3</sup>) time, which is fine since "names" tend to be short. Additionally, this program has a usecase: decomposing molecules in condensed formulas into their full names. I could see that being useful for exotic compounds or to assist with naming molecules.   