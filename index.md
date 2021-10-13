**Abstract:** Recently, a variety of new equivariant neural network model architectures have been proposed that generalize better over rotational and reflectional symmetries than standard models. These models are relevant to robotics because many robotics problems can be expressed in a rotationally symmetric way. This paper focuses on equivariance over a visual state space and a spatial action space -- the setting where the robot action space includes a subset of SE(2). In this situation, we know a priori that rotations and translations in the state image should result in the same rotations and translations in the spatial action dimensions of the optimal policy. Therefore, we can use equivariant model architectures to make Q learning more sample efficient. This paper identifies when the optimal Q function is equivariant and proposes Q network architectures for this setting. We show experimentally that this approach outperforms standard methods in a set of challenging manipulation problems. 

## Paper
Published at the Conference on Robot Learning (CoRL) 2021  
[OpenReview](https://openreview.net/forum?id=IScz42A3iCI)

[Dian Wang](https://pointw.github.io), 
[Robin Walters](http://mathserver.neu.edu/robin/), 
[Xupeng Zhu](https://www.khoury.northeastern.edu/people/xupeng-zhu/), 
[Robert Platt](http://www.ccs.neu.edu/home/rplatt/)

Khoury College of Computer Sciences  
Northeastern University

## Idea
<p align="center">
  <img src="img/equi_pick.gif">
</p>

## Video

<div style="text-align:center">
	<iframe width="853" height="480" src="https://www.youtube.com/embed/GtdpvjLHc_Q" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

## Code

[https://github.com/pointW/equi_q_corl21](https://github.com/pointW/equi_q_corl21)

## Citation
```
@inproceedings{
wang2021equivariant,
title={Equivariant \$Q\$ Learning in Spatial Action Spaces},
author={Dian Wang and Robin Walters and Xupeng Zhu and Robert Platt},
booktitle={5th Annual Conference on Robot Learning },
year={2021},
url={https://openreview.net/forum?id=IScz42A3iCI}
}
```

## Contact
If you have any questions, please feel free to contact [Dian Wang](https://pointw.github.io) at wang[dot]dian[at]northeastern[dot]edu.
