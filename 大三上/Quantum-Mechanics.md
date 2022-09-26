---
Author: USTC-irresistible
Title: Quantum Mechanics
Theme: Haru
---

<center><h1>Quantum Mechanics(Primary)</h1></center>

<p style="text-align:right">14,Septembre,2022</p>

<p style="text-align:right">Lecturer: Prof. Weihua,Wang<br>SolidPhysics,CAS<br>whwangnk@nankai.edu.cn</p>

[toc]



## Jargon List&Terminology

> 非顺序性排列

1. wave-particle duality 
2. Compton scatter
3. normalization:归一化
4. orthogonal:正交的

> Abbreviation explanation

1. Q.M.=Quantum mechanics 
2. C.M. =Classical  mechanics

## Introduction

> # `Question`
>
> ​	Why to learn QM?

+ 研究对象：研究微观粒子运动变化规律的科学
+ 经典力学是量子力学的极限形式
  + 经典力学-非相对论量子力学
  + 相对论力学-相对论量子力学
  + 经典电动力学-量子电动力学
  + 经典统计力学-量子场论&高能物理
  + Planck const: $h=6.62559*10^{-34}$
+ ==光和实物的波粒二象性==是量子力学诞生的基础
+ 旧量子场论：经典理论及与其矛盾的假设
+ 量子：场的最小激发

> #  经典物理的困难

+ 经典物理学的成功

  + Newton mechanics
  + Maxwell Equation

+ 困难

  + 黑体辐射

    + Definition: ==能够吸收射到其上的全部辐射的物体==，全吸收辐射同时自身向外放出辐射

    + Property: 

      + 辐射平衡时，能量密度与辐射波长的分布曲线只与黑体的绝对温度有关，与黑体的形状和材料无关

      + 黑体在任何高于绝对零度的情况下都会辐射电磁波

      + 在相同温度下，黑体的辐射比其他任何物体都强

    + 黑体辐射公式：

      + Wien: 在高频段良好匹配

        $$
        \begin{equation}\rho_{\nu}\mathrm{d}\mu=\nu^3f(\frac{\nu}{T})\mathrm{d}\nu\end{equation}
        $$
  
      + Rdeigh-Jeans: 在低频段良好符合，在高频段发散，紫外灾难
  
        $$
        \rho_{\nu}\mathrm{d}\nu=\frac{8\pi\nu^2}{c^3}k_{B}T\mathrm{d}\nu
        $$
  
    + 黑体辐射的物理机制
  
      + 物体中含有电子、质子等带电粒子，在高于绝对零度的情况下，这些粒子就存在热振动。带电粒子的振动形成==电偶极子==，电偶极子辐射电磁波。带电粒子的温度越高，振动速度越快，辐射强度越高，即黑体辐射与辐射体自身的温度有关，因此黑体辐射也称为热辐射。此外，带电粒子的能量服从玻尔兹曼分布，因此他们具有的能量是连续变化的，并且粒子振动的幅度与取向也是连续变化的，故黑体辐射呈现连续谱分布
  
  + 光电效应
  
    + def: 光照射到金属上，有光电子逸出的现象
    + Property: 存在临界频率$^{1}$，光电子的能量只与入射光频率有关而与光强无关$^{2}$，逸出时间短(ns)$^{3}$
  
  + 氢原子线状光谱(分立光谱)
  
  + 固体的低温电子比热

### birth of the quantum theory

> # Planck黑体辐射定律

+ 黑体空腔壁与辐射的能量交换是不连续的，能量子

+ 辐射的每一个振动方式相当于一个振子，能量值取值的几率与其大小成正比

+ Planck equation:

  $$
  \rho_{\nu}\mathrm{d}\nu=\frac{8\pi\nu^2}{c^3}\frac{h\nu}{e^{\frac{h\nu}{k_{B}T}}-1}\mathrm{d}\nu
  $$

> # 原子结构的波尔理论

+ 玻尔假定，定态条件
  + 能量不连续&角动量量子化
  + 量子跃迁，轨道量子化
+ **局限性**
  + 不能解释除氢原子外更复杂原子的光谱
  + 不能给出谱线（相对）强度
  + 不能处理非束缚问题
  + 玻尔的理论假设没有清晰的理论本质

> # `康普顿效应(compton effect)`
>
> + 光粒子性的进一步验证

+ 康普顿效应：X射线被轻元素(如白蜡、石墨等)散射后，除了原来的波长外，出现了一个新的波长$\lambda\prime$<sup>1</sup>，这一新波长比原来波长$\lambda_{0}$长，并且相对增量$\Delta\lambda$随着散射角$\theta$增大<sup>2</sup>
  $$
  \Delta\lambda=2\lambda_{0}\sin\frac{\theta}{2}
  $$

+ 定性解释

  + 光子与电子碰撞后将部分能量传递给电子，因此散射后的光子能量降低，从而频率降低而波长增大

> # `实物粒子的波粒二象性`
>
> + 德布罗意、戴维孙、G.P汤姆逊

+ L. De Broglie relationship
  $$
  E=h\nu=\hbar\omega\\
  p=\frac{h}{\lambda}=\hbar k
  $$

+ L. De Broglie wave
  $$
  \psi(\vec{r})=Ae^{\frac{i}{\hbar}(\vec{p}\cdot\vec{r}-Et)}
  $$

+ standing-wave condition
  $$
  2\pi r=n\lambda
  $$
  由驻波条件可以道处Bohr的角动量量子化条件

  > 驻波
  >
  > + 振动方向相同
  > + 频率相同
  > + 振幅相同
  > + 传播方向相反

---

## Schrödinger equation and wave function

### Statistical Interpretation

> 波函数的统计解释

1. 状态的描述

   微观粒子的运动状态用波函数描述

2. 玻恩的统计学诠释

   波函数描绘微观粒子的运动状态，波函数在空间中某点的强度(振幅绝对值平方，$|\Psi|^2$)，与在该点找到该粒子的几率成正比，它反映微观粒子运动的统计规律，波函数也称概率幅

   + ==波函数本身没有可观测的物理意义，可观测的是波函数的模==

   > #### 波函数为什么用复数？
   >
   > + The complex number lose the property of magnitude yet remains the associativity and commutativity. As the wave function shall be normalized to one,  and the wave function only represent the state motion of particles, therefore, to compare which wave function is bigger is meaningless. Based on that fact, we use complex forms to describe wave function.

> 波函数的性质

1. 波函数模有概率密度的含义
2. 模平方可积(自由粒子波函数除外)：在全域中找到粒子的概率为一
3. 归一化波函数：相差常数因子倍数的波函数描述同一概率幅
4. 自由粒子的波函数就是平面波的归一化问题

### Principal of superposition state

1. 若$\Psi_{i},i\in N^{+}$是体系可能的状态，则这些状态的线性组合也是体系的可能状态，需要指出的是叠加常数系数是复数
   $$
   \Psi=\sum_{i}C_{i}\Psi_{i},\quad C_{i}\in C
   $$

2. 量子力学中的态叠加与经典物理态叠加的区别

   + 经典中波场的叠加是真实场的叠加，量子力学中的是波函数的叠加
   + 经典中相差常数系数表示的不是同一状态，而量子力学中描述同一状态
   + 量子力学中的波函数不能处处为零，而经典中可以为零(场不存在)

