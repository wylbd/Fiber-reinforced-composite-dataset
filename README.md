# Fiber-reinforced-composite-dataset

This dataset contains around 15000 2-phase fiber reinforced composite material blocks. We placed the uniaxial extension to all the samples and record the final displacement and strain energy after the simulation. The material have 3 control parameters: fiber radius, fiber volume fraction, fiber minimum distance. 

The Inclusion_Model_Output files are raw results files including the strain energy, fiber location and size, and full field displacement in separate sheets. 
The npy files have the strain energy, full field displacement, material young's module matrix informations ready for building surrogate models. For the displacement file, it is too big to put one files. As a results, 10 files are used in the disp file and they must be used in the right order. The error samples file contains the failing sample index during simulation for some reasons, please drop those when training the surrogate models.
![fig31](https://github.com/wylbd/Fiber-reinforced-composite-dataset/assets/38464175/348d5412-2f89-4268-8292-4453bc659b4d)
