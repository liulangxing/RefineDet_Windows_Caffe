# RefineDet  Windows  Caffe  VisualStudio-15


## Details
Please take this blog as reference:

[Caffe-ssd 在 windows 下的配置，及 python 调用](https://blog.csdn.net/Chris_zhangrx/article/details/83317721)

## Windows Setup

### Requirements

 - Visual Studio 2013 (**Only with Python2.7**) or 2015 (**with Python 2.7 and Python 3.5**)
 - [CMake](https://cmake.org/) 3.4 or higher (Visual Studio and [Ninja](https://ninja-build.org/) generators are supported)

### Optional Dependencies

 - Python for the pycaffe interface. Anaconda Python 2.7 or 3.5 x64 (or Miniconda)
 - Matlab for the matcaffe interface.
 - CUDA 7.5 or 8.0 (use CUDA 8 if using Visual Studio 2015)
 - cuDNN v5

 We assume that `cmake.exe` and `python.exe` are on your `PATH`.

### Building only for CPU


    1. git clone https://github.com/anlongstory/caffe-ssd-windows

 `2. take this blog as reference:` [Windows 下用 build_win.cmd 直接编译CPU版caffe](https://blog.csdn.net/Chris_zhangrx/article/details/79096015)

and start from **Step 3** which in blog is **`3.修改Caffe配置文件`**


### Building only for GPU

    1. git clone https://github.com/anlongstory/caffe-ssd-windows

   `2. take this blog as reference:` [Windows 下用 build_win.cmd 直接编译GPU版caffe](https://blog.csdn.net/Chris_zhangrx/article/details/83339684)

and start from **Step 5** which in blog is **`5.修改Caffe配置文件`**

### Using the Python interface

You can take this blog as reference: [Windows下 Pycaffe 的配置与使用](https://blog.csdn.net/Chris_zhangrx/article/details/79210288)
