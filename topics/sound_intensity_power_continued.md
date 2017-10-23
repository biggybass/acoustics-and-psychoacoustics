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
- Thus, real sounds can vary over a range of amplitudes that is greater than a factor of million



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

 $= 20 \log_{10} \big( \frac{2Pa}{20 \mu Pa} \big)$

 $= 20 \log_{10} \bigg( \frac{2}{20 \times 10^{-6}} \bigg)$

 $= 100dB$



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

- This equation shows an amplitude term: $2\cos(\pi f t)$



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

- The delay of 1 millisecond for this waveform gives a delay of one complete period of the waveform because the period of a 1000Hz wave is 1/1000=0.001 seconds.
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

<img src="./images/SoundIntensity/isqb.gif" style="background:white"></img>



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



#### Sound Refraction

- Thus, as sound moves from cooler to hotter air it is refracted away from the normal direction  and it is refracted towards the normal direction when moving from hotter to colder air

- For outdoor sound, this means that as air temperature reduces as a function of height it results in sound being bent upwards as it moves away from a sound source 



#### Sound Refraction

<img src="./images/SoundIntensity/image24-56.png"></img>



#### Shadow Zone 

- The wave changing direction and bending upwards can create a "shadow zone" region into which the sound wave cannot penetrate.
 
- A person standing in the shadow zone will not hear the sound even though he/she might be able to see the source. The sound waves are being refracted upwards and will never reach the observer.



#### Shadow Zone 

<img src="./images/SoundIntensity/image25-57.jpeg"></img>




#### Sound Refraction

- This means that listeners on the ground experience a reduction in sound level as they move away from the sound, and it reduces more quickly than the inverse square law predicts.

- This help to reduce the nuisance effect of environmental noise



#### Example

- Another example is suppose a group are camping on the shore of a lake which is not too wide, maybe 1km across. During the day the campers on the other side of the lake can be seen but not heard. At night, however, they can be both seen and heard as they sit around their camp fire.



#### Inversion

- This effect is due to a temperature inversion is when the temperature is coolest right next to the ground and warmer with respect to increasing height above the ground. 

- Since the temperature increases with height, the speed of sound also increases with height. This means that for a sound wave traveling close to the ground, the part of the wave closest to the ground is traveling the slowest, and the part of the wave farthest above the ground is traveling the fastest. 



#### Inversion

- Because of diffraction, the faster wave will change direction and bends downwards. 

- Temperature inversions most often happen at night after the sun goes down when the ground (or water in a lake) cools off quickly, while the air above the ground remains warm. 




#### Inversion Effect 

<img src="./images/SoundIntensity/image26-59.jpeg"></img>



#### Absorption, Reflection and Diffusion

- Sound may be absorbed, transmitted or reflected. This occurs when sound interacts with any physical object.

- When a room boundary, such as a roof, floor or a wall, is hit by a sound wave, some of the sound energy will be reflected, some is absorbed within the material and some is transmitted through it



#### Absorption, Reflection and Diffusion

<img src="./images/SoundIntensity/image27-61.gif"></img>



#### Sound Absorption

- This happens because when sound hits an object then it will vibrate unless it is infinitely rigid. So, energy is transferred from the wave to the object. 

- Sound absorption is defined, as the incident sound that strikes a material that is not reflected back. 



#### Sound Absorption

- An open window is an excellent absorber since the sounds passing through the open window are not reflected back but makes a poor sound barrier. 

- A painted concrete block is a good sound barrier and will reflect about 97% of the incident sound striking it.



#### Sound Absorption - Acoustical Material

- Conventionally speaking, acoustical materials are those materials designed and used for the purpose of absorbing sound that might otherwise be reflected.



#### Sound Absorption - Acoustical Material

<img src="./images/SoundIntensity/image28-63.gif"></img>




#### Sound Absorption - Acoustical Material

- There is a marked loss in energy when the sound travels through a porous material.

- There is a very large surface area of interaction in the material, due to the fibres and holes. There are frictional losses at the surface due to the interaction of the sound material with the surface.

- Thus, such properties will causes a higher energy loss which is why porous material such as cloth or rockwool are used for absorbing sound waves



#### Sound Absorption - Acoustical Material

- The more fibrous a material is the better the absorption; conversely denser materials are less absorptive. The sound absorbing characteristics of acoustical materials vary significantly with frequency. 

- In general low frequency sounds are very difficult to absorb because of their long wavelength. On the other hand, we hear low frequencies less well than high frequencies, which can be to our benefit in many cases.



#### Sound Absorption - Acoustical Material

- For the vast majority of conventional acoustical materials, the material thickness has the greatest impact on the material's sound absorbing qualities. 

- While the inherent composition of the acoustical material determines the material's acoustical performance, other factors can be brought to bear to improve or influence the acoustical performance. Incorporating an air space behind an acoustical ceiling or wall panel often serves to improve low frequency performance.



#### Sound Reflection

- Sound is also reflected when it strikes objects.

- There are two main situations:



#### Sound Reflection

- Hard Boundaries : Reflection from a solid boundary results in a reflected pressure component that is out of phase with the incoming wave. This is because the impedance of the boundary is greater than the propagating medium.
- Soft Boundaries: reflection from a bounded to an unbounded boundary results in in a pressure component that is in phase to the incoming wave. This is because the impedance of the boundary is less than the propagating medium.



#### Sound Reflection

- In the first case the sound waves strike an immovable object or hard boundary. The waves must bounce back in the reverse direction, resulting in a phase change in the velocity component of the wave



#### Sound Reflection

<img src="./images/SoundIntensity/image29-65.gif"></img>



#### Sound Reflection

- In the second case the sound moves from a bounded region (e.g. a tube) into an unbounded region (e.g. free space)

- In the unbounded region the molecules find it a lot easier to move

- This means that the sound wave has a pressure component that is close to zero and a large velocity component



#### Sound Reflection

- The reflection of a wave is in the reverse direction to the situation where the phase of the wave is reversed



#### Sound Reflection

<img src="./images/SoundIntensity/image30-67.gif"></img>



#### Sound Reflection - Building Material

- The amount of reflection is dependent upon the dissimilarity of the two media. For this reason, acoustically minded builders of auditoriums and concert halls avoid the use of hard, smooth materials in the construction of their inside halls. 

- A hard material such as concrete is as dissimilar as can be to the air through which the sound moves; subsequently, most of the sound wave is reflected by the walls and little is absorbed. 



#### Sound Reflection - Building Material

- Reflected sounds that are not absorbed will cause an increase in overall sound levels in a space. When the space is acoustically treated the sound build up is eliminated or reduced. 

- The sound level differences between the level of reflections in the untreated space and the acoustically treated space is described using the Noise Reduction Coefficient(NRC).




#### Sound Reflection - Buildings

- Treating a noisy reverberant space with acoustical materials can reduce the reflected sound build up that occurs due to the reflective hard surface

- Walls and ceilings of concert halls can be covered with softer materials such as fiberglass and acoustic tiles. These materials are more similar to air than concrete and thus have a greater ability to absorb sound energy, giving the room more pleasing acoustic properties.




#### Sound Absorbing and Sound Proofing Products

- Products that are designed and intended to absorb reflections/echo within a room are soft, light, fluffy products. They will generally feel soft to the touch. They are designed to soften up the surfaces within a room and reduce the echo in that space.



#### Sound Absorbing and Sound Proofing Products

- Products that are designed to block sound from entering or leaving a space are almost always found inside the wall construction. These products are heavy, dense, cumbersome, or designed to decouple the wall so that one side of the wall doesn't have hard surface contact with the other.



#### Reverb and Echo

- Reflection of sound waves off surfaces can lead to one of two phenomena - an echo or a reverberation. 

- If a reflected sound wave reaches the ear within 0.1 seconds of the initial sound, then it seems to the person that the sound is prolonged. The reception of multiple reflections off walls and ceilings within 0.1 seconds of each other causes reverberations - the prolonging of a sound. 



#### Reverb

- Since sound waves travel at about 340 m/s at room temperature, it will take approximately 0.1 s for a sound to travel the length of a 17 meter room and back, thus causing a reverberation. This is why reverberations are common in rooms with dimensions of approximately 17 meters or less. 



#### Echoes

- Reflection of sound waves also leads to echoes. Echoes are different than reverberations. Echoes occur when a reflected sound wave reaches the ear more than 0.1 seconds after the original sound wave was heard. 

- If the elapsed time between the arrivals of the two sound waves is more than 0.1 seconds, then the sensation of the first sound will have died out. 




#### Echoes
- In this case, the arrival of the second sound wave will be perceived as a second sound rather than the prolonging of the first sound. There will be an echo instead of a reverberation.



#### Reverberation

- Reverberation Time (RT) is defined as the number of seconds it takes for the reverberant sound energy to die down to one millionth (or 60dB) of itis original value from the instant that the sound signal ceases.

- Reverberation is dependent only on the volume of a space and the acoustically absorptive quality of the rooms finishes. Hard surfaced rooms will have a longer reverberation time than rooms finished with sound absorbing materials.



#### Reverberation

<img src="./images/SoundIntensity/image31-69.gif"></img>



#### Sound Reflection - Auditoriums

- In auditoriums and concert halls, reverberations can occur and can lead to the displeasing garbling of a sound.

- But reflection of sound waves in auditoriums and concert halls do not always lead to displeasing results, especially if it is designed to incorporate the reflections correctly.




#### Sound Reflection and Diffusion - Smooth Surfaces

- Smooth walls have a tendency to direct sound waves in a specific direction. 

- Subsequently the use of smooth walls in an auditorium will cause spectators to receive a large amount of sound from one location along the wall as there would be only one possible path by which sound waves could travel from the loudspeakers to the listener. 




#### Sound Reflection and Diffusion - Rough Surfaces

- Rough walls tend to diffuse sound, reflecting it in a variety of directions. The vibration thus travels along many smaller paths. This divides the energy of the wave which depletes its energy faster.

- The multitude of paths also allows a spectator to perceive sounds from every part of the room, making it seem lively and full. 




#### Sound Reflection and Diffusion - Rough Surfaces

- For this reason, auditorium and concert hall designers prefer construction materials that are rough rather than smooth.




#### Sound Reflection and Interference

- Whether waves add constructively or destructively depends on the relative phases and this depends on the distances that each had to travel.

- Because waves vary in space over their wavelength then the phase will also spatially vary. This means that constructive or destructive addition will also happen in space




#### Sound Reflections

- The destructive effects can be described as comb filtering, standing waves and flutter echoes which will degrade speech intelligibility and music clarity. 




#### Destructive Effects

- Comb Filtering: this is caused by strong early reflections. It causes coloration and can mask details. Subtle comb filtering can sound musical but a more severe effect is unwanted. 



#### Destructive Effects

- Flutter Echoes: Flutter Echoes are produced by sound traveling quickly between two parallel reflective surfaces. They are perceived as a ringing reverberation after the sound has stopped, and it has different effects on the mid- and high frequencies compared to the bass. Flutter echo affects music by blurring transients (fast musical attacks) and adding an unpleasant harshness to the midrange and treble.



#### Destructive Effects

- Standing waves: These are the result of resonances in the room frequency response that are determined by the room layout and dimensions. The effect is often perceived as a distortion to the Bass and midrange of the signal.



#### Sound Diffraction

- The fact that it is possible to hear sounds around corners and around barriers involves both diffraction and reflection of sound. 

- Diffraction in such cases helps the sound to "bend around" the obstacles. The fact that diffraction is more pronounced with longer wavelengths implies that it is easier to hear low frequencies around obstacles better than high frequencies.



#### Diffraction

- A good example of diffraction is the contrast in sound from a close lightning strike and a distant one. 

- The thunder from a close bolt of lightning will be experienced as a sharp crack, indicating the presence of a lot of high frequency sound. 

- The thunder from a distant strike will be experienced as a low rumble since it is the long wavelengths which can bend around obstacles to get to the observer. 

- There are other factors such as the higher air absorption of high frequencies involved, but diffraction is key.



#### Diffraction

<img src="./images/SoundIntensity/diffraction.jpg" height="600px"></img>
