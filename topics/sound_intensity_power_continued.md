## Sound Intensity Power and Pressure Level Adding Sounds Intensity Continued.. MU610A
## Edward Costello



#### Recap

- The 3 ways to measure energy of sound present and be able to define each relationship between loudness and intensity
- Sound Intensity Level (SIL)
- Sound Power Level (SWL)
Note:
SIL Power per unit area
SWL Total energy radiated in all directions per unit time



#### Recap
- Sound Pressure Level (SPL)
- Weber-Fechner Law
- Linear VS Logarithmic
- Correlated and uncorrelated sound sources and their relationship with phase

Note:
SPL Amplitude of a wave at a certain point in time
Weber Fechner: An increase in intensity from an arbitrary unit of 1 to 10 provides the same increase in perceived loudness as a rise from 10 to 100.




#### Key Topics

- SPL and Decibels
- Adding correlated and uncorrelated sounds
- Impact of phase
- Inverse Square Law
- Sound Interactions
- Sound Refraction, Absorbtion, Reflection
- Reverb
- Diffraction



#### Sound Pressure
- Because human ears are sensitive to pressure, it is easy to use pressure as a measure of the amplitude of a sound wave
- The unit for a pressure measurement is the Pascal ($Pa$) 
- The sound pressure for real sound sources can vary from 20 micropascals ($20\mu Pa$) to greater than 20 pascals ($Pa$)
- Thus, real sounds can vary over a range of amplitudes that is greater than a million



#### Sound Pressure Level

- Because sound is the result of a variation of pressure, in order to measure sound, we need to measure this variation. 
- One way to quantify a variation, or a relationship between two numbers, is to use a ratio number, i.e. the quotient of the two numbers. 



#### SPL

- In order to obtain absolute measurements, one of the two numbers must be a known reference. 
- The reference for Sound Pressure Levels (SPL) is the threshold of hearing and is defined worldwide
$p_0 = 20 \times 10^{-6} Pa = 20 \mu Pa$



#### Scaling and Decibels

- However this ratio is not very practical due to the extremely large range of variations that the human ear can perceive. 
- We need to scale down these variations. This is the role of the logarithmic function.
- A power ratio scaled by a logarithmic function is called a decibel unit $dB$



#### Decibels

- Therefore, a Sound Pressure Level (SPL) can be expressed in $dB$ as follows:
- $dB$ $SPL = 10 \log_{10} \big( \frac{p^{2}}{p^{2}_0} \big)$

$ = 20 \log_{10} \big( \frac{p}{p_0} \big) $ 



#### SPL Illustration

<img src="./images/SoundIntensity/image3-12.png"></img>



#### Figure Legend

- The blue dots represent the air molecules. They are dense in the compression stage and sparse in the rarefaction one.  
- In this example, the pressure variations are: 
    - (a) $45\times 10^{-6} Pa$, 
    - (b) $20\times 10^{-6} Pa$ and 
    - (c) $60\times 10^{-6} Pa$ 



#### Figure Legend
- The preferred unit to measure these variations is the decibel SPL unit: 
    - (a) $20 \log_{10}\big(\frac{45}{20}\big) = 7 dB$ $SPL$, 
    - (b) $20 \log_{10}\big(\frac{20}{20}\big) = 0 dB$ $SPL$, 
    - (c) $20 \log_{10}\big(\frac{60}{20}\big) = 9.5 dB$ $SPL$, 

Note: 
the minimum variation that the human ear can perceive is 20.10−6 Pa. Therefore, any variation smaller than (b) is not audible.



#### Example Intensities

| Sound Source  | Typical $dB$ $SPL$ | 
| ------------- |:-------------:| 
| Chainsaw | 110$dB$ |
| Vacuum Cleaner | 70$dB$ |
| Speech | 60$dB$ |
| Whispering | 40$dB$ |
| Threshold of Pain | 130$dB$ |
| Threshold of Hearing | 0$dB$ |



#### More Examples

- Calculate the $SPL$ for sound waves with pressure amplitudes of $1Pa, 2Pa$ and $2 \mu Pa$
- Doubling the pressure results in a $6 dB$ increase in the $SPL$
- A tenfold increase in the pressure results in a  $20 dB$ increase in the $SPL$



#### More Examples

- $SPL = 20 \log_{10} \big( \frac{p{actual}}{p{ref}} \big)$ 

 $= 20 \log_{10} \big( \frac{1Pa}{20 \mu Pa} \big)$

 $= 20 \log_{10} \bigg( \frac{1}{20 \times 10^{-6}} \bigg)$

 $= 94dB$



#### More Examples

- $SPL = 20 \log_{10} \big( \frac{p{actual}}{p{ref}} \big)$ 

 $= 20 \log_{10} \big( \frac{2 \mu Pa}{20 \mu Pa} \big)$

 $= 20 \log_{10} \bigg( \frac{2 \times 10^{-6}}{20 \times 10^{-6}} \bigg)$

 $= -20dB$



#### Adding sounds together

- Two situations can be considered:
- Correlated Sound sources - sources are related; they are derived from a single source and differ by just a short delay or are from the same electrical source (e.g. from multiple loudspeakers)
- Uncorrelated sound sources - sources are unrelated; they are the same but with a long time difference; or are from multiple different sources



#### Correlated Sources

<img src="./images/SoundIntensity/image8-19.png"></img>




#### Uncorrelated Sources

<img src="./images/SoundIntensity/image9-21.png"></img>



#### Addition of correlated sounds

- As we covered last week.... they simply add
- $P_{total}(t)=P_1(t)+P_2(t)+\ldots+P_n(t)$
- Correlated waves are understood to have the same frequency
- However, the phase of the different waves will impact on the size of the final waveform



##### Impact of phase
Note:
Show in grapher



#### Example

- The sound at a particular point consists of a main loudspeaker signal and a reflection at the same amplitude that has been delayed by 1 millisecond. 
- What is the pressure amplitude at this point at 250Hz, 500Hz, and 1KHz?



#### Example

- $P\_{\text{at a point}} = P\_{\text{Sound Amplitude}} \sin(2 \pi f t)$
- Where $f$ is the frequency in $Hz$ and $t$ is the time in seconds
- The effect of the delay is to change the time of the arrival of the wave by a value of $\tau$ (in seconds)

- $P\_{\text{delayed}} = P\_{\text{Sound Amplitude}} \sin(2 \pi f (t - \tau))$



#### Example
- Adding the delayed and undelayed sinewaves together
- $P\_{\text{total}} = P\_{\text{at a point}} +  P\_{\text{delayed}}$
- $P\_{\text{Sound Amplitude}} = \big( \sin{2 \pi f t} + \sin{2 \pi f (t - \tau)} \big)$
- Using trigonometry we can figure out the addition of the two sinewave terms



#### Trigonometric Addition

- $ \sin{2\pi f t} + \sin{2 \pi f (t - \tau)} =$

- $ 2 \sin{\big(\frac{2\pi f t + 2 \pi f (t - \tau)}{2}\big)} \cos{\big(\frac{2\pi f t - 2 \pi f (t - \tau)}{2}\big)}$
 
 because:

$\sin(u) + \sin(v) = 2\sin{\frac{u+v}{2}} \cos{\frac{u-v}{2}} $

- $ 2 \sin{\big(\frac{4\pi f t - 2 \pi f \tau}{2}\big)} \cos{\big(\frac{2\pi f \tau)}{2}\big)}$

- $= 2\sin(2\pi f(t - \frac{\tau}{2}))\cos(\pi f \tau)$



#### Example 

- $P\_{\text{total}} = P\_{\text{Sound Amplitude}} (2\cos(\pi f t)\sin(2 \pi f (t - \frac{\tau}{2})))$

- $= 2\cos(\pi f t) P\_{\text{Sound Amplitude}} \sin(2 \pi f (t - \frac{\tau}{2})))$

- This equation shows and amplitude term: $2\cos(\pi f t)$



#### Example

- And a frequency term of the original sine wave delayed by $\frac{\tau}{2}$,  $\sin(2 \pi f (t - \frac{\tau}{2}))$

- The effect of the delay on the total Pressure Amplitude at different frequencies can then be calculated



#### $f = 250Hz$

- $2 \cos(\pi f \tau) P\_{\text{Sound Amplitude}}$

- $f=250Hz$ and $\tau = 1 \times 10^{-3}$seconds

- $=2 \cos(\pi \times 250 \times 1 \times 10^{-3}) P\_{\text{Sound Amplitude}}$

- $=2 \cos\big(\frac{\pi}{4}\big) P\_{\text{Sound Amplitude}}$

- $= 1.41 P\_{\text{Sound Amplitude}}$



#### Plots of Direct and Reflected Sinusoid

<img src="./images/SoundIntensity/image11-33.png"></img>



#### Plots of Combined Output

<img src="./images/SoundIntensity/image12-35.png"></img>



#### $f = 500Hz$

- $2 \cos(\pi f \tau) P\_{\text{Sound Amplitude}}$

- $f=500Hz$ and $\tau = 1 \times 10^{-3}$seconds

- $=2 \cos(\pi \times 500 \times 1 \times 10^{-3}) P\_{\text{Sound Amplitude}}$

- $=2 \cos\big(\frac{\pi}{2}\big) P\_{\text{Sound Amplitude}}$

- $= 0 P\_{\text{Sound Amplitude}} = 0$



#### Plots of Direct and Reflected Sinusoid

<img src="./images/SoundIntensity/image13-38.png"></img>



#### Plots of Combined Output

<img src="./images/SoundIntensity/image14-40.png"></img>



#### $f = 1000Hz$

- $2 \cos(\pi f \tau) P\_{\text{Sound Amplitude}}$

- $f=1000Hz$ and $\tau = 1 \times 10^{-3}$seconds

- $=2 \cos(\pi \times 1000 \times 1 \times 10^{-3}) P\_{\text{Sound Amplitude}}$

- $=2 \cos\big(\pi\big) P\_{\text{Sound Amplitude}}$

- $= -2 P\_{\text{Sound Amplitude}}$



#### $f = 1000Hz$

- The delay of 1 millisecond for this waveform ives a delay of one complete period of the waveform because the period of a 1000Hz wave is 1/1000=0.001 seconds.
- Further, delaying the sinusoid by $\tau/2$ results in the wave starting at the halfway point in its period, just before the wave has its negative trajectory.
- This accounts for that although the pressure amplitude above is a negative value the resulting combination wave is completely in phase with the original.



#### Plots of Direct and Reflected Sinusoid

<img src="./images/SoundIntensity/image15-44.png"></img>



#### Plots of Combined Output

<img src="./images/SoundIntensity/image16-46.png"></img>



#### Adding uncorrelated sounds

- These do not add algebraically, instead the powers of the individual waves must be added together
- $P_{\text{total uncorrelated}}=\sqrt{P^2_1 + P^2_2 + ... + P^2_N}$
- The phase of the sources has no impact here so there will always be an increase in level



#### Adding uncorrelated sounds

- The maximum amplitude increase for two uncorrelated sources is only $\sqrt{2}$
- Example: calculate the increase in signal level when two vocalists sing together at the same level and when a choir of N vocalists sing together at the same level



#### Example

- $P_{\text{total uncorrelated}}=\sqrt{P^2_1 + P^2_2 + ... + P^2_N}$

- For N sources of the same amplitude this becomes

- $P_{\text{total uncorrelated}}=\sqrt{P^2_1 + P^2_1 + ... + P^2_1} = \sqrt{NP^2_1}$

- $=P_1 \sqrt{N}$

- In the case of two sources we have $P_1\sqrt{2}$



#### Adding Decibels together

- Note that adding logarithms is the equivalent of multiplying the quantities that the logarithms represent
- When Decibel quantities are added together it is important to convert them back to their original ratios before adding



#### Example

- Calculate the increase in signal level when two vocalists sing together, one at 69dB and the other at 71dB SPL
- We use the equation for multiple uncorrelated sources
- $SPL = 10 \log\_{10} \big( \sum^{n}\_{i=1} 10^{\frac{SPL\_i}{10}} \big)$



#### Example

- $SPL = 10 \log\_{10} \big( 10^{69/10} + 10^{71/10} \big)$
- $=73.1 dB$



#### Inverse square law

- Sound propagates in three dimensions

- It does not travel as a constant beam, rather it spreads as it radiates from a source

- As it spreads it gets weaker because the further away the energy is spread more thinly



#### Inverse square relationship

- As the distance from the sound source is doubled, the intensity reduces by a factor of four 

- This is described as an inverse square relationship

- Other factors include absorption in air. These have more effect at higher frequencies so sound not only get quieter but duller too.



#### Inverse Square Law and the spread of energy

<img src="./images/SoundIntensity/image21-53.png"></img>



#### Inverse square relationship

- A convenient rule of thumb is that the sound intensity level reduces by 6dB every time we double the distance

- The Nearfield region is different, this is described by the region within the physical radius of the source

- In the Nearfield, the sound field can vary wildly depending on the local variation of the vibration amplitudes of the source




#### Diagram of sound intensity as a function of distance

<img src="./images/SoundIntensity/image22-54.png"></img>




#### Boundaries

- Many acoustic contexts involve the presence of boundaries near the sources or all the way around them (if in a room)

- The inverse square law still holds

- The effect of a boundary is to concentrate the sound power of the source into a smaller range of angles

- Each boundary increases the sound intensity at a point by 3dB due to increased directivity



#### Sound Interactions

- What happens when sound interacts with physical objects, or other sound waves, or changes in the propagation medium?

Note:
New section this is what happens when sounds interact



#### Superposition

- The pressure or velocity at a given point in space is simply the sum, or superposition, of the individual waves that are propagating through that point.

Note:
A definition:



#### Sound Refraction

- This is analogous to the refraction of light at the boundary of different materials.

- In the acoustic case it arises because the velocity of sound in air depends on the temperature

- The speed of sound increases with temperature