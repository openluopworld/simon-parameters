# simon-parameters
The standard parameter of SIMON-64-128 is (8, 1, 2). And [Simeck] gives the parameter (5,0,1). Some other parameters are given in the paper [Observation on the SIMON block cipher family]. The code tries to evaluate the software performance based on ATmega128.

Only one block of encryption is taken into consideration.

|   Parameter   |  Flash(bytes) |   Time(cycles)  |
|   --------    |  -----------  |   -----------   |
| (8,1,2)       |               |                 |
| (5,0,1)       |               |                 |
| (12,5,3)      |               |                 |
| (7,0,2)       |               |                 |
| (1,0,2)       |               |                 |

  [Simeck]:<https://eprint.iacr.org/2015/612.pdf>
  [Observation on the SIMON block cipher family]:<https://eprint.iacr.org/2015/145.pdf>