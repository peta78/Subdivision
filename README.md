# [Subdivision algorithm](https://opus4.kobv.de/opus4-zib/frontdoor/deliver/index/docId/177/file/SC-95-11.pdf) using [PyOpencl](https://github.com/inducer/pyopencl)

Unlike subdivision algorithm, this subdivides in all dimensions at the same time. So minor changes in comparison with [Approximation of box dimension of attractors using the subdivision algorithm](https://www.tandfonline.com/doi/abs/10.1080/14689360500141772). Now with int64 support, you can theoretically go to ((r=20)+1)*(dim=3)=63<64, which is quite furher than the dimension paper.

This works on [Linux Mint](https://linuxmint.com/), [Ubuntu](https://ubuntu.com/), [Sparky Linux](https://sparkylinux.org/) and [arch linux](https://archlinux.org/) (for example Manjaro) as well, after installing [GPU drivers](https://wiki.archlinux.org/title/GPGPU) (for AMD do 'sudo pacman -S rocm-opencl-runtime') and on Microsoft Windows as well with Intel processor.

Chaotic attractor

(2^6)^3 = 262,144 boxes

![chaotic](./images/chaotic_0005.png)

(2^9)^3 = 134,217,728 boxes

![chaotic](./images/chaotic_0008.png)

(2^12)^3 = 68,719,476,736 boxes

![chaotic](./images/chaotic_0011.png)

Rossler attractor

(2^6)^3 = 262,144 boxes

![rossler](./images/rossler_0005.png)

(2^9)^3 = 134,217,728 boxes

![rossler](./images/rossler_0008.png)

Lorenz attractor

(2^6)^3 = 262,144 boxes

![lorenz](./images/lorenz_0005.png)

(2^9)^3 = 134,217,728 boxes

![lorenz](./images/lorenz_0008.png)

Halvorsen attractor

(2^6)^3 = 262,144 boxes

![halvorsen](./images/halvorsen_0005.png)

(2^9)^3 = 134,217,728 boxes

![halvorsen](./images/halvorsen_0008.png)

Or in 3D with [3d glasses needed](https://www.amazon.com/50-Pairs-Glasses-Anaglyph-Cardboard/dp/B07HK9Y6H3/):

![halvorsen](./images/01.png)

![halvorsen](./images/02.png)

![halvorsen](./images/03.png)

![halvorsen](./images/04.png)

![halvorsen](./images/05.png)
