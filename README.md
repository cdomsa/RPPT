## RPPT
This repository containts the data files used in the computational experiments in the working paper

> Domínguez, C., Labbé, M., & Marín, A. (2020). The Rank Pricing Problem with Ties.

## Citation

If you use the data in this repository in your own research, please cite the above paper.

## License 

This code is available under the MIT License.

Copyright (C) 2018 Velibor Misic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Repository Structure

This repository contains one directory:

+ `RPPT_DATA`: Contains the data files used in the numerical experiments:
  + `RPPT_DATA_K*_I**_NPREF***_TIES****_INS*****`: contains data for synthetic data instances (see Section 8 of Domínguez et al.), where `*`, `**`, `***` and `****` are the values of *`|K|`*, *`|I|`*, *`n`* and *Ties*, respectively, and  `*****` indicates the number of the instance (there are 5 randomly generated instances for each combination of parameters). Each file includes:
   + K : Number of customers (`|K|` in the paper),
   + I : Number of products (`|I|` in the paper),
   + PREFERENCES : The preference matrix, where entrance `(k,i) = n` if product `i \in S^k_n`, and `(k,i) = 0` if product `i \notin I^k`.
   + BUDGETS : Vector of budgets of each customer.

