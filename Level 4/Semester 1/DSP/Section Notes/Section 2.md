# __Section 2__

- function overloading - object oriented language - according to the number of arguments

## __Matlab__
- object oriented languag, supports function overloading
  - The function is determined according to the number of arguments  
 <br/>
- sum function = sum the matrix elements (matlab)

- base unit in **matlab** --> matrix

- matrices multiplication: number of col == number of rows

- element wise multiplication: .*    (dot operator) 

<br/>  

## __Unit Impulse Function__

**unit impulse function:** If **multiplied** to any system it represents the system


**Plot function:** continuous  
**Stem function:** discrete 

<br/>

**Unit Impulse Function:**

``` Matlab
n=0;
imp = 1;
stem(n, imp, 'LineWidth', 2);
```


**Unit step VS Unit impulse:**
> unit step is a unit impulse for all values from 0 to inf.

## unit step:

### Code
``` Matlab
Range = 10;
n = [0:Range-1];
imp = ones(1, Range);
stem(n, imp, 'LineWidth', 2);
```


--------------------------------------------
<br/>

### __Sampling:__ 
**Nyquist Rate:**  == 2 * max Frequency  
**Sampling Rate:** >= 2 * max Frequency


**Aliasing:** cannot revert the function to its original value due to lack of samples.


### Sine: 
__sin(2 * pi * freq *t)__

<br/>

__Sin sampling:__  
**Code:**

``` matlab
f = 2;
fs = 2*f;         // Nyquist Rate
ts = 1/fs;
t = 0:ts:1;
x = sin(2*pi*f*t);

plot(t, x);
hold on
stem(t,x);
```






















