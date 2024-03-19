# lapack95_fixed_patch

Since [routine `?gelsx` was expaired](https://netlib.org/lapack/lapack-3.1.1/html/zgelsx.f.html), we require lapack95 interface to comment-out the related lines of code.
This repo. provide the patch to `f77_lapack_single_double_complex_dcomplex.f90` and `f95_lapack_single_double_complex_dcomplex.f90` in `LAPACK95/SRC/`.
