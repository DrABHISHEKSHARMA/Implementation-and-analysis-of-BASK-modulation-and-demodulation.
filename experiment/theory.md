## Theory

####  Binary Amplitude Shift Keying (BASK) -
<p>
    Modulation process in digital communication corresponds to switching the <b>amplitude</b>, <b>frequency</b> or <b>phase</b> angle</b> of the carrier signal in accordance with the modulating signal. Depending on the parameter used to alter the modulation frequency.
    Three basic digital modulation techniques called binary <b>amplitude shift keying(BASK)</b>, <b>binary frequency shift keying(BFSK)</b> and <b>binary phase shift keying(BPSK)</b>.
    <br>
    
In the <b>BASK modulation technique</b>, digital data is represented by varying the amplitude of a carrier signal. The BASK signal scan be varied by changing binary 0 or 1 in accordance with the message signal. BASK is also known as <b>on-off keying</b>. In this, the <b>frequency</b> and <b>phase of the carrier signal</b> are kept <b>constant</b>.

Mathematically, BASK(t) can be defined as:

            BASK(t) = (Acsin(2πfct) -----> binary 1
                      (0)           -----> binary 0 
            where, Ac is a constant amplitude and fc is the carrier frequency.
<br> 


 ```
                              ┌────────────┐        ┌────────────┐
                              |            |        |            |
 Modulated BASK Signal -----> |  Rectifier | -----> |RC Low- pass| -----> Demodulated BASK Signal
                              |            |        |   Filter   |
                              └────────────┘        └────────────┘
 ```
</p>
