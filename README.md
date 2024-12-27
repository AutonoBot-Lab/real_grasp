

## Requirements
- Python 3.6/3.7/3.8/3.9/3.10
- PyTorch 1.7.1 with CUDA 11.0
- [MinkowskiEngine](https://github.com/NVIDIA/MinkowskiEngine) v0.5.4


## Installation
1. Follow MinkowskiEngine [instructions](https://github.com/NVIDIA/MinkowskiEngine#anaconda) to install [Anaconda](https://www.anaconda.com/), cudatoolkit, Pytorch and MinkowskiEngine. **Note that you need ``export MAX_JOBS=2;`` before ``pip install`` if you are running on an laptop due to [this issue](https://github.com/NVIDIA/MinkowskiEngine/issues/228)**. If PyTorch reports a compatibility issue during program execution, you can re-install PyTorch via Pip instead of Anaconda.

2. Install other requirements from Pip.
```bash
    pip install -r requirements.txt
```

3. Install ``pointnet2`` module.
```bash
    cd pointnet2
    python setup.py install
```

## License Registration
   
Due to the IP issue, currently we can only release the SDK library file of AnyGrasp in a licensed manner. Please get the feature id of your machine and fill in the [form](https://forms.gle/XVV3Eip8njTYJEBo6) to apply for the license. See [license_registration/README.md](license_registration/README.md) for details. **If you are interested in code implementation, you can refer to our [baseline version of network](https://github.com/graspnet/graspnet-baseline), or a third-party implementation of our [GSNet](https://github.com/graspnet/graspness_unofficial).**

We usually reply in 2 work days. If you do not receive the reply in 2 days, **please check the spam folder.**


## Demo Code
Now you can run your code that uses AnyGrasp SDK. See [grasp_detection](grasp_detection) and [grasp_tracking](grasp_tracking) for details.
 
