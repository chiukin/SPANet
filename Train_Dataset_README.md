# Download links

Coming soon!


# Files

* real_world_small.tar.gz.00 - real_world_small.tar.gz.11
* dataset_small_rand.txt

# Unpack

* macOS:

```
$ brew install pigz
$ cat real_world_small.tar.gz.* | unpigz -p 8 | tar -xvC ./
$ rm real_world_small.tar.gz.*
```

* Ubuntu:

```
$ apt install pigz
$ cat real_world_small.tar.gz.* | unpigz -p 8 | tar -xvC ./
$ rm real_world_small.tar.gz.*
```
# Citation


```
@InProceedings{Wang_2019_CVPR,
  author = {Wang, Tianyu and Yang, Xin and Xu, Ke and Chen, Shaozhe and Zhang, Qiang and Lau, Rynson W.H.},
  title = {Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset},
  booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  month = {June},
  year = {2019}
}
```