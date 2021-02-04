# AIV_MAOAC

Here, we present artificial intelligence velocimetry (AIV) to quantify the velocity, pressure and stress fields of blood flow for micro-aneurysm-on-a-chip (MAOAC), by integrating the imaging data with underlying physics using physics-informed neural networks. 


## Directory

>**ImageData/**: the raw microfluidic images  
>**HFMdata2D/**: data extracted from the images and used for AIV training  
>**HFMresults/**: results after AIV training  
>**matlab_scripts/**: Matlab scripts to visualize the AIV results  
>**AIV_training.exe**: executable program that shows a demo of AIV training  


## Training AIV

In the comment prompt (Windows OS), run
> AIV_training.exe

The executable program will take a long time to complete the training, as this is run on CPUs. It will print the log and training loss and create a .mat file in `HFMresults` folder after training. 


## Others

The data and codes can be found here: [https://drive.google.com/drive/folders/1E1RmxzaQGqO3gi5eVZ4Eil1WcRF5tXX6?usp=sharing](https://drive.google.com/drive/folders/1E1RmxzaQGqO3gi5eVZ4Eil1WcRF5tXX6?usp=sharing).



