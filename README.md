# Exploring Spatial Differences in Autocorrelation Decay in Human Intracranial Brain Recordings

**Authors:** TeVaughn Shaw, Zaid Zada, Itamar Jalon  
**Institution:** Princeton Neuroscience Institute  

---

## Abstract
Listening to stories requires the brain to integrate linguistic information across multiple time-scales, from phonemes to sentences and narratives. Different cortical areas may operate over distinct **temporal receptive windows (TRWs)**.  
This project quantified TRWs during naturalistic story listening by analyzing **ECoG (electrocorticography)** signals. Using autocorrelation functions (ACFs), we measured autocorrelation widths (ACWs) to estimate TRWs. Findings revealed that TRWs vary across cortical areas, highlighting differences in temporal integration during speech comprehension.

---

## Study Paradigm
- **Data:** ECoG from **160 electrodes** across **10 subjects**.  
- **Task:** Participants listened to a **30-minute podcast episode**.  
- **Preprocessing:**  
  - Resampled signals at **400 Hz**.  
  - Notch filter at **60, 120, 180 Hz**.  
  - Split signals into three 10-minute chunks.  
- **Analysis:**  
  - Computed **autocorrelation function (ACF)** per electrode.  
  - Extracted **autocorrelation width (ACW)** (full width at half maximum).  

---

## Methodology
1. Filter raw ECoG signals across frequency bands (Broadband, Gamma, Beta, Alpha, Theta).  
2. Divide into three temporal chunks (0–10 min, 10–20 min, 20–30 min).  
3. Compute ACF and estimate ACW for each electrode.  
4. Compare ACWs across brain regions and frequency bands.  
5. Correlate electrode activity with audio waveform to assess auditory processing alignment.

---

## Results
- **TRWs vary by cortical region**: Shorter TRWs in low-level auditory areas, longer TRWs in higher-order regions.  
- **ACWs change across time chunks**, suggesting dynamic adjustments in temporal integration.  
- **Correlation with audio**: Electrodes closer to primary auditory cortex correlated more strongly with the stimulus.  
- **Scatter plot findings**: Electrodes with shorter TRWs showed higher correlations with the audio, consistent with prior work.

---

## Conclusion
- ECoG recordings reveal **dynamic temporal receptive windows** during speech comprehension.  
- The brain flexibly integrates information over multiple timescales depending on cortical hierarchy.  
- These findings advance our understanding of **temporal dynamics of language processing**.

---

## References
1. Honey, C. J. et al. (2012). *Slow cortical dynamics and the accumulation of information over long timescales.* Neuron, 76(2), 423–434.  
2. Goldstein, A. et al. (2022). *Shared computational principles for language processing in humans and deep language models.* Nature Neuroscience, 25(3), 369–380.  
