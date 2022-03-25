# Weekly Journal

- Week 1 : Finalize the abstract
- Week 2 :
- Week 3 : Download the So2SAT dataset, understanding the structure of files
- Week 6 : Read about the TIDAL project at https://x.company/projects/tidal/. Tried contacting the members for a possible collaboration.
- Week 9 : 
  - Trained a UNet (CNN based) for the water-body satellite images. Currently I trained on a subset of Sentinel-II images consisting ~2800 images with thier corresponding masks. This dataset contains water-body images of non-urban zones which are annotated using traditional methods (NWDI). While the main goal of my project is to train images in urban-settings, this could serve as a good baseline.
  - After training the model on 10 epochs, the accuracy was very low (~50%). **TODO**: change of hyperparmeters, preprocessing,  
  - Analysis of So2SAT dataset, (as this dataset is extremely large, with many channels and bands, I need to pick a subset of the ones that fit well for my problem statement). **Advantage***: Has images with water bodies in urban areas with good resolution and appropriate complexity. 
  -  Ongoing experimentation with **Teranaus** model. https://github.com/ternaus/robot-surgery-segmentation#id1 This model has proven to be more powerful than UNet, hopefully will boost accuracy.
  -  Read more about semantic aerial segmentation https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLII-3-W12-2020/183/2020/isprs-archives-XLII-3-W12-2020-183-2020.pdf for low resource applications.

## 2022-03-07 check in: alp

I encourage you to write more verbose journal entries and to update the repo weekly. Please let Nicolas and myself know once your repo better reflects the current state of your project so that we can provide insight.
