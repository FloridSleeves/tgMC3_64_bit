##Installation

```
  cd bit64
  make clean
  make
```

```
  ./mb DATA 			// run MrBayes on a single GPU
  mpiexec -n 2 ./mb DATA 	// run MrBayes on two GPUs
```
The proposed method was tested on GTX580, GTX680 and Tesla K40. However, it may have problems when executed on other GPU platforms. If there are any bugs for MrBayes tgMC3, please do not hesitate to contact the author:

Cheng Ling: lingcheng@mail.buct.edu.cn


