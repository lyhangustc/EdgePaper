# Daily Work Logs and Experiment Plans

### Experiment List
**Evaluation metirics**
- [x] MS-SSIM
- [x] FID
- [x] KID

**More experiment**
~~- [ ] CSAM discriminator: add CSAMs to discriminator__~~
~~- [ ] Resnet pix2pix: increase pix2pix capacity by switch conv_block to res_block~~
- [x] Vissulizing attention
- [x] Test the trained model with different kinds of edge maps


**Experiment States**

Experiment                  | MS-SSIM                 | FID      | KID  |
---------                   | ---------               |-------   |------|
Dataset                     | Done, may discard later | ----     | Done |
pix2pix                     | Done, may discard later | Done     | Done |
Full model                  | Done, may discard later | Done     | Done |
pix2pix with distance field | Done, may discard later | Done     | Done |
Ours without distance field | Done, may discard later | Done     | Done |
Rotation                    | ---------               | Out of driver memory | Out of driver memory |
---------                   | --------- |-------| ---------     |
CSAM discriminator          | -         | -     | out of GPU memory|
Resnet pix2pix              | -         | -     | TODO          |

Experiment                  | State                             |
---------                   |---------                          |
Vissulizing attention       | Done                              |
Test different edge maps    | Done                              |



### Known Errors
~~- [ ] calutlate FID with the author's code on CelebA dataset: the imagine part is too large when computing coefficient matrix~~
- [x] The MS-SSIM is computed pixel-wisely and may not suitable to evaluate the quality of the resutls.

## Work logs
### 2018-11-16
- [x] Add techniques of BigGAN to our code:
      - [x] Orthogonal Regularization
      - [x] Improved spetral normalization
- [x] Add techniques of examing GANs:
      - [ ] Weight, gradients, and loss stats

### 2018-11-15
- [x] Paper reading: BigGAN, see /PaperReading for details.
- [ ] Related papers collection.
- [x] Code of IPGAN, submitted.

### 2018-9-6
- [x] Set up Caltech-UCSD birds dataset, make tfrecord file with a new cropping method based bounding box
- [x] Submit experiment on birds dataset
- [x] Stanford dogs dataset
- [x] Submit experiment on dogs dataset

### 2018-9-5
- [x] Read paper: Scribbler: Controlling Deep Image Synthesis with Sketch and Color, CVPR 2017 
- [x] Read paper: Sparse, Smart Contours to Represent and Edit Images, CVPR 2018

### 2018-9-4
- [x] Write a htlm web file to display all the results of gamma experiments
- [x] Add a new subsection in the paper to discuss the gamma experiments

### 2018-8-27~2018-9-3
- [x] Gamma experiments: Test edge maps with different gamma values
- [ ] Investigate the latest related paper

### 2018-7-15~22
- [x] move paper to overleaf
- [x] contract the author of FID to fix the code of FID
- [x] add an experiment: test the model with different kinds of edge maps to show the genralizaiton of the model

skip some logs

### 2018-7-13
**TODO List**

- [x] make a list of experiment plans
- [x] submit experimets to GPU service and record the states
### 2018-7-12
**TODO List**

- [x] edit paper according to last discussion
- [x] emphasize line2face in Introdution and Abstract
- [x] add results and analysis of experiments
- [x] mark experiments to do in red
