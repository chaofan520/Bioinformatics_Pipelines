## HZAU RNA-seq Pipeline
本文主要参考华中农业大学李国亮老师的课程PPT，在此基础上进行打包。本流程的详细信息可以参考：[我的博客 hzau-rna-seq](https://chaofan520.github.io/2025/06/02/hzau-rna-seq/)。

这个我在本地跑了好几遍，只要你环境没问题就行。使用起来非常简单，配置好`config.yaml`文件后，直接在当前路径运行`snakemake`即可：
```shell
snakemake -j 16
```