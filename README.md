# Adversarial-Attacks-and-Defense-Methods-for-DL-CE

## Problem Setup

DL-based techniques replacing traditional prediction algorithms in wireless systems. Communication is VERY security sensitive. 

## Project Scope

We develop novel adversarial attacks, and study defence methods on Deep Learning based channel estimation in wireless communications.

## Channel Estimation 

Channel estimation is the process of determining the effect of the physical communication channel on the signal sent from a transmitter to a receiver. We do channel estimation because the channel introduces impairments that alter the signal's characteristics – attenuation, phase shift, multipath fading, doppler spread. The process of channel estimation is usually with pilot symbols + LS, MMSE, or Deep Learning. 
OFDM is a digital modulation scheme that splits a high-rate data stream into lower-rate streams, transmitted over multiple, orthogonal subcarriers. Since both the frequency (subcarriers) and time (OFDM symbols) dimensions are used, the channel becomes realizable in 2D as an image. For DL-based channel estimation, CNNs are popular because of their image processing capabilities, and LSTMs are suitable for time-series. 

## Adversarial Attacks on DL-based Channel Estimation

Traditional Attacks: We can perturb (add noise to) the input signal to make predictions go wrong. Attacks like FGSM/PGD/BIM require access to specific inputs. And that is NOT possible due to processing latency. 

 











