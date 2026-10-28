In my experience taking college level chemistry courses in high school and talking to my peers taking chemistry for the first time in college, 
I've found most students struggle with stoichiometry and concentration calculations. These calculations involve taking standard metric measurements of 
chemical compounds, such as liters and grams, and converting them to the appropriate chemistry units, moles or molars. 
The calculations are relatively simple mathematically, but can be difficult to conceptualize and apply for new chemistry students. So, I decided to create 
a calculator that can solve the problems for you.

The calculator acts closer to a chatbot than calculator. The code starts by promoting the user to "Input if [they're] solving a stoichiometry or molarity problem?," 
The code then takes in user inputs and by using a while troop where each if statement prints new questions about the problem the user is trying to solve. For example,
after the user inputs "stoichiometry", the code asks what the unknown of the question is, printing "Please input the unknown: mass or number of moles?" Then, a simmilar
process occurs where once the user inputs "mass" or "number of moles," the code will prompt (in this case assuming the user initially input was mass) the user to enter
the "chemical compound of the substance with capitalization of elements (eg. H2O):" and "number of moles:." For the compound, the code uses a Pycharm library that
intakes the string form of the element and takes the compound name and produce its molar mass. Then, the user input for the number of moles is transformed into a float
which is multiplied by the molar mass of the compound, yieleding the mass in grams of the substance, which is then printed as the final result. A similar process occurs
for molarity problems, instead with three unknowns that can be solved for, assuming there are two unknowns: the molarity, number of moles, or volume. 
