# Obj_Func_Modeling
An easy script to model an objective function for multiple MATPOWER cases

# Modeling of Transmission System Objective Function
### Select the Transmission System Test Case and Run:
![SelectCase](https://github.com/Heictor/Obj_Func_Modeling/assets/39010251/11d05712-8f1c-4eaa-a68c-0acb997026b6)


### Scattered Data Plot:
![MATPOWER Scattered Data](https://github.com/Heictor/Obj_Func_Modeling/assets/39010251/a9d3b052-72b5-4b5a-a2eb-b3be82861cd4)
### Polynomial Model Plot:
![MATPOWER Polynomial Function](https://github.com/Heictor/Obj_Func_Modeling/assets/39010251/222d4562-4093-4824-b8c3-81fcb1c04c06)
### **Polynomial function generated:**
```matlabTextOutput
     Linear model Poly55:
     fitresult(x,y) = p00 + p10*x + p01*y + p20*x^2 + p11*x*y + p02*y^2 + p30*x^3 
                    + p21*x^2*y + p12*x*y^2 + p03*y^3 + p40*x^4 + p31*x^3*y 
                    + p22*x^2*y^2 + p13*x*y^3 + p04*y^4 + p50*x^5 + p41*x^4*y 
                    + p32*x^3*y^2 + p23*x^2*y^3 + p14*x*y^4 + p05*y^5
       where x is normalized by mean 1.634e+04 and std 9572
       and where y is normalized by mean 300 and std 10.55
     Coefficients (with 95% confidence bounds):
       p00 =   3.805e+08  (3.787e+08, 3.822e+08)
       p10 =   4.312e+08  (4.278e+08, 4.345e+08)
       p01 =   1.852e+08  (1.818e+08, 1.885e+08)
       p20 =   1.218e+08  (1.193e+08, 1.244e+08)
       p11 =   2.145e+08  (2.124e+08, 2.166e+08)
       p02 =  -2.476e+07  (-2.735e+07, -2.218e+07)
       p30 =   3.662e+06  (-6.239e+04, 7.387e+06)
       p21 =   5.718e+07  (5.424e+07, 6.013e+07)
       p12 =  -2.045e+07  (-2.34e+07, -1.751e+07)
       p03 =   3.532e+07  (3.159e+07, 3.904e+07)
       p40 =   2.499e+05  (-6.696e+05, 1.169e+06)
       p31 =     5.5e+05  (-2.513e+05, 1.351e+06)
       p22 =   5.159e+06  (4.372e+06, 5.945e+06)
       p13 =   2.528e+07  (2.448e+07, 2.608e+07)
       p04 =   1.366e+07  (1.274e+07, 1.458e+07)
       p50 =  -8.222e+05  (-1.881e+06, 2.369e+05)
       p41 =   9.823e+05  (6.278e+04, 1.902e+06)
       p32 =   1.306e+06  (4.096e+05, 2.202e+06)
       p23 =    7.53e+06  (6.634e+06, 8.426e+06)
       p14 =   1.252e+07  (1.16e+07, 1.344e+07)
       p05 =  -4.416e+06  (-5.475e+06, -3.357e+06)
```
