# Daily Work Logs and Experiment Plans

### Experiment List
**Evaluation metirics**
- [x] Code for calcultating MS-SSIM
- [ ] Pix2pix: MS-SSIM, FID
- [ ] Full model: MS-SSIM, FID
- [ ] -Distance fields: MS-SSIM, FID
- [ ] -Global Discriminator: MS-SSIM, FID
- [ ] -Conditional Connection: MS-SSIM, FID

**More experiment**
- [ ] CSAM discriminator: add CSAMs to discriminator
- [ ] Resnet pix2pix: increase pix2pix capacity by switch conv_block to res_block
- [x] Vissulizing attention
- [x] Test the trained model with different kinds of edge maps


**Experiment States**

Experiment                  | MS-SSIM   | FID   | State                             |
---------                   | --------- |-------|---------                          |
Dataset                     | Done, may discard later | TODO     | Error in computing FID |
pix2pix                     | Done, may discard later | TODO     | Error in computing FID |
Full model                  | Done, may discard later | TODO     | Error in computing FID |
-Distance fields            | Done, may discard later | TODO     | Error in computing FID |
-Global Discriminator       | Done, may discard later | TODO     | Error in computing FID |
-Conditional Connection     | Done, may discard later | TODO     | Error in computing FID |
---------                   | --------- |-------| ---------                         |
CSAM discriminator          | -         | -     | working on code, out of GPU memory|
Resnet pix2pix              | -         | -     | waiting in training list          |

Experiment                  | State                             |
---------                   |---------                          |
Vissulizing attention       | Done                              |
Test different edge maps    | Done, wait to report              |



### Known Errors
- [ ] calutlate FID with the author's code on CelebA dataset: the imagine part is too large when computing coefficient matrix
- [ ] The MS-SSIM is computed pixel-wisely and may not suitable to evaluate the quality of the resutls.

## Work logs
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
