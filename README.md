# SAR_basic_concept
Some concepts about SAR image and image formation
## SAR成像原理
SAR利用脉冲压缩技术获得高的距离向分辨率，利用合成孔径原理获得高的方位向分辨率，从而获得高分辨率雷达图像。

SAR回波信号经距离向脉冲压缩后，雷达的距离分辨率由雷达发射信号带宽决定：<a href="https://www.codecogs.com/eqnedit.php?latex=\rho&space;_{r}=\frac{C}{2B_{r}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho&space;_{r}=\frac{C}{2B_{r}}" title="\rho _{r}=\frac{C}{2B_{r}}" /></a>，式中<a href="https://www.codecogs.com/eqnedit.php?latex=\rho_{r}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho_{r}" title="\rho_{r}" /></a>表示雷达的距离分辨率，<a href="https://www.codecogs.com/eqnedit.php?latex=B_{r}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?B_{r}" title="B_{r}" /></a>表示雷达发射信号带宽，C表示光速。

同样，SAR回波信号经方位向合成孔径后，雷达的方位分辨率由雷达方位向的多谱勒带宽决定：<a href="https://www.codecogs.com/eqnedit.php?latex=\rho&space;_{a}=\frac{v_{a}}{B_{a}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho&space;_{a}=\frac{v_{a}}{B_{a}}" title="\rho _{a}=\frac{v_{a}}{B_{a}}" /></a>式中<a href="https://www.codecogs.com/eqnedit.php?latex=\rho&space;_{a}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho&space;_{a}" title="\rho _{a}" /></a>表示雷达的方位分辨率，<a href="https://www.codecogs.com/eqnedit.php?latex=B_{a}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?B_{a}" title="B_{a}" /></a>表示雷达方位向多谱勒带宽，<a href="https://www.codecogs.com/eqnedit.php?latex=v_{a}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{a}" title="v_{a}" /></a>表示方位向SAR平台速度。在小斜视角的情况下，方位分辨率近似表示为<a href="https://www.codecogs.com/eqnedit.php?latex=\rho_{a}=\frac{D}{2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\rho_{a}=\frac{D}{2}" title="\rho_{a}=\frac{D}{2}" /></a>，其中D是方位向合成孔径的长度。

## SAR几何关系
![Alt text](https://github.com/ykl/1.png)

