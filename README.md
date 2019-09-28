# Audio Binary Classification
## Trenton Spice

Things that I tried:
- 1d CNN on raw audio data
  -  `audio-binary-classification-trent-spice-1d.ipynb`
- 2d CNN on raw audio data
  - `audio-binary-classification-trent-spice-2dCNN.ipynb`
  - `audio-binary-classification-trent-spice-2dCNN-copy.ipynb`
- 2d CNN w/ ImageDataGenerators + Spectograms
  - `audio-binary-classification-trent-spice-2dCNN-Spectogram.ipynb`
- Variational Autoencoder 
  - `audio-binary-classification-trent-spice-vae.ipynb`
  - `audio-binary-classification-trent-spice-vae-old.ipynb`
  - `audio-binary-classification-trent-spice-vae-copy.ipynb`
  
How to run the code:
1. First make sure to start a jupyter notebook server, with `jupyter notebook`
2. Be sure to run your kernel on Python 3.7
3. Then open one of the files you are looking to run
4. Make sure to install any dependencies that you may need
5. The test_data.npy and train_data.npy are NOT included in this git repository.
6. IMPORTANT NOTE: If you are running the 2D CNN w/ Spectograms, make sure there is data in both the
   `/audio` and `/spectogram` folders or else it will not work.

7. If those two folders are not present for some reason, look at running the commented out code in cells 
   7, 20, and 21. The three comments that are at the top of each cell are listed below.
   - Generate out the .wav files for creating the spectograms
   - Create spectograms for Train
   - Create spectograms for Test
   
