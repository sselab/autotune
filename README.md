# Autotune
[Learning-based Automatic Parameter Tuning for Big Data Analytics Frameworks.](https://github.com/sselab/autotune/blob/master/autotune.pdf)

Big data analytics frameworks (BDAFs) have been widely used for data processing applications. These frameworks provide a large number of configuration parameters to users, which leads to a tuning issue that overwhelms users. To address this issue, many automatic tuning approaches have been proposed. However, it remains a critical challenge to generate enough samples in a high-dimensional parameter space within a time constraint. In this paper, we present AutoTune--an automatic parameter tuning system that aims to optimize application execution time on BDAFs. AutoTune first constructs a smaller-scale testbed from the production system so that it can generate more samples, and thus train a better prediction model, under a given time constraint. Furthermore, the AutoTune algorithm produces a set of samples that can provide a wide coverage over the high-dimensional parameter space, and searches for more promising configurations using the trained prediction model. AutoTune is implemented and evaluated using the Spark framework and HiBench benchmark deployed on a public cloud. Extensive experimental results illustrate that AutoTune improves on default configurations by 63.70% on average, and on the five state-of-the-art tuning algorithms by 6%-23%.

This is the full version (12 pages) of the paper submitted to the IEEE Big Data 2018.

We will publish the source code soon...
