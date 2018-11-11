# Story-Telling-Using-Show-Attend-and-tell
augmenting the show attend and tell image captioning with story telling

implement paragraph by using https://github.com/tensorpack/tensorpack/tree/master/examples/FasterRCNN 

Files and what they do 

GetDataset.ipynb  : Split the dataset into the training and test and valuation pathfiles and save it to corresponding files "imgs_test_path.txt" 

MakeParagraphandimage.ipynb  : take the paragraph json file and map the dataset to the given paragraph "img2paragraph"

ParagraphPreprocessing.ipynb : take the paragraph json file and build the vocabulary and then from these built vocabulary append padding, bos and eos and unknown characters and build idxtoword and wordtoindex
