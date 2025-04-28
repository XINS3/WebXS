这里的能量(energy)是精力分配，情感分配的总称
此处的边可以代表人与人之间的关系链接，节点代表个人

simulate a very simple energy spreading model in small dynamic networks:

* each node i contains energy at moment t: $E_i(t)$
* $w_{ij}$ represents the weight between node i and node j
* Energy spreading formula is: $E_i(t+1)=(1-\alpha)*E_i(t)+\sum_j w_{ji} *E_j(t)$
* where $\alpha$ is energy consuming parameter
* Question:
*   if there is possibility to convergent to balance status finally?
*   如果考虑能量损耗 即 loss rate ($\alpha$) 不为0的情况下: 系统最终会崩溃或者能量耗尽
  


<video width="600" controls>
  <source src="../dynamic_network1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

*  如果不考虑能量损耗，理想情况下某些系统（也取决于网络结构）也可以达到一种平衡
  <video width="600" controls>
  <source src="../dynamic_network.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

2025-4-28
