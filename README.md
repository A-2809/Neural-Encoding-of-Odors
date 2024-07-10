# Neural-Encoding-of-Odors
Neural Encoding of Odors: Translating Odors into Unique Digital Representation with EEG Signals

## ABSTRACT 
Electroencephalography (EEG) plays a pivotal role as a non-invasive method for measuring brain activity, offering insights into cognitive processes such as perception, attention, and memory. Its significance lies in its ability to capture real-time neural dynamics with high temporal resolution, making it particularly valuable for studying the complexities of sensory perception, including olfaction. The human olfactory system is crucial for our sense of smell, understanding how the brain processes olfactory stimuli is complex due to the diverse nature of odor molecules and individual variability in perception. This work presents a novel pipeline for encoding and unique digital representations. Through these techniques, it uncovers unique odor representations, providing valuable insights into the intricacies of neural processing. These representations, embedded in matrices, have applications in healthcare, multi-sensory immersion, and e-commerce. The work explores comprehension of human cognition, while its practical implications underscore its relevance across diverse domains.

## Running the Code
Prerequisites
Ensure you have the necessary libraries installed before running the code. 

Data
All data required for this project is included as NumPy files (.npy) to optimize storage space. Ensure these files are available in the appropriate directories as specified in the code.

Steps to Execute
Running the Jupyter Notebook:
Open the notebook file in the Jupyter interface and run all cells sequentially. The autoencoder will be trained on the pre-processed data, and the encoding representations will be extracted.

Applying SVD Model:
After training the autoencoder, the bottleneck layer (encoding representations) will be used to apply the Singular Value Decomposition (SVD) model. This will calculate the unique digital representations of the odors.

Additional Notes
Ensure that the paths to the data files are correctly set in the notebook.
It is advisable to run the notebook on a machine with sufficient computational resources due to the potential intensity of training the autoencoder and running SVD.
By following these steps, you will be able to replicate the process of encoding and extracting unique digital representations of odors using EEG signals.


