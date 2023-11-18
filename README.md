# Exploring Methodology and Modalities in the Wav2lip Model: A Comprehensive Analysis

**Goal:** Explore Wav2lip applicability for the generation of lip-synced videos on 2D animations.

The implementation of Wav2lip can be found [here](https://github.com/Rudrabha/Wav2Lip).

In the implementation of Wav2lip, there are three models used to generate lip-synced 'deepfake' clips:

1. The discriminator
2. The face detection method (in this implementation, it is the sf3d model)
3. The actual Wav2lip model itself

Wav2lip can be used as a standalone method of video generation or combined with other AI models to improve results.

Here is an example of Wav2lip being used on a 3d video:

**Before:**  


https://github.com/davidkundrats/lipsync-research/assets/98171693/35b26032-a09f-43cd-9a5d-dfea82df8ebf



**After Wav2lip:**  



https://github.com/davidkundrats/lipsync-research/assets/98171693/4a8e3244-f236-4807-a17a-9eb4d1d33b7e

