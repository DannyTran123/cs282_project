CS282 Project

Michelle Tong (mwtong@berkeley.edu), Gabrielle Hoyer, Danny Tran

1. Install relevant packages to import all the package for the first cell of Processing.ipynb.
2. In Part 1 Cell 2, update all the filepaths and make relevant folders if necessary.
3. Run Part 1, in this section the data is split and the dataloader is defined. Modifications to splitting, image normalization, or image transformations should be made here. 
4. In Part 2, load and modify pre-existing models to use for our classification task. Whether the model is pretrained=True or False, all kernel_size=3, 5, or 7 for the first few layers of the network prior to the don't mess with these layers comment. The untrained models we used for training can be downloaded from this Dropbox link: https://www.dropbox.com/sh/rg6nbb0sbbql87d/AABreFb5Sy7QHlr9zOXY3MKKa?dl=0. 
5. In Part 3, run the cells to train the model, skip all the cells that say for loop version and use the param set version instead to run one parameter set. Also run Part 4.1 to see how well the model performs on validation data. Again, run the param set version code cells (just skip the cells starting with FOR LOOP VERSION).
6. Once the best model is chosen, run part 4.2 to evaluate the model on the test data.
