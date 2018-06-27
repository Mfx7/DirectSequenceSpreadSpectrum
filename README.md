## Introduction

The aim of our project is to make end to end simulation of Direct Sequence Spread Spectrum (DSSS) technique. It’s a technique that message signal is multiplied by a pseudo-random sequence to spread message bandwidth so energy of message signal expand a wider spectrum, and it appears as noise. The motivation of DSSS technique comes from channel-capacity theorem. It says that we can have good communication performance by increasing bandwidth even when signal-to-noise power is low. [1] DSSS increases transmit signal bandwidth to remove intersymbol interference (ISI) and narrowband interference. It provides security of transmission because receiver must know pseudo-random sequence to get transmitted data signal. Otherwise, receiver can’t detect original message signal, and it only sees transmitted signal as a noise. This property of DSSS technique make it suitable to use for military communication systems. DSSS also enables to usage of a bandwidth by multiple users because each user multiply its message signal by different pseudo-random sequence, and a receiver gets its message signal if it has transmitter pseudo-random sequence. The process of DSSS is shown below.  
![](https://github.com/mahmut-aksakalli/DirectSequenceSpreadSpectrum/blob/master/images/1.png)

<p align="center">
**Figure 1:** Block diagram of Spread Spectrum System [2]</center>
</p>
