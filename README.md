Shock filter the image

PDE : df/dt = -sgn(del2(f)) x norm(grad(f))
grad(f) = [fx, fy]^T
norm(grad(f)) = sqrt(fx.^2 + fy.^2)
del2(f) = f_x^2 f_xx + 2 f_x f_y f_xy + f_y^2 f_yy (Jia's paper)
or Laplacian(in general)
del2() func in matlab calculates laplacian: (fxx + fyy) / 4
 
Jiaya Jia: Two-Phase Kernel Estimation for Robust Motion Deblurring
