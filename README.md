# AIV MAOAC

Please find the data and codes [here](https://drive.google.com/drive/folders/1E1RmxzaQGqO3gi5eVZ4Eil1WcRF5tXX6?usp=sharing).

Here, we present artificial intelligence velocimetry (AIV) to quantify the velocity, pressure and stress fields of blood flow for micro-aneurysm-on-a-chip (MAOAC), by integrating the imaging data with underlying physics using physics-informed neural networks. 

## Citation


    @article {Caie2100697118,
	    author = {Cai, Shengze and Li, He and Zheng, Fuyin and Kong, Fang and Dao, Ming and Karniadakis, George Em and Suresh, Subra},
	    title = {Artificial intelligence velocimetry and microaneurysm-on-a-chip for three-dimensional analysis of blood flow in physiology and disease},
	    volume = {118},
	    number = {13},
	    elocation-id = {e2100697118},
	    year = {2021},
	    doi = {10.1073/pnas.2100697118},
	    publisher = {National Academy of Sciences},
	    issn = {0027-8424},
	    URL = {https://www.pnas.org/content/118/13/e2100697118},
	    eprint = {https://www.pnas.org/content/118/13/e2100697118.full.pdf},
	    journal = {Proceedings of the National Academy of Sciences}
    }
  



## Directory

* **ImageData/**: the raw microfluidic images  
* **HFMdata2D/**: data extracted from the images and used for AIV training  
* **HFMresults/**: results after AIV training  
* **matlab_scripts/**: Matlab scripts to visualize the AIV results  
* **AIV_training.exe**: executable program that shows a demo of AIV training  


## Training AIV

In the command prompt (Windows OS), go to the directory and run
> AIV_training.exe

The executable program will take a long time to complete the training, as this is run on CPUs. It will print the log and training loss, and create a .mat file in `HFMresults` folder after training. 


## Others

The data and codes can be found here: [https://drive.google.com/drive/folders/1E1RmxzaQGqO3gi5eVZ4Eil1WcRF5tXX6?usp=sharing](https://drive.google.com/drive/folders/1E1RmxzaQGqO3gi5eVZ4Eil1WcRF5tXX6?usp=sharing).



