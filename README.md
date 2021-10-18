# On-Chip-Clock-Multiplier (PLL) using OSU 180nm PDK  | VSD
This particular project is enodorsed and faciliated by VSD, and emphasizes on the development of an 'On-Chip-Clock-Multiplier' or PLL using OSU 180nm PDK. It comes as part of a 24-hour long tutorial/workshop initiated on 19th October, 2021.

### Introduction 

* Intellectual Property (IP): Pre-defined logical cells that are not built from scratch but are rather bought from IP vendors so that they can be used directly on a chip/core. RAM and ROM are few examples of IPs. This helps to reduce design and testing time significantly.

* On-Chip Clock Multiplier: Amplifies incoming low frequency clock signal into a high freqeuncy clock signal, in order to improve performance. This is especially required by processors that demand high frequency clock signals. Figure below demonstrates a typical implementation of a On-Chip Clock Multiplier using PLL. 

<p align="center">
  <img width="681" height="287" src="https://i.imgur.com/p6963Zc.png">
</p>

Processors come in two types - Synchronous and Asynchronous; those that require a clock signal are categorized as synchronouse and those that don't are categorized as asynchronous.

