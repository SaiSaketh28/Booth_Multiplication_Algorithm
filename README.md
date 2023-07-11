# Booth_Multiplication_Algorithm
* Booth's multiplication algorithm is a multiplication algorithm that multiplies two signed binary numbers in two's complement notation.
* Booth's algorithm can be implemented by repeatedly adding (with ordinary unsigned binary addition) one of two predetermined values A and S to a product P, then performing a rightward arithmetic shift on P. Let m and r be the multiplicand and multiplier, respectively; and let x and y represent the number of bits in m and r.
* Language - Verilog

# Test Benche Result:
![image](https://github.com/SaiSaketh28/Booth_Multiplication_Algorithm/assets/97435804/ff9cd0b4-a16b-4252-bb83-3ff82157f57f)

Result on the monitor:
*  0ns :        -16 * -16 =    256
* 10ns :       -107 *  32 =  -3424
* 20ns :          7 *   0 =      0
* 30ns :          1 *   1 =      1
* 40ns :         60 *   5 =    300
* 50ns :        -86 *  35 =  -3010
* 60ns :         17 *  28 =    476
* 70ns :          8 * -65 =   -520
