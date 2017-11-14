### MU610A: Acoustics & Psychoacoustics
### Edward Costello
### Critical Bands 



#### Psychoacoustics

- Psychoacoustics is the study of the perception of sound

- This includes our listening, the psychological responses, and the physiological impact of music and sound upon the human nervous system. 

- Sound arrives at our ears as pressure waves which are processed and converted into the perception of sound. Whereas physical sound can be measured the same by different individuals, the perception of sound will vary from one individual to another. 



#### Psychoacoustics includes:

- Dynamic range of the ear and frequency dependency
- The localization of sounds
- Masking
- Binaural effects



#### Sensitivity of the ear

- The range of the ear is about 20 Hz to 20 kHz, and is most sensitive at 2 to 4 KHz
- Its dynamic range (quietest to loudest) is about 96 dB.
- Approximate threshold of pain: 130 dB.
    - Hearing damage: > 90 dB (prolonged exposure).
    - Normal conversation: 60-70 dB.
    - Typical classroom background noise: 20-30 dB.
- Normal voice range is about 500 Hz to 2 kHz.
    - Low frequencies are vowels.
    - High frequencies are consonants



#### Range of Human Hearing

<img src="./images/critical_bands/image1-10.png"></img>



#### Typical SPL Levels

<img src="./images/critical_bands/image2-12.png"></img>



#### Hearing Loss with Age

- The human hearing range is between 20 to 20,000 Hz. There is considerable variation in the hearing range between individuals. 
- Most young people can hear up to 18,000Hz. 
- Our ability to hear high frequencies declines with age. By the age of 55 some men can't hear above 5,000 Hz and some women can't hear above 12,000 Hz. 
- Women tend to have better hearing than men at high frequencies.



#### Decibels and Loudness

- A logarithmic scale provides a relative measure of sound intensity.  Based on powers of 10, decibel units allow a manageable range of numbers to represent the wide range of the human auditory response.  

- The human auditory system works loosely on a logarithmic scale.  Our ears respond to ratios rather than differences, with the smallest perceptible change in loudness that the human auditory system can distinguish being roughly 1 dB. 



#### Intensity vs Loudness

- Sound intensity is a measurable quantity relating to the actual acoustic energy whereas loudness is a subjective quality affected by the human auditory response to sound. 

- Loudness is subjective.  What seems twice as loud to one person, may not be twice as loud to another.  



#### Fletcher Munson

- In the 1930s, two employees at Bell Labs, Harvey Fletcher and Wilden Munson, wanted to make a correlation between sound intensity and loudness.  

- They asked a group of people to judge when pure tones of two different frequencies were the same loudness.  They averaged their results and came up with a graph now known as Fletcher-Munson curves.



#### Fletcher Munson Curves

<img src="./images/critical_bands/image5-18.jpeg"></img>



#### Fletcher Munson Curves

- The Fletcher-Munson curves are also known as equal loudness curves.  Any frequency of given intensity along the curve is 'as loud' as any other frequency on the curve.  

- These loudness levels are referred to as phons.  Looking at the 10 phons curve, a 20 Hz tone at an intensity of approximately 75 SPL will sound as loud as a 1000 Hz tone at 10 SPL. 



#### Fletcher Munson Curves

- They accentuate the frequency range to coincide with the frequency components of speech.

- These curves demonstrate the relative insensitivity of the ear to sounds of low frequency at moderate to low intensity levels. Hearing sensitivity reaches a maximum around 4000 Hz, which is near the first resonance frequency of the outer ear canal, and again peaks around 13 kHz, the frequency of the second resonance.



#### Fletcher Munson Curves

- Sounds like _p_ and _t_ have very important parts of their spectral energy within the accentuated range so it makes them more easy to discriminate between them.

- The ability to hear sounds of the accentuated range (around a few kHz) is thus vital for speech communication.



#### Impact on listening levels

- Notice that the curves tend to flatten out when the level goes up. 

- Firstly, notice when you turn down your music player, you are less sensitive to low and high frequencies (compared to the mid-range frequencies) than when the stereo was turned up. Therefore the timbral balance changes, particularly in the low end. 



#### Impact on listening levels

- If the level is low, then you'll think that you hear less bass. This is why sometimes there's a bass boost switch on the stereo. It boosts the bass to compensate for the low-level equal loudness curves.

- Secondly, things simply sound better when they're louder. This is because there's a "better balance" in your hearing perception than when they're at a lower level. 



#### Impact on listening levels

- This is why the salesperson will turn up the volume if you're buying speakers... they sound good that way because a higher level means you hear more bass. 




#### The Cochlea 

- The cochlea is often thought of as a bank of filters because it performs frequency analysis using a frequency to place mapping along the basilar membrane. 

- That is, each place along the membrane has a characteristic frequency $f\_c$, for which it is maximally displaced when a pure tone of that frequency is presented as an input. 



#### The Cochlea 

<img src="./images/critical_bands/image6-20.png"></img>



#### Cochlea filterbank characteristics

- Non-uniform filter bandwidths: Frequency resolution is higher at the lower frequencies

- Asymmetric frequency response of individual filters: for a bandpass filter centred at $f\_c$, this is interpreted as an asymmetric magnitude response, with sharper cutoff on the high frequency side



#### Cochlea filterbank characteristics

- Level-dependent frequency response of individual filters: From a filtering perspective, this implies that the peak gain of the filter centred at $f\_c$ decreases as the level of the input stimulus increases. 

- Another observation is that the magnitude response becomes broader and more symmetric with increasing sound levels



#### Auditory Filterbank

- Auditory filter banks are non-uniform overlapping bandpass filter banks designed to imitate the frequency resolution of human hearing 

- Auditory filter banks have been proposed that are based on psychoacoustic measurements

- The magnitude response, or shape, of the filter has frequently been derived from simultaneous masking experiments, but sometimes uses mechanical response of basilar membrane



#### Some Assumptions

- When trying to detect a sinusoidal signal in noise:
    - The listener makes use of an auditory filter with a centre frequency close to that of the signal. This filter passes the signal but removes a great deal of the noise.
    - Only the components in the noise which pass through the filter have any effect in masking the signal.
    - The threshold for detecting the signal is determined by the amount of noise passing through the auditory filter.



####  The Auditory Filterbank

<img src="./images/critical_bands/image7-22.png"></img>

The auditory system is like a set of overlapping bandpass filters



#### Roex Filter

- Patterson and Nimmo-Smith (1980) suggested that the magnitude response of the auditory filter might well be represented by a pair of back-to-back exponential functions that were rounded in some way at the top and bottom, in accordance with the data. 



#### Roex Filter

- They described a series of rounded-exponential, or "roex" functions, to represent the magnitude characteristic of the auditory filter with a small number of filter parameters 

- The Equivalent Rectangular Bandwidth (ERB) is a psychoacoustic measurement of the width of the auditory filter in each  location along the cochlea



#### Roex Filter

- The roex family is useful mostly as a descriptive model to parameterise and describe the shape of an auditory filter's magnitude response

- Limitations with the roex filter were recognised by (Patterson et al., 1987), such as no phase response, and no time-domain description so it cannot be implemented



#### Gammatone & Gammachirp

- An alternative auditory filter that can be implemented as a digital filter are the families of gammatone (GT) and gammachirp (GC) filters 

- These were developed to provide time-domain simulations of auditory filtering with magnitude responses similar to those derived with the roex filter. 



#### Gammatone Filters

<img style="background:white;" src="./images/critical_bands/image8-24.png"></img>



#### Gammachirp Filters

<img style="background:white;" src="./images/critical_bands/image10-28.png"></img>



#### psychoacoustic Response

- Using one sinusoid is informative but most sounds have many components

- How do we detect sound when many components are present in what we hear?



#### Masking

- Masking is the process by which the detection threshold of a sound (called 'the signal') is increased by the presence of another sound (called 'the masker').

- The amount of masking is defined as the increase (in decibels) in the detection threshold of a sound (signal) due to the presence of a masker sound.



#### Types of Masking

<img style="background:white;" src="./images/critical_bands/image11-30.jpeg"></img>



#### Forward and Backward Masking 

- Masking can occur when the tone (signal) and the masker are not simultaneous.
- Forward Masking
    - Masking of a tone by a sound that ends a 	short time  (e.g 20-30ms) before the tone 	begins
- Backward Masking
	- Masking of a tone by a sound that begins 	sometime later (e.g. 10ms later)



#### Simultaneous Masking, Critical Bands

- For a given frequency, the critical band is the smallest band of frequencies around it which activate the same part of the Basilar Membrane. 

- Essentially two partials that lie within the same critical band will interfere with each other



#### Masking

<img style="background:white;" src="./images/critical_bands/image12-32.png"></img>



#### Simultaneous Masking, Critical Bands

- In terms of length the critical band is nearly constant at 1.2 mm, within which are located about 1300 receptor cells, and is generally independent of intensity. 

- Twenty-four critical bands of about one-third octave each comprise the audible spectrum. The Bark scale is used to represent the Critical band values. They are nonlinear in Hz but linear in Bark. 



#### Critical Band and Hertz
<img style="background:white;" src="./images/critical_bands/image13-34.png"></img>



#### Swamping or Suppression?

- Swamping
    - The masker produces a significant amount 	of activity in the auditory filters which 	swamps the information making the signal undetectable
- Suppression
    - When a signal is well above or below the 	masker, the neural response to a tone may be 	suppressed by a tone that does not excite that particular neuron.



#### Critical Bandwidth

- The critical bandwidth represents the ear's resolving power for simultaneous tones or partials.

- In a complex tone with more than one partial, the critical bandwidth corresponds to the smallest frequency difference between two partials such that each can still be heard separately. 



#### Critical Bandwidth

- Simultaneous tones lying within a critical bandwidth do not give any increase in perceived loudness over that of the single tone, provided the sound pressure level remains constant. 

- For tones lying more than a critical bandwidth apart, their combination results in increased loudness



#### Evidence for Critical Bands

- When two tones are close together in frequency, beats occur, and the resulting tone is a fusion of the two frequencies. 

- Increasing the frequency difference, roughness in the tones appears, indicating that both frequencies are activating the same part of the basilar membrane. 



#### Evidence for Critical Bands

- Further apart, the two frequencies can be discriminated separately. At this point they are activating different sections of the Basilar membrane



#### Illustration of perceptual changes with one tone is fixed and moving the second tone

<img style="background:white;" src="./images/critical_bands/image14-36.png"></img>



#### The principle

- If the fluctuation rate is smaller than the critical bandwidth, then a single tone is perceived either with fluctuating loudness (beating) or with roughness.

- If the fluctuation rate is larger than the critical bandwidth, then a complex tone is perceived, to which one or more pitches can be assigned but which, in general, exhibits no beating or roughness. 



#### Some Definitions - Beats

- The combination of two pure tones with slightly different frequencies results in an amplitude modulation of the resulting waveform.

- The loudness of the waveform rises and falls in a regular pattern over time

- This is known as beating and occurs for fluctuations up to 20Hz



#### Beating
<img style="background:white;" src="./images/critical_bands/image15-38.jpeg"></img>



#### Some Definitions - Roughness

- As the rate of AM is increased by increasing the frequency difference, the loudness appears to be constant and the fluctuations are perceived as "fluttering" or roughness. 

- As the amplitude fluctuation rate is increased further, the roughness reaches a maximum strength and then gradually diminishes until it disappears (~>= 75-150 Hz, depending on the frequency of the interfering tones).



#### Some Definitions - Roughness

- The term roughness describes an aural sensation to label harsh, raspy, hoarse sounds. It is perceptually associated with dissonance.



#### Masking with Tones
- One can generate a 1 kHz masking tone, at fixed sound level of 60 dB, then raise the level of a nearby tone until just audible
<img style="background:white;" src="./images/critical_bands/image16-40.png"></img>
- Plot shows threshold of audibility raised for tones at nearby frequencies



#### From Tone to Noise Masking

- Psycho-acousticians have trouble carrying out the tone masking experiments.

- When the masking tone is very close to the frequency of the tone being masked, the interference beats occur, which makes meaningful masker detection measurements increasingly difficult 



#### From Tone to Noise Masking
- In 1940 Fletcher studied the masking of tones using broad band, white noise. The sound energy of the tone is concentrated but the noise power is distributed across frequencies.



#### Critical Band and Masking

- Early experimenters (e.g. Fletcher) thought that masking of a tone by broadband noise was independent of the noise bandwidth until the bandwidth became smaller than some critical value.

- The ear acts as a collection of parallel filters, each with its own characteristic bandwidth. (Critical Bandwidth or CB)



#### Masking and Noise

<img style="background:white;" src="./images/critical_bands/image18-44.jpeg"></img>




#### Signal detection threshold and Noise BW
<img style="background:white;" width="400px" height="350px" src="./images/critical_bands/image19-46.png"></img>
- As the noise bandwidth increases the level of the signal needed to be able to hear it increases  until it reaches  the Critical Bandwidth



#### Signal detection threshold and Noise BW
<img style="background:white;" width="400px" height="350px" src="./images/critical_bands/image19-46.png"></img>
- We can't know the exact filter bandwidth or shape from these results
- At 2kHz the Critical Bandwidth is 400Hz



#### Fletcher's original experiments

- Fletcher used a rectangle as an approximation of the filter's shape. 
- Rectangular approximations came to be known as Equivalent Rectangular Bandwidths (ERB)
- Typically, the bandwidth of a filter is around 10% to 15% of the center frequency



#### Noise Masking at other 

- The threshold of detection of the tone is raised by the masking noise. However, that noise will also be able to mask a tone at other frequencies. 
- However, the further away from the centre frequency of the masking noise, the lower the threshold of detection until, if the tone's frequency is outside the critical band, the threshold of detection is the threshold of hearing. 



#### Moving the tone outside the critical band

<img style="background:white;" src="./images/critical_bands/image20-48.png"></img>

- Threshold of detection curve in the presence of a masking noise with a bandwidth equal to the critical bandwidth, a centre frequency of 1 kHz and a level of 60 dBspl (dB sound pressure level)



#### Moving the tone outside the critical band

<img style="background:white;" src="./images/critical_bands/image20-48.png"></img>
- The threshold of detection is not raised at only 1 kHz, but at surrounding frequencies



#### Noise Masking at other Frequencies
<img style="background:white;" src="./images/critical_bands/image21-50.png"></img>
<img style="background:white;" src="./images/critical_bands/image22-52.png"></img>
- The amount that a masking noise changes the threshold of detection of a tone at its centre frequency depends on the bandwidth and the level of the noise. 



#### Noise Masking at other Frequencies
<img style="background:white;" src="./images/critical_bands/image21-50.png"></img>
<img style="background:white;" src="./images/critical_bands/image22-52.png"></img>
- The figures shows the change in the threshold of detection caused by a masking noise with a bandwidth equal to the critical bandwidth with a centre frequency of 1 kHz at various levels.



#### Critical Band Masking Demo

https://csd.wisc.edu/vcd202/cbmask.html



#### Numerical Example 1

- If the equation to convert from Frequency to Bark is
$ \text{Bark}(z) = 13 \arctan \big( 0.00076 \times f\big)+3.5\arctan\Big(\big(\frac{f}{7500}\big)^{2}\Big)$

- Considering the two tones below, will the masking tone mask the test tone?
    - Masking tone: 1000Hz, 70dB
    - Test tone: 1370 Hz, 35dB



#### Numerical Difference

- First we need to determine the critical band value difference between the masking and test tone

$ z_{M} = 13 \arctan \big( 0.00076 \times 1000 \big)+3.5\arctan\Big(\big(\frac{1000}{7500}\big)^{2}\Big)=8.51$

$ z_{T} = 13 \arctan \big( 0.00076 \times 1370 \big)+3.5\arctan\Big(\big(\frac{1370}{7500}\big)^{2}\Big)=10.58$

$ \Delta z = z\_{M} - z\_{T} = -2.07$



#### Masking based on Bark difference

<img style="background:white;" src="./images/critical_bands/image25-58.png"></img>



#### Locate the Masker

- Find the point at -2.07 Bark on the plot which corresponds to the Test tone magnitude of 35dB

<img style="background:white;" src="./images/critical_bands/image26-60.png"></img>



#### Is the tone masked?

- The x-axis value is 2.07 bark, the y-axis value is 35dB. The intersection (yellow dot) falls under the 70dB masking curve. This means that the 70dB masking tone will mask the test tone.
- Therefore, the 1370Hz tone at 35dB would be completely masked by the 1000Hz tone at 70dB.



#### Numerical Example 2

- Considering the two tones below, will the masking tone mask the test tone?
    - Masking tone: 770Hz, 45dB
    - Test tone: 2000Hz, 40dB




#### Bark Difference of Tones

$ z_{M} = 13 \arctan \big( 0.00076 \times 770 \big)+3.5\arctan\Big(\big(\frac{770}{7500}\big)^{2}\Big)=6.91$

$ z_{T} = 13 \arctan \big( 0.00076 \times 2000 \big)+3.5\arctan\Big(\big(\frac{2000}{7500}\big)^{2}\Big)=13.01$

$ \Delta z = z\_{M} - z\_{T} = -6.10$



#### Locate on the Plot

<img style="background:white;" src="./images/critical_bands/image28-64.png"></img>



#### Finally

In this case, the masking tone would need to be above 80dB to mask the test tone. Because the masking tone is only 45dB, the test tone is not masked.



#### Asymmetric Auditory filter Shape

- A lower tone can more effectively mask a higher tone

- A higher tone does not mask a lower tone so well

- There is an asymmetry in the auditory filter shapes



#### Ideal Asymmetric Auditory Filterbank shape

<img style="background:white;" src="./images/critical_bands/image29-66.png"></img>



#### Off-Frequency Listening

- When the masker frequency is above the signal frequency, the listener might do better to use the information from a filter centred just below the signal frequency. 

- If the filter has a relatively flat top, and sloping edges, this will considerably attenuate the masker at the filter output, while only slightly attenuating the signal. 



#### Off-Frequency Listening

- Using this filter the listener can improve performance. This is known as 'off-frequency listening' or 'off-place listening', and there is good evidence that humans do indeed listen 'off-frequency' when it is advantageous to do so



#### Off-Frequency Listening

- So, this happens when the signal is detected through a filter different from the one with a centre frequency $(f_c)$ equal to the signal frequency

- It can occur because auditory filters are asymmetric and have steep high-frequency slopes



#### Masking Patterns

- In the masking experiments described, the frequency of the signal was held constant, while the masker was varied. 

- These experiments are most appropriate for estimating the shape of the auditory filter at a given centre frequency. 



#### Masking Patterns
- However, if the masker is held constant in both level and frequency, and the signal threshold is measured as a function of the signal frequency. The resulting functions are called masking patterns or masked audiograms



#### Excitation Patterns

- Masking patterns show steep slopes on the low-frequency side (when the signal frequency is below that of the masker). The slopes on the high-frequency side are less steep and depend on the level of the masker. 

- The excitation pattern shows how much energy comes through each auditory filter close to the signal frequency. It is analogous to the pattern of vibration on the basilar membrane. 



#### Masking Patterns for Narrowband Noise Masker

<img style="background:white;" src="./images/critical_bands/image31-70.jpeg" width="350px" height="250px"></img>
- Masking patterns for a narrowband noise masker centred at 410Hz.



#### Masking Patterns for Narrowband Noise Masker

<img style="background:white;" src="./images/critical_bands/image31-70.jpeg" width="350px" height="250px"></img>
- Each curve shows the elevation in threshold of a pure-tone signal as a function of signal frequency. 
- The overall noise level in dB SPL for each curve is indicated in the figure.



#### Excitation Patterns
<img style="background:white;" src="./images/critical_bands/image32-72.gif"></img>
- SNHL: Sensorineural Hearing loss
- For a 1000 Hz pure tone the excitation pattern for a normal and for a SNHL listener look like this:



#### Excitation Patterns
- The excitation pattern to a complex tone is simply the sum of the patterns to the sine waves that make up the complex tone (since the model is a linear one). 

- A person can hear a tone at a particular frequency in a mixture if there is a clear peak in the excitation pattern at that frequency.



#### Excitation Patterns
- Since people suffering from SNHL have broader auditory filters their excitation patterns do not have such clear peaks, rather everything is blurred. Sounds mask each other more, and so they have difficulty hearing sounds (such as speech) in noise.



#### Forward Masking 

- Forward masking is greater the smaller the delay between the two signals
- The rate of recovery from forward masking is greater for higher masker levels. Decays to zero in all cases, after 100 - 200 ms
- Forward masking increases with increased masker duration... until about 50ms.
- Forward masking depends on the signals used



#### Forward Masking experiment

- Play 1 kHz masking tone at 60 dB, plus a test tone at 1.1 kHz at 40 dB. Test tone can't be heard (it's masked).

- Stop masking tone, then stop test tone after a short delay.

- Adjust delay time to the shortest time when test tone can be heard (e.g., 5 ms).

- Repeat with different level of the test tone and plot 



#### Forward Masking 
<img style="background:white;" src="./images/critical_bands/image33-74.png"></img>

- The shorter the masker sound is on for, the quicker the forward-masking effect decays. 

- Post-masking occurs within 200 milliseconds of the masking sound turning off. 



#### Forward Masking 
<img style="background:white;" src="./images/critical_bands/image33-74.png"></img>

- After about 200 milliseconds, hearing returns to typical "threshold in quiet" behaviour.

- Also, the louder is the test tone, the shorter it takes for our hearing to get over hearing the masking



#### Forward Masking 

- Response of the basilar membrane continues after the end of the masker. ("ringing")
- Masker produces short-term adaptation or fatigue in the auditory nerve or higher centres in the auditory system
- Neural activity persists at some level in the auditory system



#### Persistance of Neural Activity
<img style="background:white;" src="./images/critical_bands/image35-78.png"></img>



#### Backward Masking

- Sometimes called pre-masking, Intuitively, it is unexpected because it takes place before the masker is switched on
- Can possibly be explained that the auditory system requires an integration time to build the perception of sound and loud sounds require more time than soft sounds



#### Backward Masking

- In the diagram on the next slide the pre-masking lasts about 20ms but is most effective in the few milliseconds before the onset of the masker
- Is important for pre-echo or pre-noise artifacts that can appear in audio codec algorithms
- These happen when the energy of the coded signal is spread in time before the onset of the attack
- It occurs with instruments like castanets and cymbals



#### Three types of Masking

<img style="background:white;" src="./images/critical_bands/image36-80.png"></img>



#### Masking in Time and Frequency

<img style="background:white;" src="./images/critical_bands/image37-82.gif"></img>



#### Psychoacoustics and MP3

- MPEG audio compression takes advantage of psychoacoustic models

- Applies a filter bank to the input to break it into its frequency components

- Inaudible frequency components are discarded because they are either underneath the threshold of hearing or are masked by other components



#### Psychoacoustics and Consonance

- The motion from consonance to dissonance and back again is a standard feature of most Western music, and several attempts have been made to explain, define, and quantify the terms 'consonance' and 'dissonance'



#### Sensory Dissonance with Sinewaves

- One approach is called tonal or sensory dissonance, in which the sensory dissonance between pairs of sine waves is determined from psychoacoustic experiments. 

- The sensory dissonance of more complex sounds is then defined to be the sum of the dissonances between all simultaneously sounding sine wave partials. 



#### Sensory Dissonance with Sinewaves

- Because sensory dissonance depends on the partials, sounds with different spectra may function differently. 

- For instance, an interval may be quite consonant when played with one sound, but quite dissonant when performed with another



#### Dissonance Curve

- This describes the sensory dissonance of a sound

- The example on the next slide  shows a plot for a sound with six harmonic partials over a range of intervals slightly larger than an octave. 



#### Dissonance Curve

<img style="background:white;" src="./images/critical_bands/image38-84.png"></img>

- Dissonance curve for a spectrum with fundamental at 500 Hz and six harmonic partials has minima at 1.0, 1.14, 1.2, 1.25, 1.33, 1.5, 1.67, 1.78, and 2.0, which are shown by the tick marks on the frequency axis



#### Dissonance Curve Analysis

- The minima of this curve occur at the simple integer ratios of the Just Intonation scale, reinforcing the familiar notion that the most consonant (i.e. least dissonant) intervals for sounds with harmonic spectra are those with small integer ratios. 

- The top axis shows the steps of the 12-tone equal tempered scale, which can be viewed as approximating many of these just ratios.



#### Sensory Consonance

- Sensory consonance is thought to be dependent on three fundamental auditory attributes: roughness, sharpness, and tonalness

- Sharpness refers to the high energy in the upper registers of a sound's timbre and tonalness is the degree of tonal components a sound holds

- For the sounds of music and for their musical consonance, roughness is most important.



#### Tonalness

- Aures defined this as the relationship between the tonal and noise components in the signal after the pitch and masking phenomena are corrected 



#### Consonance and Dissonance in Music

- Consonant chords are, roughly speaking, made up of notes that 'sound good' together, like middle C and the G above it (an interval called a fifth). 

- Dissonant chords are combinations that sound jarring, like middle C and the C sharp above (a minor second). 



#### More formally

- Consonant intervals are usually described as pleasant and agreeable. 
- Dissonant intervals are those that cause tension and desire to be resolved to consonant intervals. 



#### Consonance

- Consonances are traditionally divided into two groups: perfect and imperfect. 

- Perfect intervals (1, 4, 5, 8) are perfect consonances, as seen in the polyphonic music of the Middle Ages. 

- Imperfect consonances (3 and 6) are either major or minor. 



#### Dissonance

- Dissonances can be divided into sharp and soft dissonances. This division relates mainly to atonal music. 

- Minor second and major seventh are sharp dissonances. In tonal music, non-diatonic intervals (diminished and augmented) are usually dissonances, 

- However in jazz and other African-American music, the tritone is "neutral", so it does not require resolution to a consonance.



#### Consonance and Dissonance
- Note that the concepts "consonance" and "dissonance" are highly context-related. 

- How sonance (consonance or dissonance) is perceived depends on several music-psychological factors including temperament; genre (in atonal music, consonances are scarce); timbre; the extent of the interval. 



#### Chords and overtones

- All sounds except sinewaves will contain more than one frequency component. These are often called overtones or partials

- They are described as harmonics if their frequency has an integer relationship with the pitch/fundamental frequency of the sound. The frequency components that made up sound of most pitched instruments has this relationship approximately



#### Chords and overtones

- A sound is inharmonic is the frequency component relationships are not integers, and this well describes metal percussive sound



#### Chords and overtones

- Considering  the playing of chords there are many consonance and dissonance relationship they can occur between each frequency component in the constituent notes

- The pleasantness of the resulting sound then is highly dependent on the relative positions of the frequency components and their amplitudes



#### Consonance and Dissonance

- It has often been suggested that humans have innate preferences for consonance over dissonance, 

- This has led some to conclude that music in which dissonance features prominently is violating a natural law and is bound to sound bad... but it is very subjective



#### History and Consonance

- The debate over what constitutes consonance and dissonance is as old as the music-theoretic tradition itself. 

- Indeed, most historical narratives begin with Pythagoras; 

- Pythagoras judged consonance, or symphonos, in terms of mathematical ratios.



#### Pythagoras and Consonance

- He recognised that the pitch of a string is related to its length and that the degree to which two simultaneous tones sound consonant is determined by the simplicity of their length ratios. 

- For example, a ratio of 2/1 is considered simpler, and therefore more consonant, than one of 4/3, because the integers involved are smaller.



#### Helmholtz

- Much later on Helmholtz outlined an extensive, "mechanistic" explanation for the consonance-dissonance distinction that involved the presence of beating

- Helmholtz conceived of consonance as a sensory response caused by two factors, the affinity of the upper partials (overtones) of two or more tones and the absence of acoustic beats among these partials



#### Helmholtz

- For Helmholtz, the preponderance of acoustical beating and the sensation of roughness was what constituted dissonance; 

- this not only included beating, between the fundamentals of frequencies tuned "improperly" but the beating of conflicting partials between multiple frequencies that are either mistuned, have inharmonic timbres, or both.



#### Helmholtz and Music

- However, he did recognize that musical theory and practice involved digressions from the physical properties of sound



#### Stumpf

- Psychologist Carl Stumpf (1848-1936) held a different viewpoint, taking a psychological frame of reference - Tonpsychologie (the psychology of musical sound)

- Stumpf asserted instead that dissonance is a psychological response: the perception of lack of tonal fusion of two tones



#### Modern Times

- Green and Butler's conclusion regarding what they deem "the legacy of Helmholtz and Stumpf" strongly suggests that modern, current conceptions of musical consonance rely much more upon subjective, aesthetic judgement rather than objective, scientific definitions

- Burdette Green and David Butler, "From Acoustics to Tonpsychologie," The Cambridge History of Western Music Theory, ed. Thomas Christensen (New York: Cambridge University Press, 2002, 260 



#### Psychoacoustics and Dissonance

- Two tones close in frequency interfere to produce 'beating'. 

- If the difference in frequency is within a certain range, rapid beats create a rattling sound called roughness. 

- An aversion to roughness has seemed consistent with the common dislike of intervals such as minor seconds.



#### Psychoacoustics and Dissonance

- In a recent study normal-hearing people rated small intervals (minor seconds and major seconds, such as C-D) and large but sub-octave intervals (minor sevenths (C-B flat) and major sevenths (C-B)) as very unpleasant.

- People with amusia, who cannot distinguish between tones, showed no distinctions between any of the intervals



#### Psychoacoustics and Dissonance

- Both groups could detect beating and they found that the amusics disliked it about as much as the control group. So apparently something else was causing the latter to dislike the dissonant intervals.

- The scientists postulated then that it was the harmonicity of consonant intervals that most people prefer



#### Psychoacoustics and Dissonance

- Notes contain many overtones - frequencies that are whole-number multiples of the basic frequency in the note. 

- For consonant intervals the overtones of the two notes tend to coincide as whole-number multiples, 

- For dissonant intervals this is no longer the case: they look more like the irregular overtones for sounds that are 'inharmonic'.



#### Psychoacoustics and Dissonance

- The normal group preferred consonant intervals with these regular harmonic relationships over artificial 'consonant' ones in which the overtones were subtly shifted to be inharmonic while the basic tones remained the same. 

- For the amusics, meanwhile, they registered no difference between the two cases: they seem to be insensitive to harmonicity.



#### Connection to tuning and intonation

- Tuning systems are significant impacted
- Consider the intervals played in Just Intonation and Equal temperament

<audio controls>
  <source src="./sounds/critical_bands/media1-87.wav" type="audio/wav">
</audio>



#### Missing Fundamental

- This can happen when the combination of partials suggests that the waveform should have a lower fundamental frequency, but no component exists at that lower frequency

- The fundamental frequency of a waveform is found by the Highest Common Factor (HCF), so 3 components, 200Hz, 300Hz, and 400Hz have a HCF=100Hz. The waveform repeats at the rate of 100Hz

- The brain realises this and fills in. 



#### Missing Fundamental

- Try the example here 
    - https://www.auditoryneuroscience.com/topics/missing-fundamental



#### Just Intonation

- Just intonation aims at maximal harmony, tuning all intervals with rational frequency ratios, see next slide for the relationships

- This system results in an absence of beats but has differences in the sizes of intervals along the scale

- Just intonation makes transposition and modulation difficult (at least within the confines of a 12-pitch keyboard)



#### Frequency ratios of the scales
|   |   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|---|
|major| 1 | 9/8  | 5/4  | 4/3  | 3/2  | 5/3 | 15/8 | 2/1 |
|minor| 1 | 9/8  | 6/5  | 4/3  | 3/2  | 8/5 | 9/5 | 2/1 |

- Example of scale in Just Intonation
    - <audio controls>
  <source src="./sounds/critical_bands/media2-88.wav" type="audio/wav">
</audio>
- Example of chords in Just intonation
    - <audio controls>
  <source src="./sounds/critical_bands/media3-89.wav" type="audio/wav">
</audio>



#### Just Intonation

- However, with software now you hear and play music in 'just intonation' music
- http://just-intonation.org/




#### Equal temperament

- In equal temperament every semitone is the same distance apart 

- In equal temperament the octave is divided into 12 equal intervals not because it sounds better that way-but primarily because the music can be transposed to any key



#### Equal temperament
- The twelve-tone equal-tempered scale contains all seven of the basic consonant intervals to a good approximation - within one percent - and contains more consonant intervals than dissonant intervals
- Tuning an instrument-primarily keyboard instruments-to twelve-tone equal temperament introduces a lot of beating, and hence, roughness. 



#### Equal temperament
- Basic Consonant Intervals
    - 2/1 octave harmonic inverse of 1/1
    - 3/2 perfect fifth harmonic inverse of 4/3
    - 4/3 perfect fourth harmonic inverse of 3/2
    - 5/3 major sixth harmonic inverse of 6/5
    - 5/4 major third harmonic inverse of 8/5
    - 6/5 minor third harmonic inverse of 5/3
    - 8/5 minor sixth harmonic inverse of 5/4
- Note that the inverse is when you switch the interval, 
- i.e. C with G above is a 5th, C with G below is a 4th



#### Equal temperament

- Compositions performed in twelve-tone equal-temperament will contain a healthy amount of beating between its intervals and harmonies

- Taking a Stumpfian view: tonal music in equal temperament isn't dissonant because listeners, by and large, don't consider equally tempered intervals and the harmonies they produce as being dissonant



#### Alternative tuning systems

- There are a number of proposed systems out there
- John O'Sullivan in the US has Eagle53 http://johnsmusic7.com/
- http://just-intonation.org/
- http://nicksworldofsynthesizers.com/flashorgan.php



#### Hermode Tuning

- http://www.hermode.com/index_en.html
- This is a system for tuning electronic instruments dynamically in real time
- It takes away the tuning errors of traditional equal temperament, tuning fifth and thirds to a high degree of purity. The result is powerful bass and brilliant treble



#### Hermode Tuning Theory

- See here for the theory
    http://doc.crudebyte.com/musical-tuning-systems/



#### Examples

http://www.hermode.com/html/hermode-tuning-examples_en.html




#### Some more background

- Online book on the development of musical tuning systems
    http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.368.2097&rep=rep1&type=pdf

    http://demonstrations.wolfram.com/PythagoreanMeantoneAndEqualTemperamentMusicalScales/