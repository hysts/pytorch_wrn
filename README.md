# PyTorch Implementation of WRN

## Usage

```
$ python main.py --depth 28 --widening_factor 10 --outdir results
```

## Results on CIFAR-10

| Model     | Test Error (median of 3 runs) | Test Error (in paper)   | Training Time |
|:----------|:-----------------------------:|:-----------------------:|--------------:|
| WRN-28-10 | 4.03                          | 4.00 (median of 5 runs) |  16h10m       |

![](figures/WRN-28-10.png)

**NOTE** This model was trained with batch size 64 (128 in paper).

## References

* Sergey Zagoruyko and Nikos Komodakis. Wide Residual Networks. In Richard C. Wilson, Edwin R. Hancock and William A. P. Smith, editors, Proceedings of the British Machine Vision Conference (BMVC), pages 87.1-87.12. BMVA Press, September 2016. [arXiv:1605.07146]( https://arxiv.org/abs/1605.07146 ), [Torch implementation]( https://github.com/szagoruyko/wide-residual-networks )


