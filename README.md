# EyeSearch (Js Version)
# author:wangxinwen, mail: mywcyfl$163.com (replace $ with @)
# all right reserved, 2013-2015.
#
# dependent on pygame, can get it from : http://www.pygame.org

README:
	EyeSearch是一个轻量级SBIR（Sketch-based Image Retireval Engine，草图检索引擎)，
	其核心基于“基于网格多级精确度递进式草图识别算法”，该算法识别物体的过程颇为类似
	于于人眼辨别物体的过程：先站在远处观察各物体模糊的形状进行初步排查，筛选掉一些
	外形差异极大的，然后站近一点做进一步观察与筛选，近一点距离可以观察到更多的细节，
	从而提高精度筛选掉一些上一步无法判别出的物体，如此递进直至剩下最后结果。

目录说明：
	./src/			为当前工程的源码目录，无需解释

补充：
	1.本工程为EyeSearch的js版本，另有python版本名为EyeSearch-py（可在GitHub中搜索到），python版本更为完善与清晰。
	2.出于可读性的考虑，代码在编写时力求简明清晰，代价是牺牲了部分效率。
	3.该算法已提交专利申请，关于算法更多信息可参见此专利权利要求书。
	4.亦可参见本人毕业论文《基于网格多级精确度递进式草图识别算法研究与设计》。
	5.相对于给出了交互体验的python版，js版本仅给出了核心算法。
	5.js版本目前有bug，正在调试中（如果你看到了这句话，说明调试还未完成）。

联系方式：
	中山大学信息科学与技术学院计算机技术（专硕）15届毕业生，王新文，mywcyfl$163.com(replace $ with @)
