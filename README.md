This is the source code for the paper: 

Joint Event Extraction via Recurrent Neural Networks

Thien Huu Nguyen, Kyunghyun Cho and Ralph Grishman  (NAACL 2016)

If you use this code, please cite the following paper:

@InProceedings{nguyen-cho-grishman:2016:N16-1,
  author    = {Nguyen, Thien Huu  and  Cho, Kyunghyun  and  Grishman, Ralph},
  title     = {Joint Event Extraction via Recurrent Neural Networks},
  booktitle = {Proceedings of the 2016 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies},
  year      = {2016},
}

----------------

There are two steps to run this code:

1. Preprocessing: using file jee_processData.py

You will need to have the ACE 2005 data set in the formate required by this file.
We cannot include the data in this release due to licence issues.

2. Train and test the model: using file evaluateJEE.py

This step takes the output file in step 1.

There are various parameters of the model you can change directly in the evaluateJEE.py file.

THE CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.