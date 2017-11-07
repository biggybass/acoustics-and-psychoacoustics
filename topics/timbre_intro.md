## Timbre Introduction.. MU610A
## Edward Costello



#### Fundamental Items

- General definition of timbre
- Helmholtz model for timbre
- The three stage envelope
- Harmonic series
- The spectrum
- Bandwidth
- Fourier Transform



#### Timbre

- "Timbre is that attribute of auditory sensation in terms of which a listener can judge that two sounds similarly presented and having the same loudness and pitch are dissimilar." ["American national standard acoustical terminology" (1994). American National Standards Institute, ANSI S1.1-1994 (R1999)]



#### Timbre

- Timbre is clearly difficult to define
- It is related to the perceived tone qualities of classes of sound, sometimes called sound colour, in analogy to light
- It is, as above, difficult to characterise, much more so than loudness and pitch. It is multi-dimensional and cannot be characterised as a one dimensional scale, such as high/low or loud/soft.
Notes:
Brightnesss, roughness


#### Timbre

- Timbre constitutes a highly subjective area, as it deals with the individual's perception of sound. In order to form an objective as possible view of this area we will begin by looking at the classic definition of timbre and how we can decompose sounds down to their very basic make-up using the Fourier transform.




#### Timbre

- As we start to discuss the perception as opposed to the physical nature of sound we begin to move more and more towards an area of research known as psychoacoustics.
- Ultimately, the aim of studies of timbre is to to identify the different perceptual results of different physical changes to the sound and to organise these findings into some sort of graph based on a multi-dimensional 'timbre-space'



#### Timbre

- A lot of what we know today in relation to the basics of timbre was studied in the 19th century by Hermann von Helmholtz, in his classic work _On Sensations of Tone_. His studies laid the foundation of modern acoustics in the 20th century.



#### Timbre

- Helmholtz's model for a tone can be summarised as:
    1. A periodic waveform enclosed by an amplitude envelope.
    2. The sensation of pitch arises from periodic waveforms.
    3. Waveforms (ie: the shape of the waves) are essentially fixed and unchanging with time
    4. Timbre is greatly determined by the shape/nature of the waveform



#### Helmholtz's model for Musical tone

- Three stage envelope
- During the attack of the tone, the amplitude grows from zero to peak. During the steady-state the amplitude is ideally constant. During the decay, the sound dies away.
Note:
Like Csounds linen



#### Helmholtz's model for Musical tone

<img src="./images/Envelope.jpg"></img>



#### Helmholtz's model for Musical tone

- An enclosed waveform
- Waveform is periodic and has a fixed shape
- Helmholtz did not regard inharmonic sounds as music



#### Complex / Periodic Waves

- Up until now, we have been discussing only sinusoidal waves. These were very useful to study a number of basic elements, but in the real world, sound waves of all shapes are found, typically more complex than sinusoidal waves.



#### Complex / Periodic Waves
- Waves that are not purely sinusoidal waves are called complex waves. Jean Baptiste Fourier showed that, theoretically, any complex wave can be broken down into a sum sinusoidal waves, characterised by their individual amplitudes, frequencies and phases.
- As Helmholtz determined, a pitched sensation will be produced. The pitch height will depend on the fundamental frequency.



#### A Complex, Periodic Waveform

- Practically, complex waves with a single identifiable pitch are periodic.

<img src="./images/complex.jpg"></img>



#### Harmonic Components

- A complex periodic wave (one with a number of frequency components) will also exhibit some very important characteristics



#### Harmonic Components
- 
    1. The frequencies of the sinusoidal components will be integer multiples (or close to) of the fundamental frequency.

    2. These components, because of their integer relationship with a fundamental are also called harmonic components or harmonics.

    3. The different mixtures of harmonics, their presence/absence, individual amplitudes, etc.. will be the main element affecting the nature of a wave (the shape and timbre)



#### Harmonic series

- The series of integer multiples of a fundamental is called the harmonic series.

- The harmonic series becomes important when discussing tuning systems, since many are based on some of the ratios found in the harmonic series.
Notes:
Show a spectrogram of instrument



#### The Spectrum

- The Spectrum is a the name given to the set of sinusoidal components of a complex wave. These components can be found using a mathematical tool called the Fourier transform.

- A sound wave can be represented as the pressure amplitude through time, this representation is called the _time domain_ representation or the waveform.



#### The Spectrum

- We can also represent a sound wave in terms of the spectral components. In this case, we will have the amplitude of each component versus frequency. This is called the _frequency domain_ representation, or spectrum.



#### The Spectrum

- So, the spectral description of a sound has a correlation with the timbre
- For instance, the qualitative description of 'bright' characteristics in spectra that have a great deal of energy at high frequencies. The spectra produced by most brass instruments exhibit this trait. Sounds with extreme amount of high-harmonic energy normally sound 'buzzy'.



#### The Spectrum

- A specific example: a spectrum with little or no energy in the even numbered harmonics characterises the particular timbre that is produced by the clarinet in the low register. 
- Most percussive sounds have spectra that are not even close to being harmonic. For example, the clanging sound of a bell is the result of a highly inharmonic spectrum.



#### The Spectrum

- In addition, research has shown that many pitched acoustical instruments exhibit spectra which are slightly inharmonic. The overtones are slightly mistuned from exact harmonics. This causes a sensation of beating in the tone, contributing to the liveliness of the instrument.



#### The Spectrum

- The spectral envelope of a sound is one of the important determinants of timbre. The spectral envelope outlines the pattern of frequency distribution in a spectrum. The spectral envelope of a periodic waveform can be graphically approximated by connecting the tops of the bars in a plot of harmonic ampiltude versus frequency.
Note: 
Show spectral envelope plot, in ableton maybe?



#### The Spectrum

- Examination of spectral envelopes of waveforms may show them to be 'band-limited'. That is, there is a frequency above which the tones contain no significant amount of acoustic energy.
- The bandwidth of a sound is the width of the frequency region in which its significant components reside; one of a number of useful means of characterising spectra.
- This is important to consider in the areas of sound engineering and recording production
Note:
Show mp3 spectrum



#### Spectral Representations

- As we have seen, the Spectrum of a sound can be shown as a simple amplitude against frequency graph. The problem with this representation is that, although it shows the individual components very well, it is just like a photograph of an instant in time.



#### Spectral Representations

- This would suffice for the Helmholtz model, where the spectrum does not change.Nevertheless, all 'interesting' (and, indeed, natural) sounds will exhibit some spectral evolution, what we call a dynamic spectrum, so just one plot of the frequency domain will not be sufficient.



#### Spectral Representations

- Of particular interest, the Helmholtz model neglects the manner in which initial sounds called attack transients (bowing noise, breath sounds, etc) can have a large impact on timbre perception.

- So a dynamic model would be of benefit.

Note:
Show spectrogram



### The Fourier Transform
- We have seen how complex waveforms can be built out of sinusoidal components. One of the most powerful and useful conceptual tools for understanding this process is the Fourier Transform.
- Fourier derived a mathematical expression that transforms a waveform into its spectrum, showing explicitly the amplitudes and phases of the sinusoidal that comprise it. No information is lost in this transformation, the spectrum may be transformed into the waveform and vice versa.



### The Fourier Transform

- In computer terms the Fourier Transform equation takes a long time to computer so we use a slightly modified version of the transform which follows changes in spectra over time called the Short Time Fourier Transform (STFT).
- This transform is the basis of one of the most useful DSP tools available to musicians, the Phase Vocoder.

https://bl.ocks.org/jinroh/7524988