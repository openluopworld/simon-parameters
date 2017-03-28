# simon-parameters
The standard parameter of SIMON-64-128 is (8, 1, 2).  Some other parameters are given in the paper [Observation on the SIMON block cipher family](https://eprint.iacr.org/2015/145.pdf). The code tries to evaluate the software performance based on ATmega128.

Only one block of encryption is taken into consideration.

|   Parameter   |  Flash(bytes) |   Time(cycles)  |
|   --------    |  -----------  |   -----------   |
| SIMON[8,1,2]  |               |                 |
| SIMON[12,5,3] |               |                 |
| SIMON[7,0,2]  |               |                 |
| SIMON[1,0,2]  |               |                 |