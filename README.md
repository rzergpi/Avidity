# Avidity
Avidity index and repeatability between sample replicates
The code needs a CSV file with the format seen below

Exp,Samples,M.09,M.18,M.375,M.75,M1.5,M3
0,GuHCl,-1.028028724,-0.726998728,-0.425968732,-0.124938737,0.176091259,0.477121255
1,A01,0.307,0.268,0.316,0.261,0.185,0.115
1,A01,0.253,0.27,0.289,0.305,0.2,0.121
1,A02,0.122,0.11,0.106,0.09,0.082,0.049
1,A02,0.104,0.112,0.101,0.094,0.081,0.059
1,A03,0.476,0.492,0.473,0.438,0.367,0.289
1,A03,0.505,0.459,0.484,0.456,0.367,0.327
14,B01,0.39,0.378,0.395,0.31,0.199,0.165
14,B01,0.396,0.358,0.429,0.353,0.194,0.153
14,B02,0.391,0.391,0.482,0.423,0.352,0.27
14,B02,0.372,0.368,0.51,0.391,0.341,0.214
14,B03,0.116,0.123,0.099,0.103,0.073,0.058
14,B03,0.111,0.127,0.108,0.101,0.077,0.057


The second row should always have the different concentrations of a chaotropic agent (in this case GuHCl).
First column has the experiment identifiers. If more than 2 experiments are loaded certain parts of the code will be executed.
Second column has the Sample identifiers. Two or more repetitions are required for each sample to check repeatability of sample replicates.
Third column and beyond must have the corresponding chaotropic agent molar concentration expressed as logarithm (base 10) in the second row and all values for each sample replicate in the appropiate rows.
The set of data shown will work with the code, if a demonstration is needed.
