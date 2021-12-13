# Sub-GHz-IQ-signals-dataset
Dataset with IQ signals captured from multiple Sub-GHz technologies (Sigfox, LoRA, IEEE 802.15.4g, IEEE 802.15.4 SUN-OFDM, IEEE 802.11ah)


## Summary

We provide a dataset with IQ signals captured from multiple Sub-GHz technologies. Specifically, the dataset targets wireless technology recognition (machine learning) algorithms for enabling cognitive wireless networks. The Sub-GHz technologies include Sigfox, LoRA, IEEE 802.15.4g, IEEE 802.15.4 SUN-OFDM and IEEE 802.11ah.

The dataset was captured using a [RTL-SDR](https://www.rtl-sdr.com/) at a sampling rate of 2.048 MHz using coaxial cables. Two center frequencies (864.0 MHz and 867.4 MHz) were considered to cover all considered channels of the wireless Sub-GHz technologies. The following settings for the various technologies have been considered:

| Technology             | Center frequency    | Bandwidth | Modulation / setting                  | 
| --------               | --------            | --------  | --------                              |
| LoRa                   | 868.1 MHz           | 125 MHz   | Spread spectrum SF 7                  |
|                        | 868.1 MHz           | 125 MHz   | Spread spectrum SF 12                 |
| Sigfox                 | 868.2 MHz           | 100 Hz    | BPSK (400 chan.)                      |
| IEEE 802.11ah          | 863.5 MHz           | 1 MHz     | MCS 0, 10 (BPSK) and 7 (64-QAM)       |
|                        | 864.0 MHz           | 2 MHz     | MCS 0 (BPSK) and 7 (64-QAM)           |
|                        | 864.5 MHz           | 1 MHz     | MCS 0, 10 (BPSK) and 7 (64-QAM)       |
|                        | 866.0 MHz           | 2 MHz     | MCS 0 (BPSK) and 7 (64-QAM)           |
| IEEE 802.15.4 SUN-FSK  | 868.1 MHz           | 200 KHz   | BFSK                                  |
| IEEE 802.15.4 SUN-OFDM | 863.625 MHz         | 1.2 MHz   | MCS 2 (OQPSK)                         |
|                        | 863.425 MHz         | 800 KHz   | MCS 2 (OQPSK)                         |
|                        | 863.225 MHz         | 400 KHz   | MCS 2 (OQPSK)                         |
|                        | 863.125 MHz         | 200 KHz   | MCS 2 (OQPSK)                         |
|                        | 863.125 MHz         | 200 KHz   | MCS 6 (16-QAM)                        |

More information can be found in [1].

Please always refer to our publication [1] when using our dataset.

[The dataset can be downloaded here.](https://cloud.ilabt.imec.be/index.php/s/bqXtdp9QsfXLbb3)

## References
[1] Fontaine, J., Shahid, A., Elsas, R., Seferagic, A., Moerman, I., & De Poorter, E. (2020, November). Multi-band sub-GHz technology recognition on NVIDIA’s Jetson Nano. In 2020 IEEE 92nd Vehicular Technology Conference (VTC2020-Fall) (pp. 1-7). IEEE.

## Contact
If you need any further details about the dataset, then you can contact at jaron.fontaine@ugent.be or adnan.shahid@ugent.be

