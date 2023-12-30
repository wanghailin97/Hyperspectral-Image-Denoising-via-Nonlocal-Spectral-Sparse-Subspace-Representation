# Code of NS3R - JSTARS-2023
The released code of NS3R algorithms for HSI denoising, mainly proposed in the paper "Hyperspectral Image Denoising via Nonlocal Spectral Sparse Subspace Representation" which is accepted by the IEEE journal STARS, 2023.

Citation: 

@ARTICLE{10141654,

  author={Wang, Hailin and Peng, Jiangjun and Cao, Xiangyong and Wang, Jianjun and Zhao, Qibin and Meng, Deyu},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  
  title={Hyperspectral Image Denoising via Nonlocal Spectral Sparse Subspace Representation}, 
  
  year={2023},
  
  volume={16},
  
  number={},
  
  pages={5189-5203},
  
  doi={10.1109/JSTARS.2023.3281808}
  }


------ Description-----

--1. The proposed NS3R is very simple and powerful, which first adopts a spectral sparse PCA to get the representation coefficient images (RCIs), then uses a non-local low-rank approximation to further denoise the RCIs, and last get the denoised by inverse spectral sparse PCA.

--2. The proposed spectral sparse PCA startegy is very useful for real HSI denoising, which can adatively distinguishs the complex noise in real HSI data.

--3. The proposed NS3R algorithm achieves very fast denoising speed and meanwhile obatains competitive denoising performance comapred with other state-of-the-art HSI denoising methods, including BM4D, LRMR, TDL, KBR, LLRT, E3DTV, FastHyDe, SNLRSF, NGmeet and TenSRDe. 

------May this work is helpful to you!-----

-------------------------------------------wrriten by Hailin Wang, 2023-6-28--------------------------------------

--if you have any question, please contact me without hesitation--email: wanghailin97@163.com




