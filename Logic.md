![Basic Logic Gates with Truth Tables](Basic-Logic-Gates-with-Truth-Tables.jpg)


### Mux
- O = S ? B : A
![mux](mux.png)

### Decoder
- n bit input, $2^n$ bit output
- exactly one bit in the ouput is $1$
- the input number denotes the index of $1$

### Adder
- adding bits A,B. Getting carry bit C and sum bit S
![half adder](carry_sum.png)
![](full_adder.png)

### ALU Design
### Propagation delay
![](propa_delay.png)


### Sequential Logic
#### SR Latch
![](srlatch.png)
#### D Latch
![](dlatch.png)
- G determines if new values are assigned
- D determines if Q is 0 or 1

- Hard to determine timing for the D Latch Gate
    - if gate opens for too long: cycle is propagated twice or more
    - if gates open for too short: not enough time to stablize value
#### Flip Flop
![](flipflop.png)

> when clock is on its rising edge, the data value passes into $Q$ and does not change until the next rising edge

![](flipflop2.png)
> Q only updated during rising edges where en is high

### Finite State Machine