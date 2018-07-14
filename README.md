# Daily Work Log
### 2018-7-12
**TODO List**

- [x] 按照上次的讨论修改论文
- [x] 在Abstract和Introduction中强调：我们的任务是Edge2Face- 
- [x] 在Experiment中写出预期结果和分析
- [x] 在Experiment中红字标出后续实验方案

### 2018-7-13
**TODO List**

- [x] 详细列出后续实验
- [ ] summit以上列出的实验并记录实验state

### Experiment List
** Evaluation metirics **
- [x] Code for calcultating MS-SSIM
- [ ] Pix2pix: MS-SSIM, PID
- [ ] Full model: MS-SSIM, PID
- [ ] -Distance fields: MS-SSIM, PID
- [ ] -Spectral Normalization: MS-SSIM, PID
- [ ] -Global Discriminator: MS-SSIM, PID
- [ ] -Conditional Connection: MS-SSIM, PID

** More experiment **
- [ ] CSAM discriminator: add CSAMs to discriminator
- [ ] Resnet pix2pix: increase pix2pix capacity by switch conv_block to res_block
- [ ] Vissulizing attention


** Experiment state **
Experiment                  | MS-SSIM   | FID   | State
----                        | ------    | ---   | ----      
Dataset                     | -         | -     | -
pix2pix                     | -         | -     | -
Full model                  | -         | -     | -
-Distance fields            | -         | -     | training
-Spectral Normalization     | -         | -     | core dump, reason unknown
-Global Discriminator       | -         | -     | training
-Conditional Connection     | -         | -     | training
----                        | ------    | ---   | ---- 
CSAM discriminator          | -         | -     | working on code, out of GPU memory
Resnet pix2pix              | -         | -     | waiting in training list
Vissulizing attention       | -         | -     | working on code
