# FHSS-DSSS
Explain FHSS and DSSS with Examples

**FHSS**

Frequency
hopping spread spectrum (FHSS) is a method of transmitting radio
signals by shifting carriers across numerous channels with
pseudorandom sequence which is already known to the sender and
receiver.  
  
Frequency hopping spread spectrum is defined in the
2.4 GHz band and operates in around 79 frequencies ranging from 2.402
GHz to 2.480 GHz. Every frequency is GFSK modulated with channel
width of 1MHz and rates defined as 1 Mbps and 2 Mbps respectively.

Frequency
hopping spread spectrum is a robust technology with only very little
influence from reflections, noise and other environmental factors.
The active system numbers in same geographical areas is higher than
an equivalent number for direct sequence spread spectrum systems.
Thus it is suited well for installations designed to cover large
areas where numerous co-located systems are needed. They are also
used in cellular deployments for fixed broadband wireless access
where direct sequence spread spectrum cannot be used. A variation of
frequency hopping spread spectrum is adaptive frequency hopping
spread spectrum that improves resistance to radio frequency
interference by avoiding crowded frequency in hopping sequence.

#### Benefits
or advantages of FHSS

Following
are the benefits or advantages of FHSS:  
1. It provides very
robust transmission path in the presence of interferences such as
multipath, noise and other wireless transmissions etc. due to support
of wide bandwidth.   
2. It can be employed in point to multipoint
applications.   
3. It supports about ten nearby WLAN compliant APs
(Access Points) without any significant interference issues.   
4.
It provides security against any kind of intrusion as only
transmitter and receiver are aware of PN codes. 

![alt
text](http://www.rfwireless-world.com/images/DSSS-Transmitter-Receiver-Block-Diagram.jpg)

#### Drawbacks
or disadvantages of FHSS

Following
are the disadvantages of FHSS:  
1. As FHSS relies on carrier
frequencies to transmit information bits, it leads to strong bursty
errors due to frequency selective fading mainly.   
2. It supports
lower data rate of 3 Mbps compare to 11 Mbps supported by DSSS.   
3.
It supports lower coverage range due to high SNR requirement at
receiver.   
4. The modulation scheme has become obsolete due to use
of emerging wireless technologies in the wireless products. 

**Examples
**

1)
Wireless local area network (WLAN) standard for wi-fi

2) Wireless personal area
network (WPAN) standard of bluetooth.

**DSSS**

DSSS
is a spread spectrum modulation technique used for digital signal
transmission over airwaves. It was originally developed for military
use, and employed difficult-to-detect wideband signals to resist
jamming attempts. It is also being developed for commercial purposes
in local and wireless networks.  
  
The stream of information in
DSSS is divided into small pieces, each associated with a frequency
channel across spectrums. Data signals at transmission points are
combined with a higher data rate bit sequence, which divides data
based on a spreading ratio. The chipping code in a DSSS is a
redundant bit pattern associated with each bit transmitted. This
helps to increase the signal's resistance to interference. If any
bits are damaged during transmission, the original data can be
recovered due to the redundancy of transmission.   
  
The entire
process is performed by multiplying a radio frequency carrier and a
pseudo-noise (PN) digital signal. The PN code is modulated onto an
information signal using several modulation techniques such as
quadrature phase-shift keying (QPSK), binary phase-shift keying
(BPSK), etc. A doubly-balanced mixer then multiplies the PN modulated
information signal and the RF carrier. Thus, the TF signal is
replaced with a bandwidth signal that has a spectral equivalent of
the noise signal. The demodulation process mixes or multiplies the PN
modulated carrier wave with the incoming RF signal. The result
produced is a signal with a maximum value when two signals are
correlated. Such a signal is then sent to a BPSK demodulator.
Although these signals appear to be noisy in the frequency domain,
bandwidth provided by the PN code permits the signal power to drop
below the noise threshold without any loss of information.

#### Benefits
or advantages of DSSS

Following
are the benefits or advantages of DSSS:  
1. It uses both
time and frequency planes for transmission of information bits,
effect of interference and fading can be minimized to great extent.
  
2. It can be employed in point to point applications at the rate
of 11 Mbps.   
3. It supports higher coverage range due to low SNR
requirement at receiver. 

#### Drawbacks
or disadvantages of DSSS

Following
are the disadvantages of DSSS:  
1. It is very sensitive
technology in the presence of harsh environments such as collocated
cells, larger coverage areas, multipath and in the presence of
frequencies used for bluetooth network. This is due to the fact that
it operates at narrow bandwidth.   
2. The system is prone to errors
at lower level than FHSS. 

**Examples:**

1) To combact intentional
interferance (jamming)

2) To reject unintentional
interference

3) To minimize self
interferance due to multipath propogation

4) In the law probability of
intercept signal 

5) In obtaining message
privacy

6) Code division multiple
access with DSSS.
