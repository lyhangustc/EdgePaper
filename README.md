# Daily Work Logs

### Experiment List
**Evaluation metirics**
- [x] Code for calcultating MS-SSIM
- [ ] Pix2pix: MS-SSIM, FID
- [ ] Full model: MS-SSIM, FID
- [ ] -Distance fields: MS-SSIM, FID
- [ ] -Spectral Normalization: MS-SSIM, FID
- [ ] -Global Discriminator: MS-SSIM, FID
- [ ] -Conditional Connection: MS-SSIM, FID

**More experiment**
- [ ] CSAM discriminator: add CSAMs to discriminator
- [ ] Resnet pix2pix: increase pix2pix capacity by switch conv_block to res_block
- [x] Vissulizing attention
- [ ] Test the trained model with different kinds of edge maps


**Experiment States**

Experiment                  | MS-SSIM   | FID   | State                             |
---------                   | --------- |-------|---------                          |
Dataset                     | Done         | -     | -                                 |
pix2pix                     | Done         | -     | -                                 |
Full model                  | Done         | -     | -                                 |
-Distance fields            | Done         | -     | finish training                   |
-Global Discriminator       | Done         | -     | finish training                   |
-Conditional Connection     | Done         | -     | finish training                   |
---------                   | --------- |-------| ---------                         |
CSAM discriminator          | -         | -     | working on code, out of GPU memory|
Resnet pix2pix              | -         | -     | waiting in training list          |

Experiment                  | State                             |
---------                   |---------                          |
Vissulizing attention       | Done                              |
Test different edge maps    | Done, wait to report              |



### Known Errors
- [ ] calutlate FID with the author's code on CelebA dataset: the imagine part is too large when computing coefficient matrix

## Work logs
### 2018-9-3
Test edge maps with different gamma values

### 2018-7-15~22
- [ ] move paper to overleaf
- [ ] contract the author of FID to fix the code of FID
- [ ] add an experiment: test the model with different kinds of edge maps to show the genralizaiton of the model

skip some logs

### 2018-7-13
**TODO List**

- [x] make a list of experiment plans
- [ ] submit experimets to GPU service and record the states
### 2018-7-12
**TODO List**

- [x] edit paper according to last discussion
- [x] emphasize line2face in Introdution and Abstract
- [x] add results and analysis of experiments
- [x] mark experiments to do in red
