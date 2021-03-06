# NC_GE_Evolved_Trading_Strategy

## Evolving Short-Term Trading Strategies with Machine Learning

Video summary:
https://youtu.be/nnNDyLz46Yc

Report:
https://github.com/eoincUCD/NC_GE_Evolved_Trading_Strategy/blob/master/MIS40980_Eoin_Carroll_16202781.pdf

Abstract:
The finance industry is often quick to adopt new technology and the application of natural computing techniques is a contemporary research area. This project aimed to derive and test genetically evolved trading strategies with a grammatical evolution algorithm. Four S&P 500 stocks were modelled over a 17-year period and trading strategies were generated. The results were marginally more profitable than a benchmark buy and hold strategy. 

## Code Notes
To run the program, copy all of the GE Program folder into a new directory.
Execute "run_ponyge.py" in the folder GE Program\src

The following files were modified from PonyGE2 for this project:
\src\fitness\pymax.py "trading.py" - The fitness function and stock selection
\grammars\pymax.pybnf "trading.pybnf" - The grammar
\parameters\pymax.txt "trading.txt" - Parameters file

Contact me with any questions and I would be happy to help!

Thanks to Michael Fenton for his support in implementing the powerful PonyGE2 library. 

Eoin Carroll
