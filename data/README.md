# Adding files

Due to their large number, there are some .npy files missing from [nesp-9936-unique-mutations-voxel-features/](nesp-9936-unique-mutations-voxel-features/).  This file details how to add them. 

### Download from Kaggle

    Go to [https://www.kaggle.com/code/vslaykovsky/14656-unique-mutations-voxel-features-pdbs/data](https://www.kaggle.com/code/vslaykovsky/14656-unique-mutations-voxel-features-pdbs/data) and download output. There are three dots on the right-hand side of the website that allow you to download the output from this file. You specifically want the *features/* directory. 

### Using the Kaggle API

    Alternatively, Kaggle has its own API that can be used from the command line. You will need to follow the instructions at [https://github.com/Kaggle/kaggle-api](https://github.com/Kaggle/kaggle-api) to install it. Once it's downloaded, you can use the following command to download the output:

```
kaggle kernels output vslaykovsky/14656-unique-mutations-voxel-features-pdbs -p /path/to/dest
```




