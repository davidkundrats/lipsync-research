# Exploring Methodology and Modalities in the Wav2lip Model: A Comprehensive Analysis
Goal: Explore Wav2lip applicability for the generation of lip synced videos on 2d animations.

The implementation of Wav2lip can be found here: https://github.com/Rudrabha/Wav2Lip

In the implementation of Wav2lip, there are 3 models used to generated lip synced 'deepfake' clips. These 3 are the discriminator, the face detection method (in this implementation, it is the sf3d model), and the actual wav2lip model itself. 

Wav2lip can be used as a standalone method of video generation or combined with other AI models to improve results. 

Here is an example of Wav2lip being used on a video: 

Before: 





https://github.com/davidkundrats/lipsync-research/assets/98171693/8203967c-86ef-4abe-8958-2ad058a3ba3e


After Wav2lip:



https://github.com/davidkundrats/lipsync-research/assets/98171693/79fa50f7-f829-4fd1-b463-21bcf973544e

