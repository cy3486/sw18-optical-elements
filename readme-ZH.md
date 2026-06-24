# elements

这里放的是我在 SolidWorks 里画光路图时自用的一些元件零件文件。

## 说明

- 建模软件版本：SolidWorks 2018
- 目录用途：搭建激光/非线性光学实验光路时使用的常用器件
- 文件类型：`.SLDPRT` 和 `.SLDASM`

## 零件清单

- `ao_lens.SLDPRT`：凹面镜
- `cylindrical.SLDPRT`：柱面镜
- `etalon.SLDPRT`：标准具
- `flat.SLDPRT`：平面件 / 平面镜类元件
- `hwp.SLDPRT`：半波片
- `hwpjiazi.SLDPRT`：半波片夹具
- `lens.SLDPRT`：凸透镜
- `pbs.SLDASM`：PBS 组件装配体
- `pbs1.SLDPRT`：PBS 零件
- `pinhole.SLDPRT`：光阑
- `PowerMeter.SLDPRT`：功率计
- `SFG.SLDPRT`：和频晶体
- `SHG.SLDPRT`：倍频晶体
- `yuanjia.SLDPRT`：镜架，用于夹持圆形镜片

## 推荐的使用方式

1. 根据需要画出光路的框架(frame.sldprt)作为基准
2. 新建solidworks装配体，并置入frame.sldprt，建议frame.sldprt的基准面与装配体的基准面重合。
3. 按光路需要拖入装配图，并确定零件与frame的几何关系。
4. 自行绘制合适的，用于表示“光”的元件(sldprt)，并绑定到框架上
5. 渲染