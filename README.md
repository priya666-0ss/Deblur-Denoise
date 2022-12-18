# Denoising and Deblurring signals
We are given two signal. xn is true signal and yn is blurred and denoised signal.
we need to obtain xn fron yn by denoising and deblurring it.
We used two appraoches for this.

In this project, we have done two things.
denoise-deblur === First we  have denoise (by simply taking the average) the signal yn and then deblur (inverse fourier tranform) it.
deblur-denoise === First we  have deblur (inverse fourier tranform) the signal yn and then denoise (by simply taking the average) it.
we tried to achieve the target signal xn.

