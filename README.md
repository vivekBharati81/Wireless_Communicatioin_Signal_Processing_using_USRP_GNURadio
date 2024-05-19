# Real Time Wireless Communication and Signal Processing using USRP and GNU Radio

## Overview
Welcome to the real-time Wireless Communication and Signal Processing using Universal Software Radio Peripheral (USRP), RTL-SDR, and GNU Radio. The focus is on understanding the process of establishing data communication links with SDR hardware, utilizing GNU Radio for signal processing, and mitigating wireless channel impairments.

## Learning
1. **Real-time Wireless Communication with SDR**
   - Explored modulation techniques including BPSK, QPSK, and QAM for encoding digital data onto carrier signals.
   - Investigated coherent and non-coherent demodulation for accurately retrieving transmitted data.
   - Established data communication links with SDR hardware like USRP and RTL-SDR.

2. **GNU Radio for Wireless Signal Processing**
   - Explored signal processing concepts like upsampling the I & Q data, pulse shaping at Tx/Rx, the effect of ISI and its removal, clock recovery for correct sampling of received symbols, carrier recovery (frequency and phase synchronization) to enhance signal fidelity, and impact of frequency offset and methods to mitigate its effects.
   - Utilized Root Raised Cosine (RRC) filter at Tx and LPF at Rx to implement the pulse shaping, observed the effect of frequency offset on constellation points, used Polyphase Clock Sync block for clock recovery, and used Costas Loop for carrier recovery in PSK modulation schemes.

3. **Combating Wireless Channel Impairments**
   - .
   - Techniques and strategies to mitigate impairments and improve communication reliability.

4. **Packet Transmission Using GNU Radio**
   - Concepts and implementation of packet transmission in GNU Radio.
   - Practical examples and exercises to reinforce theoretical knowledge.
