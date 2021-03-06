# Condensed Local Differential Privacy (CLDP)

Condensed LDP (CLDP) is a formal alternative to Local Differential Privacy (LDP). In CLDP, similar outputs are systematically favored to distant outputs using condensed probability when perturbing user data. This repository contains the implementations of our CLDP protocols proposed in:

```
Secure and utility-aware data collection with condensed local differential privacy. 
Gursoy, M. E., Tamersoy, A., Truex, S., Wei, W., & Liu, L. (2019). 
IEEE Transactions on Dependable and Secure Computing.
```

A pre-print version of the paper is [also available on arXiv](https://arxiv.org/pdf/1905.06361.pdf).

## Repository Status

This repository is currently under construction. Eventually, it will contain implementations of the following protocols:

- **Ordinal-CLDP** for collecting user data that stem from finite and discrete metric spaces. Examples include malware infection counts, letters and strings ordered by dictionary order, categorical domains with tree-structured domain taxonomy.
- **Item-CLDP** for collecting user data that stem from non-ordinal discrete spaces. Examples include OS versions, merchant transactions, emojis, and so forth.
- **Sequence-CLDP** for collecting user data that correspond to a *sequence of items*. Examples include computer log files, genomics (DNA sequences), web browsing histories, and location traces. 

We will be gradually cleaning and uploading the code for these protocols. Please check back frequently!

## Project Status

There is ongoing work in our lab regarding LDP, CLDP, and privacy-preserving data analytics. The code in this repository is provided as is, without warranty or support. It is maintained by [M. Emre Gursoy](http://www.memregursoy.com). If you use our code, please cite:

```
@article{gursoy2019secure,
  title={Secure and utility-aware data collection with condensed local differential privacy},
  author={Gursoy, Mehmet Emre and Tamersoy, Acar and Truex, Stacey and Wei, Wenqi and Liu, Ling},
  journal={IEEE Transactions on Dependable and Secure Computing},
  year={2019},
  publisher={IEEE}
}
```
