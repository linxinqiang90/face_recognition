##### cmake
```shell
conda install -c conda-forge cmake
conda install -c conda-forge gcc
conda install -c conda-forge gxx
pip install -r requirements_dev.txt
```

```shell
# rgb_small_frame = small_frame[:, :, ::-1]
rgb_small_frame = np.ascontiguousarray(small_frame[:, :, ::-1])
```
