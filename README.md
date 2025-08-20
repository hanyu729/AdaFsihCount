# AdaFsihCount—Dataset
Aquaculture encompasses a variety of farming practices, such as cage culture and recirculating aquaculture systems. Across different farming modes—or even within the same mode under varying conditions—there exhibit substantial domain gaps arising from changes in water conditions, fish behavior, and camera viewpoints. These domain discrepancies can critically undermine the practical deployment performance of vision-based fish counting methods. To address this, we constructed an optical dataset comprising data from four cage farms and two RAS ponds to support the development of fish counting methods that can adapt to multiple target domains. Further validation was conducted using a publicly available dataset exhibiting variations in lighting conditions.
# 1. Self-collected dataset
All data were collected from the farming systems of Oplegnathus punctatus operated by Laizhou Mingbo Aquatic Co., Ltd., located in Yantai, Shandong Province, China, as illustrated in Fig.1.
| ![Image 1](https://github.com/hanyu729/AdaFsihCount/blob/main/Figs/fig1.png) |
|--------------------------------------------|
| *Figure 1: Data collection location and scenarios.*       |

As shown in Fig.2, cage 1 features a relatively sparse fish distribution with dim, bluish water; Cage 2 exhibits a dense fish distribution with dim, greenish water; Cage 3 has a relatively sparse fish distribution with bright, bluish water; and Cage 4 shows a dense fish distribution with turbid, dark green water. Tank 1 contains a sparse fish distribution with bright, bluish water, while Tank 2 also shows a sparse fish distribution but with greenish water and noticeable impurities on the tank’s inner walls.

| ![Image 2](https://github.com/hanyu729/AdaFsihCount/blob/main/Figs/fig2.png) |
|--------------------------------------------|
| *Figure 2: Example images from different deep-sea cages and aquaculture tanks, with two examples shown for each scenario.* |

**To download the dataset, please visit the [link](https://caueducn-my.sharepoint.com/:u:/g/personal/hanyuu_cau_edu_cn/ETIpzGgoU7VGniB4cLRZYj0BXXrkzZcF9HuAsFbUVnV7xA?e=I2StqQ)！**
# 2. Public datasets
The public Carp Counting Dataset (CCD) is used to validate the proposed method’s adaptability to different scene conditions with other fish species. Following the construction principle of the CCD, source and target domains are defined based on varying lighting conditions: images captured outdoors under daylight serve as the source domain, while images taken indoors during the day and at night with supplemental lighting constitute the target domain. Further details are illustrated in Fig. 3.

| ![Image 3](https://github.com/hanyu729/AdaFsihCount/blob/main/Figs/fig3.png) |
|--------------------------------------------|
| *Figure 3: Example images from the CCD under varying lighting conditions.* |

**The CCD dataset is available upon request from the authors of the cited reference.**
## References
- Xin, J., Wang, Y., Li, D., Xiang, Z., 2025. A fish counting model based on pyramid vision transformer with multi-scale feature enhancement. Ecological Informatics, 103025. [link](https://doi.org/10.1016/j.ecoinf.2025.103025)
