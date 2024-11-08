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
5. Hermitian:厄米，埃尔米特
6. eigenfunction:本征函数
7. Commutation:对易
8. Harmonic oscillator:谐振子
9. virial theorem:位力定理

> Abbreviation explanation

1. Q.M.=Quantum mechanics 
2. C.M. =Classical  mechanics



---

<center><h1>Main Content</h1></center>

# Main Content

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
  >
  > 驻波特性
  >
  > + 振动距离为半波长整数倍

### Appendix

[附录一](#Appendix_1)  

我们提供了更多的资料供读者阅览，但出于篇幅限制，我们将其放在附录中，读者可以点击上方锚点快速跳往相关位置，此后章节类似并不再说明

---



## Schrödinger equation and wave function

### Statistical Interpretation

> 波函数的统计解释

1. 状态的描述

   微观粒子的运动状态用波函数描述

2. 玻恩的统计学诠释

   波函数描绘微观粒子的运动状态，波函数在空间中某点的强度(振幅绝对值平方，$|\Psi|^2$)，与在该点找到该粒子的几率成正比，它反映微观粒子运动的统计规律，波函数也称概率幅

   + 波函数的强度(模)表示任意时刻粒子在空间位矢处的单位体积中出现的概率

   + ==波函数本身没有可观测的物理意义，可观测的是波函数的模==
   + 波函数描述的概率分布是相对概率分布，这也是为什么常数因子不影响波函数对概率幅的描述
   
   > #### 波函数为什么用复数？
   >
   > + The complex number lose the property of magnitude yet remains the associativity and commutativity. As the wave function shall be normalized to one,  and the wave function only represent the state motion of particles, therefore, to compare which wave function is bigger is meaningless. Based on that fact, we use complex forms to describe wave function.
   > + ......

> 波函数的性质

1. 波函数模有概率密度的含义
2. 模平方可积==(自由粒子波函数除外)==：在全域中找到粒子的概率为一
3. 归一化波函数：相差常数因子倍数的波函数描述同一概率幅
4. 自由粒子的波函数就是平面波的归一化问题
5. 波函数的标准条件(自然边界条件)：单值、有限、连续

> 量子力学的基本假定

1. 波函数完全描述粒子的状态
2. 波函数随时间的演化遵循薛定谔方程

### Principal of superposition state

1. 若$\Psi_{i},i\in N^{+}$是体系可能的状态，则这些状态的线性组合也是体系的可能状态，需要指出的是叠加常数系数是复数
   $$
   \Psi=\sum_{i}C_{i}\Psi_{i},\quad C_{i}\in C
   $$

2. 量子力学中的态叠加与经典物理态叠加的区别

   + 经典中波场的叠加是真实场的叠加，量子力学中的是波函数的叠加
   + 经典中相差常数系数表示的不是同一状态，而量子力学中描述同一状态
   + 量子力学中的波函数不能处处为零，而经典中可以为零(场不存在)

### Coordination&momentum&operator and their average

1. 力学量的平均值

   1. 位置均值
      $$
      \overline{x}=\lang{x}\rang=\int_{-\infty}^{\infty}x|\psi(x)|^2\mathrm{dx}
      $$

   2. 动量均值

      更多参见表象理论
      $$
      \overline{P_{x}}=\int_{-\infty}^{\infty}\hat{P_{x}}|\psi(x)|^2\mathrm{dx}
      $$
      算符$\hat{P_{x}}$表示将动量表示为坐标空间的函数，用算符表示力学量，称为一次量子化

      具体推演参见附录

   3. 力平均值

      对于一个动量为P。势能为V的微观粒子，经典力学基本方程
      $$
      \frac{\mathrm{d\lang P\rang}}{\mathrm{dt}}=\lang-\frac{\partial V}{\partial x}\rang
      $$
      依然成立，上式右侧是力函数的平均值[^2]

      [^2]: 这是埃伦费斯特定理的特殊形式，该定理表明，由量子行为向经典退化的一个途径是取力学量的期望值

      
      $$
      F(x)=\lang-\frac{\partial V}{\partial x}\rang
      $$

2. 算符

   1. 坐标算符

      坐标表示在坐标空间就是它本身，即：
      $$
      \hat{x}=x\\
      \hat{r}=\vec{r}
      $$

   2. 动量算符
      $$
      \hat{P_{x}}=-i\hbar\frac{\mathrm{d}}{\mathrm{dx}}
      $$

      $$
      \hat{\vec{P}}=-i\hbar[\vec{i}\frac{\partial}{\partial x}+\vec{j}\frac{\partial}{\partial y}+\vec{k}\frac{\partial}{\partial z}]=-i\hbar\nabla
      $$

   3. 能量算符
      $$
      \hat{E}=-\frac{\hbar^2}{2m}\nabla^2+V=\hat{H}
      $$

   4. 角动量算符
      $$
      \hat{L}=\hat{r}\times\hat{p}=-i\hbar(\vec{r}\times\nabla)=-i\hbar\begin{bmatrix}i&j&k\\x&y&z\\\frac{\partial}{\partial x}&\frac{\partial}{\partial y}&\frac{\partial}{\partial z}\end{bmatrix}
      $$

3. 算符的本征方程

   通常算符作用在一个函数上得到的是另一个函数，但存在一种特殊情况：==算符作用在一个函数上的结果等于一个常数乘以这个函数本身==，即：
   $$
   \hat{F}\psi=\lambda\psi
   $$
   这个称为算符的本征函数，常数值称为本征值，作用函数称为对应于本征值的本征函数，在量子力学中也称为==本征态==

4. ==量子力学算符的一个基本假设==

   量子力学中表示力学量的算符$\hat{F}$是厄米算符，它们的本征函数构成完备集。当体系处于任意波函数$f(x)$所描述的状态时，力学量F没有确定的数值，而是有一系列可能的取值，这些取值就是算符$\hat{F}$的本征值。

   力学量在任意态中的平均值

   1. 分立谱

      如果体系的状态$f(x)$就是算符$\hat{F}$的一个本征态，那么：
      $$
      \lang\hat{F}\rang=\int\psi^{*}_{n}(x)\hat{F}\psi_{n}(x)\mathrm{dx}=\lambda_{n}
      $$
      任意态函数在本征函数系${\psi_{n}(x)}$的展开为：
      $$
      f(x)=\sum c_{n}\psi_{n}(x)\\
      c_{n}=\int\psi_{n}^{*}(x)f(x)\mathrm{dx}
      $$
      力学量F在任意态$f(x)$的平均值便是：
      $$
      \lang F\rang=\sum_{n}\lambda_{n}|c_{n}|^2
      $$
      它具有统计平均的形式，可以一般性的简化为：
      $$
      \lang \hat{F}\rang=\int f^{*}(x)\hat{F}f(x)\mathrm{dx}
      $$

   2. 连续谱

      如果算符$\hat{F}$的本征值组成连续谱，则相应的本征方程为：
      $$
      \hat{F}\psi_{\lambda}(x)=\lambda\psi_{\lambda}(x)
      $$
      这里的本征值是连续变化的实数，这时本征函数的正交关系为：
      $$
      \int\psi_{\lambda\prime}^{*}\psi_{\lambda}\mathrm{dx}=\delta(\lambda-\lambda\prime)
      $$
      任意态函数$f(x)$在本征函数集${\psi_{\lambda}(x)}$的展开则表示为对本征值的积分：
      $$
      f(x)=\int c(\lambda)\psi_{\lambda}(x)\mathrm{d\lambda}\\
      $$
      连续谱下的概率幅$c(\lambda)$为：
      $$
      \int \psi_{\lambda\prime}^{*}(x)f(x)\mathrm{dx}=\int\psi_{\lambda\prime}^{*}(x)[\int c_{\lambda}\psi_{\lambda}(x)\mathrm{d\lambda}]\mathrm{dx}\\=\int c(\lambda)[\int\psi_{\lambda\prime}^{*}\psi_{\lambda}\mathrm{dx}]\mathrm{d\lambda}\\=\int c(\lambda)\delta(\lambda-\lambda\prime)\mathrm{d\lambda}\\=c(\lambda\prime)
      $$
      即：
      $$
      c(\lambda)=\int\psi_{\lambda}(x)f(x)\mathrm{dx}
      $$
      力学量在$f(x)$态中的平均值为：
      $$
      \lang F\rang=\int \lambda|c(\lambda)|^2\mathrm{d\lambda}
      $$
      连续谱形式下的一般形式与分立谱一致：
      $$
      \lang \hat{F}\rang=\int f^{*}(x)\hat{F}f(x)\mathrm{dx}
      $$

### Static schrödinger equation

1. 定态薛定谔方程
   $$
   \hat{H}\psi(\vec{r})=E\psi(\vec{r})\\
   \hat{H}|\psi\rang=E|\psi\rang
   $$
   不含时间的哈密顿算符的本征方程，即==能量本征方程==，$\psi(\vec{r})$是本征函数或本征态，$E$是本征值，即能量

2. 定态问题求解步骤

   1. 列出定态方程
   2. 基于单值、有限、连续条件给出本征值问题
   3. 解出本征值及其对应本征函数，确定归一化系数
   4. 给出完整含时波函数

3. 性质

   1. 概率密度不随时间演化
   2. 本征解归一化
   3. 平均值不随时间演化，满足守恒定律

### Linear Hamonic oscillator

1. 线性谐振子在平衡点附近的势能形式为
   $$
   U(x)=U(x_{0})+\frac{k}{2}(x-x_{0})^2,\quad k=\mu\omega_{0}^2,固有频率
   $$

2. 线性谐振子势能定态薛定谔方程

   1. 线性谐振子能级
      $$
      E_{n}=(n+\frac{1}{2})\hbar\omega,n\in N
      $$
      $n=0$时的能量称为零点能

### Appendix

[附录二](#Appendix_2)

---

## Barrier and Potential Well

### Potential Well

1. 一维对称无限深势阱
   $$
   \begin{aligned}
   &-\frac{\hbar^2}{2m}\frac{\mathrm{d^2}}{\mathrm{dx^2}}\psi=E\psi\\
   &k^2=\frac{2mE}{\hbar^2}\\
   &\psi=A\cos(kx)+B\sin(kx)\\
   \Leftrightarrow&\psi=C\exp(ikx)+C\prime\exp(-ikx)\\
   \Leftrightarrow&\psi=D\sin(kx+\delta)
   \end{aligned}
   $$

   > 上面三种解的形式是等价的，但在处理不同问题时难易程度不一样
   >
   > 解形式一对于势阱问题直观好理解
   >
   > 解形式二多用于势垒问题
   >
   > 解形式三在利用一些边界条件时方便

   $$
   \begin{aligned}
   &\psi(-a)=A\cos(-ka)+B\sin(-ka)=0\\
   &\psi(a)=A\cos(ka)+B\sin(ka)=0\\
   \Rightarrow&
   \begin{vmatrix}
   \cos(-ka)&\sin(-ka)\\
   \cos(ka)&\sin(ka)
   \end{vmatrix}=0\\
   \Rightarrow&\sin(2ka)=0\\
   \Rightarrow&k=\frac{n\pi}{2a}\\
   \Rightarrow&E_{n}=\frac{n^2\pi^2\hbar^2}{2m(2a)^2}\\
   \Rightarrow&\psi=D\sin\frac{n\pi}{2a}(x+a)\\
   &normalization\\
   \Rightarrow&D=\frac{1}{\sqrt{a}}\\
   \Rightarrow&\psi=\frac{1}{\sqrt{a}}\sin\frac{n\pi}{2a}(x+a),x\in(-a,a),n\in N^{+}
   \end{aligned}
   $$

   从结果看到，n为偶数时为奇函数，波函数具有奇宇称；n为奇数时为偶函数，波函数具有偶宇称

   空间波函数$\psi_{n}(x)$具有$(n-1)$个节点(零点)，其对应的概率密度具有$n$个极大值

2. 高维无限深势阱

   对于高维势阱，进一步分离空间函数，按照类似的方法去推导，就能发现最终的波函数形式是各个正交坐标基矢上波函数的直乘形式
   $$
   \psi(x,y)=\sqrt\frac{2}{l_{x}}\sqrt{\frac{2}{l_{y}}}\sin\frac{n_{x}\pi x}{l_{x}}\sin{\frac{n_{y}\pi y}{l_{y}}}\\
   E_{i}=\frac{n_{i}^2\pi^2\hbar^2}{2ml_{i}^2}
   $$
   
   $$
   \psi(x,y,z)=\sqrt\frac{8}{l_{x}l_{y}l_{z}}\sin\frac{n_{x}\pi x}{l_{x}}\sin\frac{n_{y}\pi y}{l_{y}}\sin\frac{n_{z}\pi z}{l_{z}}\\
   E_{i}=\frac{n_{i}^2\pi^2\hbar^2}{2ml_{i}^2}
   $$
   当各个方向上的势阱长度相等时，就会出现能级简并，能量本征值为
   $$
   E=\frac{\pi^2\hbar^2}{2ma^2}\sum n_{i}^2
   $$
   能级的简并度取决于
   $$
   \sum n_{i}^2=\frac{2ma^2E}{\pi^2\hbar^2}
   $$
   的整数解$(n_{1},n_{2},\cdots)$的个数

3. 态密度

   态密度就是单位能量范围内的状态数

   本节式子中：势阱全为无限深，$N$为势阱中占据的量子态总数，能量为E，各方向上势阱宽度为L，质量为m
   $$
   \rho(E)=\frac{\mathrm{dN}}{\mathrm{dE}}
   $$
   

   1. 一维势阱

      一维势阱中，设一个粒子占据一个本征态，一维中，量子态总数与本征态总数相等，即$N=n$
      $$
      \begin{aligned}
      &E=\frac{n^2\pi^2\hbar^2}{2mL^2}=\frac{N^2\pi^2\hbar^2}{2mL^2}\\
      &\mathrm{dE}=\frac{N\pi^2\hbar^2}{mL^2}\mathrm{dN}\\
      &\rho(E)=\frac{L}{2\pi\hbar}\sqrt{\frac{2m}{E}}
      \end{aligned}
      $$

   2. 二维势阱

      设一个粒子占据一个本征态，二维中，一个量子态由坐标$(n_{1},n_{2})$表征，坐标系中每一个点表征一个量子态。空间中总量子态数就是以$\sqrt{n_{1}^2+n_{2}^2}$为半径的四分之一圆的面积，这是因为$n_{i}$全是正整数。
      $$
      \begin{aligned}
      &N=\frac{1}{4}\pi(n_{1}^2+n_{2}^2)\\
      &E=\frac{\pi^2\hbar^2}{2mL^2}(n_{1}^2+n_{2}^2)\\
      &\rho(E)=\frac{L^2m}{2\pi\hbar^2}
      \end{aligned}
      $$
      可见，二维无限深势阱中态密度与能量本征值无关

   3. 三维势阱——==金属自由电子气模型==

      同样地，三维中，一个量子态由坐标$(n_{1},n_{2},n_{3})$表征，空间中总量子态数是以$\sqrt{n_{1}^2+n_{2}^2+n_{3}^2}$为半径的八分之一球空间的点数目，即体积大小。
      $$
      \begin{aligned}
      &N=\frac{1}{8}\frac{4\pi}{3}(n_{1}^2+n_{2}^2+n_{3}^2)^{\frac{3}{2}}\\
      &E=\frac{\pi^2\hbar^2}{2mL^2}(n_{1}^2+n_{2}^2+n_{3}^2)\\
      &\rho(E)=\frac{L^3}{4\pi^2\hbar^3}(2m)^{\frac{3}{2}}\sqrt{E}
      \end{aligned}
      $$

4. 费米面与费米能级

   > 联动半导体物理学习

   令三维无限深势阱中体系的本征能量方程为
   $$
   E=\frac{\hbar^2}{2m}(\frac{n_{1}^2\pi^2}{L_{x}^2}+\frac{n_{2}^2\pi^2}{L_{y}^2}+\frac{n_{3}^2\pi^2}{L_{z}^2})=\frac{\hbar^2k^2}{2m}
   $$

   $$
   \vec{k}\equiv\{k_{x},k_{y},k_{z}\}=\{\frac{n_{1}\pi}{L_{x}},\frac{n_{2}\pi}{L_{y}},\frac{n_{3}\pi}{L_{z}}\}
   $$

   这是固体中电子波矢量的允许值，对应三维k空间的第一卦限

   1. 费米面

      在三维k空间中，每个电子态占据的体积为$\frac{\pi^3}{L_{x}L_{y}L_{z}}=\frac{\pi^3}{V}$。假设固体包含$N$个原子，每个原子具有$q$个自由电子。一个电子有两种自选状态，因此每个状态占据的体积为$\frac{\pi^3}{2V}$，其倒数即为==态密度==

      k空间中电子对应占据的八分之一球体半径为$k_{F}$，空间中所有$Nq$个电子状态占据的体积等于空间的体积
      $$
      \begin{aligned}
      &Nq\frac{\pi^3}{2V}=\frac{\pi k_{F}^3}{6}\\
      &\rho=\frac{Nq}{V},自由电子密度\\
      &k_{F}=(3\rho\pi^2)^{\frac{1}{3}}
      \end{aligned}
      $$
      ==k空间中电子态所占据的区域与未被占据部分的分界面称为费米面==，是一个八分之一球面，球半径为$k_{F}$，即费米半径

   2. 费米能级

      费米半径对应的能级称费米能级，对于自由电子气
      $$
      E_{F}=\frac{\hbar^2k_{F}^2}{2m}
      $$

   3. 体积为V的固体中全部电子的总能量

      k空间中八分之一球壳的体积是
      $$
      \frac{1}{8}4\pi k^2\mathrm{dk}
      $$
      这一球壳中的电子态数目为
      $$
      \frac{1}{2}\pi k^2\mathrm{dk}*\frac{2V}{\pi^3}
      $$
      总能量为
      $$
      \frac{1}{2}\pi k^2\mathrm{dk}*\frac{2V}{\pi^3}*\frac{\hbar^2 k^2}{2m}
      $$
      积分结果
      $$
      E=\frac{\hbar^2 V k_{F}^5}{10\pi^2m}
      $$

### Barrier

​	势垒贯穿是一维散射问题

​	下面假定粒子从无限远处沿坐标轴正向射入势垒，势垒的势函数如下
$$
V(x)=\begin{Bmatrix}
V_{0},x\in(0,a)\\
0,else
\end{Bmatrix}
$$
​	这一问题我们需要探索反射系数和透射系数。反射系数是反射粒子数与入射总粒子数之比，即反射流密度与入射流密度之比。根据概率流密度守恒，透射系数即用一减去反射系数即可

​	由于势垒的存在，在$x\in(-\infty,0)$区域内，即存在入射粒子，也存在反射粒子；在$x\in(a,\infty)$区域内，只有透射粒子存在。波函数形式如下
$$
\psi(x)=\begin{Bmatrix}
Ae^{ikx}+Re^{-ikx},x\in(-\infty,0)\\
Se^{ikx},x\in(a,\infty)
\end{Bmatrix}
$$
​	入射流粒子密度
$$
J_{in}=\frac{i\hbar}{2m}(\psi\nabla\psi^{*}-\psi^{*}\nabla\psi)=\frac{A^2\hbar k}{m}
$$
​	类似地有反射和投射粒子流密度，进一步得到投射和反射系数
$$
Re=R^2,Tr=S^2,(取A^2=1)
$$
​	在势垒内部的定态方程
$$
\frac{\mathrm{d^2}}{\mathrm{dx^2}}\psi-\frac{2m}{\hbar^2}(V_{0}-E)\psi=0
$$
​	边界条件由波函数及其一阶导数在$x=0$的连续性确定

​	剩下的工作就与前面类似了

​	结论就是即便在入射能量小于势垒的情况下，透射系数依然不为零，这一现象就是量子隧穿效应

---

## Harmonic osicllator

​	只要振幅足够小，任何震动都可以近似为简谐振动。固体中的晶格振动、原子核的表面振动、分子与分子之间的相互作用势、核子与核子之间的相互作用势，这些势场在平衡点附近的展开准确到二阶后就是谐振子势

​	在物理上，任何连续振动的体系，都可以等价地看成无限多个谐振子的集合，比如辐射场可以看成是无穷多个谐振子发出的简谐波的叠加

### Algebraic analysis

​	代数揭发指的是通过算符代数运算的方法求解量子谐振子的本征问题

---



## Operators

### Hermitian operator

​	所有力学量的数值都是实数。当量子体系处于一个算符的本征态时，该算符的本征值就是这个力学量的取值，这样的本征值必须为实数。厄米算符的本征值就是实数，因此==量子力学中表示力学量的算符都是厄米算符==

#### Definition

1. 厄米算符定义

   对于任意两个函数$\psi,\phi$，如果算符$\hat{F}$满足如下等式：
   $$
   \int\psi^{*}\hat{F}\phi\mathrm{dx}=\int(\hat{F}\psi)^{*}\phi\mathrm{dx}
   $$
   则称该算符为厄米算符

2. 算符的厄米共轭

   算符$\hat{F}$的厄米共轭用$\hat{F}^{\dagger}$表示，定义如下：
   $$
   \int(\hat{F}\psi)^{*}\phi\mathrm{dx}=\int\psi^{*}\hat{F}^{\dagger}\phi\mathrm{dx}
   $$
   比较厄米算符的定义可以知道，==如果一个算符与它的厄米共轭相等，这该算符是厄米算符==，这也是厄米算符的另一种定义
   
3. 体系的哈密顿算符是厄米算符

#### Properties of eigenfunction

​	厄米算符本征函数具有以下性质：

1. 正交性

   相互正交的定义如下：两个函数$\psi_{1},\psi_{2}$满足关系式
   $$
   \int\psi_{1}\psi_{2}^{*}\mathrm{dx}=0
   $$
   ==厄米算符属于不同本征值的两个本征函数相互正交==

2. 完备性

   设厄米算符$\hat{F}$的正交归一本征函数是$\phi_{n}(x)$，对应的本征值是$\lambda_{n}$，则任意函数$\psi(x)$可以按$\phi_{n}(x)$展开为级数
   $$
   \psi_{x}=\sum_{n}c_{n}\phi_{n}(x)
   $$
   系数$c_{n}$与自变量无关。本征函数具有的这种性质称为完备性

### Commutation relation

​	**所谓对易，就是在运算过程中可以调换顺序**

​	在经典力学中，所有力学量都用函数表示，他们之间都是对易的

​	但在量子力学中，算符之间存在不对易性。量子力学算符对易关系定义如下：

​	
$$
[\hat{A},\hat{B}]=\hat{A}\hat{B}-\hat{B}\hat{A}
$$

#### Commonly used commutation identity

1. 对易式满足的代数恒等式
   $$
   \begin{aligned}
   &[\hat{A},\hat{B}]=-[\hat{B},\hat{A}]\\
   &[\hat{A},\hat{A}]=0\\
   &[\hat{A},c]=0\\
   &[\hat{A},\hat{B}+\hat{C}]=[\hat{A},\hat{B}]+[\hat{A},\hat{C}]\\
   &[\hat{A},\hat{B}\hat{C}]=\hat{B}[\hat{A},\hat{C}]+[\hat{A},\hat{B}]\hat{C}\\
   &[\hat{A}\hat{B},\hat{C}]=\hat{A}[\hat{B},\hat{C}]+[\hat{A},\hat{C}]\hat{B}\\
   &[\hat{A},\hat{B}]^{\dagger}=[\hat{B}^{\dagger},\hat{A}^{\dagger}]\\
   &[\hat{A},[\hat{B},\hat{C}]]+[\hat{B},[\hat{C},\hat{A}]]+[\hat{C},[\hat{A},\hat{B}]]=0
   \end{aligned}
   $$

2. 设$\vec{A},\vec{B}$为矢量算符，$F$为标量算符
   $$
   \begin{aligned}
   &[F,\vec{A}\cdot\vec{B}]=F\vec{A}\cdot\vec{B}-\vec{A}\cdot\vec{B}F\\
   &[F,\vec{A}\times\vec{B}]=\vec{A}\times[F,\vec{B}]+[F,\vec{A}]\times\vec{B}
   \end{aligned}
   $$

3. 设算符${A},{B}$和他们的对易式$[{A},{B}]$都对易，有
   $$
   \begin{aligned}
   &[A,B^n]=nB^{n-1}[A,B]\\
   &[A^n,B]=nA^{n-1}[A,B]
   \end{aligned}
   $$

#### Commutation indentity

1. 如果$[A,B]\neq 0$，$\lambda$是实数，则有
   $$
   e^{\lambda A}F(B)e^{-\lambda A}=F(e^{\lambda A}Be^{-\lambda A})
   $$

2. **Hadamard**公式

   如果$[A,B]\neq 0$，则有
   $$
   e^{A}Be^{-A}=B+\frac{1}{1!}[A.B]+\frac{1}{2!}[A,[A,B]]+\frac{1}{3!}[A,[A,[A,B]]]+\cdots
   $$
   证明提示：参量微分法，构造$F(\lambda)=e^{A\lambda}Be^{-A\lambda}$，在零点泰勒展开比对即可

3. **Baker-Campbell-Hausdriff**公式

   在处理指数形式算符的过程中，BCH公式特别实用

   如果算符$\hat{A},\hat{B}$满足$[\hat{A},\hat{B}]=\hat{C}$，并且算符$\hat{C}$和算符$\hat{A},\hat{B}$对易，则有：
   $$
   \exp(\hat{A}\alpha+\hat{B}\beta)=exp(\hat{B}\beta)\exp(\hat{A}\alpha)\exp(\frac{\beta\alpha}{2}\hat{C})
   $$

#### Basic commutation

​	力学量都是坐标和动量的函数，利用位置和动量之间的对易关系可以得出其他力学量之间的对易关系，因此位置和动量的对易关系称为基本对易式
$$
[\hat{x_{\alpha}},\hat{p_{\beta}}]=i\hbar\delta_{\alpha\beta}
$$
其中$\hat{x_{\alpha}}(\alpha=1,2,3)\equiv(x,y,z),\hat{p_{\beta}}(\beta=1,2,3)\equiv(\hat{p_{x}},\hat{p_{y}},\hat{p_{z}})$

​	对易关系本质是算符间作用于波函数的一种表达，所以在证明对易关系时要借助波函数$\psi$

​	相关证明参见本节附录

#### commutation linked with momentum and coordination

​	以下公式族中$\vec{r}$表示位置算符，$F(\vec{r},\vec{\hat{p}})$为标量算符，$V(r)$为标势
$$
\begin{aligned}
&{[p_{x},f(x)]}=-i\hbar\frac{\partial}{\partial x}f(x)\\
&[\vec{p},F]=-i\hbar\nabla F\\
&[\vec{p},V(r)]=-i\hbar\nabla V(r)\\
&[\vec{p},\frac{1}{r}]=i\hbar\frac{\vec{r}}{r^3}\\
&[p^2,\frac{1}{r}]=2\hbar^2\frac{1}{r^2}\frac{\partial}{\partial r}\\
&[p^2,r^2]=-\hbar^2(6+4r\frac{\partial }{\partial r})\\
&[\vec{r},F]=i\hbar\frac{\partial}{\partial\vec{p}}F\\
&[\vec{r},p^2]=2i\hbar\vec{p}\\
&[\vec{r}\cdot\vec{p},p^2]=2i\hbar p^2\\
&[\vec{r}\cdot\vec{p},V(r)]=-i\hbar\vec{r}\cdot(\nabla V(r))
\end{aligned}
$$
​	部分相关证明参见本节附录

#### Physical meaning of commutative operators

1. ==定理==

   如果两个算符有一组共同的本征矢$|n\rang$，并且它们构成完备集，则这两个算符对易

2. 逆定理

   如果两个算符对易，则他们有共同的本征矢

3. 推广定理

   如果一组算符有共同的本征矢，且它们构成完备集，则这一组算符中任意两个算符对易，并且该定理的逆定理也成立

### Appendix

[附录三](#Appendix_3)

---

## Conserved quantity

### Ehrenfest principal

1. ==埃伦费斯特定理==

   埃伦费斯特定理时描述力学量的平均值随时间的演化关系

   >  注意这里描述的是力学量的平均值对时间的演化，而不是力学量随时间变化的平均值

   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang A\rang=\frac{1}{i\hbar}[A,H]+\lang\frac{\partial A}{\partial t}\rang
   $$

   数学证明参见附录

2. ==海森堡运动方程==

   当力学量不随时间演化，埃伦费斯特定理就转化为海森堡运动方程
   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang A\rang=\frac{1}{i\hbar}[A,H]
   $$
   
3. 位置、动量和力的平均值关系
   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang x\rang=\frac{1}{i\hbar}\lang[x,H]\rang=-\frac{1}{i\hbar}\lang[H,x]\rang\\
   =\frac{i}{\hbar}\lang[H,x]\rang=\frac{i}{2m\hbar}\lang[p_{x}^2+p_{y}^2+p_{z}^2,x]\rang\\
   =\frac{i}{2m\hbar}\lang[p_{x}^2,x]\rang=\frac{i}{2m\hbar}\lang p_{x}[p_{x},x]\rang+\frac{i}{2m\hbar}\lang[p_{x},x]p_{x}\rang\\
   =\frac{1}{m}\lang p_{x}\rang
   $$

   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang\vec{r}\rang=\frac{1}{m}\lang\vec{p}\rang
   $$

   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang p_{x}\rang=\lang-\frac{\partial V}{\partial x}\rang
   $$

   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang \vec{p}\rang=\lang-\nabla V\rang
   $$

   这些结果与经典力学的牛顿定律形式是一致的

### Virial theorem

1. 位力定理描述当体系处于定态下与动能相关的平均值 
   $$
   2\lang T\rang=\lang\vec{r}\cdot(\nabla V)\rang
   $$
   数学证明见附录

   特别的，如果势场$V(x,y,z)$是$x,y,z$的$n$次齐次函数，则有
   $$
   2\lang T\rang=n\lang V\rang
   $$
   这一关系称为==欧拉齐次定理==

   1. 对于谐振子势，$n=2$
   2. 对于库伦势，$n=1$
   3. 对于$\delta$势，$n=-1$

### Hellmann-Feynman theorem

1. 借助赫尔曼-费曼定理可以得出关于力学量平均值的许多信息而不必借助波函数进行繁琐计算

   设体系的哈密顿量中含有某个参数$\lambda$，$E_{n}$是体系哈密顿量的本征值，相应的本征函数已经归一化，则有
   $$
   \frac{\partial E_{n}}{\partial t}=\lang\psi_{n}|H|\psi_{n}\rang
   $$
   数学证明参见附录

### Appendix

[附录四](#Appendix_4)

---



## Dirac notation

### Basic form

​	在量子力学中，系统的状态由波函数描述的是波动力学的方法，也可以用态矢量描述，这是矩阵力学的方法。采用狄拉克符号能直观地表达量子力学的概念和量子系统的性质，并能用来简洁的处理运算过程

1. 系统的态用狄拉克符号==$|\rang$==来表示，例如

   1. $|\Psi\rang$表示波函数$\Psi$
   2. $\lang\Psi|$表示波函数$\Psi$的复共轭$\Psi^{*}$
   3. $|\psi_{n}\rang$表示一个算符的本征态
   4. $|x\prime\rang$表示坐标的本征态，本征值为$x\prime$
   5. $|p\prime\rang$表示动量的本征态，本征值为$p\prime$
   6. $|lm\rang$表示$(l^2,l_{z})$的共同本征态，本征值分别为$l(l+1),m\hbar$

2. 分立谱，算符本征态的正交归一性表示为：
   $$
   \int\psi_{m}^{*}\psi_{n}\mathrm{dx}=\lang\psi_{m}|\psi_{n}\rang=\delta_{mn}
   $$

3. 连续谱，算符本征态的正交归一性表示为：
   $$
   \int\psi_{\lambda\prime}^{*}\psi_{\lambda}\mathrm{dx}=\lang\psi_{\lambda\prime}|\psi_{\lambda}\rang=\delta(\lambda-\lambda\prime)
   $$

4. 在矩阵力学中，本征态$|\psi_{n}\rang$称为==本征矢(基矢)==，$\lang\psi_{m}|\psi_{n}\rang$可以理解为基矢$|\psi_{n}\rang$向基矢$\lang\psi_{m}|$的投影，下标不同时，二基矢正交，投影为零；下标相同时两者重合

5. 任意两个量子态的内积表示为：
   $$
   \int\psi^{*}\phi\mathrm{dx}=\lang\psi|\phi\rang
   $$
   这个也可以理解为态矢量之间的投影。复共轭形式为
   $$
   \lang\psi|\phi\rang^{*}=\lang\phi|\psi\rang
   $$

6. 一个任意态矢量$|\psi\rang$向坐标本征矢$\lang x|$的投影就是这个态以$x$为变量的波函数
   $$
   \lang x|\psi\rang=\psi(x)
   $$

7. 算符$\hat{F}$的本征方程为
   $$
   \hat{F}|\psi_{n}\rang=\lambda_{n}|\psi_{n}\rang
   $$

8. 薛定谔方程表示为
   $$
   i\hbar\frac{\mathrm{d}}{\mathrm{dt}}|\psi(t)\rang=\hat{H}|\psi(x)\rang
   $$

9. 一个算符$\hat{F}$作用于态矢量$|\psi(x)\rang$得到新的态矢量$|\phi(x)\rang=\hat{F}|\psi(x)\rang$，它的复共轭为
   $$
   \lang\phi(x)|=(\hat{F}|\psi(x)\rang)^{*}=\lang\psi(x)|F^{\dagger}
   $$

10. 算符$\hat{F}$在任意态$|\psi\rang$的平均值(期望)表示为
    $$
    \int\psi^{*}\hat{F}\psi\mathrm{dx}=\lang\psi|\hat{F}\psi\rang=\lang\hat{F}\rang
    $$

11. 投影算符

    投影算符的一般定义为$|\alpha\rang\lang\beta|$，它作用于$|\Psi\rang$给出$|\alpha\rang\lang\beta|\Psi\rang$，这是将态矢量$\Psi$投影到态矢量$|\alpha\rang$上，给出一个长度为$\lang\beta|\Psi\rang$、沿$|\alpha\rang$方向的态矢量
    $$
    |\alpha\rang\lang\beta|\Psi\rang=\lang\beta|\Psi\rang|\alpha\rang
    $$
    

---



<center><h1>Appendix List</h1></center>

# Appendix

## 附录一

<a id="Appendix_1">附录一锚点</a>

1. 关于瑞丽-金斯定律

​	黑体辐射的平衡状态时内部辐射的能量等于吸收的能量，从表观看等效于无能量发散。==黑体辐射平衡空腔内的电磁波均为驻波。==

​	根据驻波特性：振动的距离为半波长的整数倍；存在结点，结点在内壁上[^1]

[^1]: 参见《光学》

​	另外，==当波阵面固定时，从一个方向上观察，在该方向上，两个波阵面之间的最小距离为空间周期，其倒数即为空频==[^1]，翻译成数学如下，其中$\alpha,\beta,\gamma$为空间直线方位角：
$$
\frac{\lambda_{x}}{2}\cos\alpha=\frac{\lambda}{2}\\
\frac{\lambda_{y}}{2}\cos\beta=\frac{\lambda}{2}\\
\frac{\lambda_{z}}{2}\cos\gamma=\frac{\lambda}{2}
$$
​	根据驻波振动距离为半波长整数倍的特性：
$$
n_{x}\lambda_{x}=2a\quad n_{y}\lambda_{y}=2a\quad n_{z}\lambda_{z}=2a
$$
​	由上两式可以得到：
$$
\frac{1}{\lambda^2}=\frac{n_{x}^2+n_{y}^2+n_{z}^2}{(2a)^2}
$$
​	上式表明，一组正整数$(n_{x},n_{y},n_{z})$对应一个波长

​	在$\lambda$到$\lambda+\mathrm{d}\lambda$范围内包含的能量等于在这一范围内存在多少个波长，等价于存在多少组这样的数，即在空间中存在多少个点。注意到上式的数学意义表征一个球，由于全为正整数，实际上反映的只有八分之一个球。定义：
$$
n^2=n_{x}^2+n_{y}^2+n_{z}^2
$$
这样就将问题转化为半径为n，厚度为$\mathrm{dn}$的球壳内存在多少个点。我们知道一个立方体的顶点被八个全同的立方体共用，相当于一个立方体内只有一个点。于是球点的个数等效于球体积，即波的个数为：
$$
\frac{1}{8}4\pi n^2\mathrm{dn}
$$
​	电磁波是两个互相垂直的振动，因此乘以前置系数2
$$
2\cdot\frac{1}{8}4\pi n^2\mathrm{dn}
$$
​	利用光速公式：
$$
\lambda=\frac{c}{\nu}=\frac{2a}{n}
$$
​	根据能均分定理。一个波长分到kT的能量。由以上，得到频率$\mathrm{d\nu}$内单位体积的能量为：
$$
\rho(\nu)\mathrm{d\nu}=\frac{2\cdot\frac{1}{8}\cdot 4\pi (\frac{2a\nu}{c})^2\frac{2\nu}{c}\mathrm{d\nu}}{a^3}kT
$$

2. 戴维孙-革末电子衍射实验

   内容：电子正入射到镍单晶上观察电子束强度和散射角之间的关系

   现象：散射电子束强度随散射角改变，当取某些散射角时散射强度具有最大值

   结论：电子具有波动性

3. 斯特恩-盖拉赫实验

   结论：氢原子有磁矩，原子的磁矩在磁场中只有两种取向，即==原子磁矩时空间量子化的==

4. 玻尔-索末非量子化条件

   玻尔角动量量子化条件仅使用于圆形轨道，索末非将玻尔角动量量子化条件推广为
   $$
   \oint p\mathrm{dq}=nh
   $$
   注意这里是普朗克常数而不是约化普朗克常数。$p,q$是一对共轭的正则坐标与正则动量，闭合回路积分代表对周期运动积分的一个周期

## 附录二

<a id="Appendix_2">附录二锚点</a>

1. 薛定谔方程推演

   由自由粒子波函数及德布罗意关系：
   $$
   \varepsilon(\vec{r},t)=\varepsilon_{0}e^{i(\vec{k}\cdot\vec{r}-\omega t)}\\
   \vec{p}=\hbar k,E=\hbar\omega
   $$
   自由粒子波函数为：
   $$
   \Psi(\vec{r},t)=A\exp\frac{i}{\hbar}(\vec{p}\cdot\vec{r}-Et)
   $$
   将上式分别对时间求一阶偏导和对坐标求二阶偏导得到：
   $$
   \frac{\partial\Psi}{\partial t}=-\frac{i}{\hbar}E\Psi\\
   \frac{\partial^2\Psi}{\partial x^2}=-\frac{p_{x}^2}{\hbar^2}\Psi\\
   \frac{\partial^2\Psi}{\partial x^2}=-\frac{p_{y}^2}{\hbar^2}\Psi\\
   \frac{\partial^2\Psi}{\partial x^2}=-\frac{p_{z}^2}{\hbar^2}\Psi
   $$
   其中：
   $$
   \vec{p}\cdot\vec{r}=(p_{x}i+p_{y}j+p_{z}k)\cdot(xi+yj+zk),\quad i,j,k=\vec{i},\vec{j},\vec{k}
   $$
   注意Laplace算符，于是：
   $$
   \nabla^2\Psi=-\frac{p^2}{\hbar^2}\Psi\\
   i\hbar\frac{\partial\Psi}{\partial t}=E\Psi=\frac{\hbar^2p^2}{2m\hbar^2}\Psi=-\frac{\hbar^2}{2m}\nabla^2\Psi
   $$
   一般地粒子在势场中存在势场，于是：
   $$
   E=\frac{p^2}{2m}+V(\vec{r})\\
   i\hbar\frac{\partial\Psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\Psi+V(\vec{r})\Psi
   $$

2. 概率流守恒定律

   概率流守恒定律自动地包含在薛定谔方程中，下面从波函数的统计解释出发得到这一结论
   $$
   \rho=\rho(\vec{r},t)=\Psi(\vec{r},t)\Psi^{*}(\vec{r},t)=\Psi\Psi^{*}
   $$
   概率密度随时间的变化率为：
   $$
   \frac{\partial\rho}{\partial t}=\Psi\frac{\partial\Psi^{*}}{\partial t}+\Psi^{*}\frac{\partial\Psi}{\partial t}
   $$
   由薛定谔方程：
   $$
   i\hbar\frac{\partial\Psi}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\Psi+V(\vec{r})\Psi
   $$

   $$
   \frac{\partial\Psi}{\partial t}=\frac{i\hbar}{2m}\nabla^2\Psi+\frac{1}{i\hbar}V(\vec{r})\Psi\\
   \frac{\partial\Psi^{*}}{\partial t}=-\frac{i\hbar}{2m}\nabla^2\Psi^{*}-V(\vec{r})\Psi^{*}
   $$

   得到概率随时间的变化关系式为：
   $$
   \frac{\partial\rho}{\partial t}=\frac{i\hbar}{2m}(\Psi^{*}\nabla^2\Psi-\Psi\nabla^2\Psi^{*})=\frac{i\hbar}{2m}\nabla\cdot(\Psi^{*}\nabla\Psi-\Psi\nabla\Psi^{*})
   $$
   令($\vec{J}$称为概率流密度)：
   $$
   \vec{J}=-\frac{i\hbar}{2m}(\Psi^{*}\nabla\Psi-\Psi\nabla\Psi^{*})
   $$
   即：
   $$
   \frac{\partial\rho}{\partial t}+\nabla\vec{J}=0
   $$
   概率流守恒定律表明：==在相对论力学中，一般来说，粒子既不能产生，也不会湮灭，体系的离子数守恒，粒子必然会在全空间出现，这是个必然事件。即，在全空间中找到粒子的概率为1==

3. 波函数归一化的时间不变性

   数学表述：
   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\int_{-\infty}^{\infty}\Psi\Psi^{*}\mathrm{d\vec{r}}=0
   $$
   证明阐述：

   ​	从玻恩的统计学诠释中可以证明这一点：波函数强度表征在任意时刻在空间位矢处找到粒子的概率密度，因此全空间积分值为1，即需要满足归一化条件。隐藏条件时，在任意时刻都能找到这个粒子，即任意时刻必须归一化为1

4. 动量算符推演

   数学推演：
   $$
   \frac{\mathrm{d\lang{x}\rang}}{\mathrm{dt}}=\int_{-\infty}^{\infty}x\frac{\partial}{\partial t}(|\Psi|^2\mathrm{dx})
   $$
   注意到：
   $$
   i\hbar\frac{\partial}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2
   $$
   即：
   $$
   \lang{v}\rang=\frac{\mathrm{d\lang{x}\rang}}{\mathrm{dt}}=\frac{i\hbar}{2m}\int_{-\infty}^{\infty}x\frac{\partial}{\partial x}\big(\frac{\partial}{\partial x}(\Psi\Psi^{*})\big)\mathrm{dx}\\=
   \frac{i\hbar}{2m}\int_{-\infty}^{\infty}x\frac{\partial}{\partial x}\big(-\Psi\frac{\partial \Psi^{*}}{\partial x}+\Psi^{*}\frac{\partial\Psi}{\partial x}\big)\mathrm{dx}\\=
   \frac{i\hbar}{2m}x\big(-\Psi\frac{\partial \Psi^{*}}{\partial x}+\Psi^{*}\frac{\partial\Psi}{\partial x}\big)|_{-\infty}^{\infty}-\frac{i\hbar}{2m}\int_{-\infty}^{\infty}\big(-\Psi\frac{\partial \Psi^{*}}{\partial x}+\Psi^{*}\frac{\partial\Psi}{\partial x}\big)\mathrm{dx}\\=
   -\frac{i\hbar}{m}\int_{-\infty}^{\infty}\Psi^{*}\frac{\partial\Psi}{\partial x}\mathrm{dx}
   $$
   故：
   $$
   \lang{P}\rang=m\lang{v}\rang=\int_{-\infty}^{\infty}\Psi^{*}(-i\hbar\frac{\partial}{\partial x})\Psi\mathrm{dx}\\
   =\int_{-\infty}^{\infty}\hat{P}|\Psi|^2\mathrm{dx}
   $$

5. 厄米算符本征函数正交性证明

   设$\hat{F}\psi_{k}=\lambda_{k}\psi_{k},\hat{F}\psi_{l}=\lambda_{l}\psi_{l}$，并且$l\neq k$时，$\lambda_{l}\neq\lambda_{k}$

   根据厄米算符的本征值是实数，有：
   $$
   (\hat{F}\psi_{k})^{*}=\lambda_{k}\psi_{k}^{*}
   $$
   用$\psi_{l}$右乘上式并对全域积分有：
   $$
   \int(\hat{F}\psi_{k})^{*}\psi_{l}\mathrm{d\tau}=\int\lambda_{k}\psi_{k}^{*}\psi_{l}\mathrm{d\tau}
   $$
   用$\psi_{k}^{*}$左乘并对全域积分有：
   $$
   \int\psi_{k}^{*}(\hat{F}\psi_{l})\mathrm{d\tau}=\int\psi_{k}^{*}\lambda_{l}\psi_{l}\mathrm{d\tau}
   $$
   由厄米算符定义：
   $$
   \int\psi_{k}^{*}(\hat{F}\psi_{l})\mathrm{d\tau}=\int(\hat{F}\psi_{k})^{*}\psi_{l}\mathrm{d\tau}
   $$
   即：
   $$
   \int\lambda_{k}\psi_{k}^{*}\psi_{l}\mathrm{d\tau}=\int\psi_{k}^{*}\lambda_{l}\psi_{l}\mathrm{d\tau}
   $$
   故：
   $$
   \int\psi_{k}^{*}\psi_{l}\mathrm{d\tau}=0
   $$

## 附录三

<a id="Appendix_3">附录三锚点</a>

1. 动量与位置坐标对易关系证明

   1. $[x,\hat{p}_{x}]=i\hbar$
      $$
      \begin{aligned}
      {[x,\hat{p_{x}}]}\psi&=x\hat{p_{x}}\psi-\hat{p_{x}}x\psi\\
      &=-xi\hbar\frac{\partial}{\partial x}\psi+i\hbar\frac{\partial}{\partial x}(x\psi)\\
      &=i\hbar\psi
      \end{aligned}
      $$

   2. $[x,\hat{p_{y}}]=0$
      $$
      \begin{aligned}
      {[x,\hat{p_{y}}]}\psi&=x\hat{p_{y}}\psi-\hat{p_{y}}x\psi\\
      &=-xi\hbar\frac{\partial}{\partial y}\psi+i\hbar\frac{\partial}{\partial y}(x\psi)\\
      &=0
      \end{aligned}
      $$

2. 与位置、动量有关的算符对易关系
   $$
   \begin{aligned}
   {[\vec{p},F]}&=[\hat{p_{x}}\vec{i}+\hat{p_{y}}\vec{j}+\hat{p_{z}}\vec{k},F]\\
   &=-i\hbar\frac{\partial}{\partial x}F\vec{i}-i\hbar\frac{\partial}{\partial y}F\vec{j}-i\hbar\frac{\partial}{\partial z}F\vec{k}\\
   &=-i\hbar\nabla F
   \end{aligned}
   $$

   $$
   [\vec{p},\frac{1}{r}]=-i\hbar\nabla\frac{1}{r}=i\hbar\frac{\vec{r}}{r^3}
   $$

   $$
   \begin{aligned}
   {[\vec{r},p^2]}&=[\vec{r},p_{x}^2]+[\vec{r},p_{y}^2]+[\vec{r},p_{z}^2]\\
   &=[x,p_{x}^2]\vec{i}+[y,p_{y}^2]\vec{j}+[z,p_{z}^2]\vec{k}\\
   &=[p_{x}[x,p_{x}]+[x,p_{x}]p_{x}]\vec{i}+[p_{y}[y.p_{y}]+[y,p_{y}]p_{y}]\vec{j}+[p_{z}[z.p_{z}]+[z,p_{z}]p_{z}]\vec{k}\\
   &=2i\hbar\vec{p}
   
   \end{aligned}
   $$

   $$
   [\vec{r}\cdot\vec{p},p^2]=\vec{r}[\vec{p},p^2]+[\vec{r},p^2]\vec{p}=[\vec{r},p^2]\vec{p}=2i\hbar\vec{p}\cdot\vec{p}=2i\hbar p^2
   $$


## 附录四

<a id="Appendix_4">附录四锚点</a>

1. 埃伦费斯特定理的证明
   $$
   \frac{\mathrm{d}}{\mathrm{dt}}\lang A\rang=\frac{1}{i\hbar}[A,H]+\lang\frac{\partial A}{\partial t}\rang
   $$

   $$
   \lang A\rang=\int\psi^{*}A\psi\mathrm{d\tau}
   $$

   $$
   i\hbar\frac{\partial }{\partial t}\psi=\hat{H}\psi\\\\
   -i\hbar\frac{\partial }{\partial t}\psi^{*}=\psi^{*}\hat{H}
   $$

   $$
   \begin{aligned}
   \frac{\mathrm{d}}{\mathrm{dt}}\lang A\rang&=\int\frac{\partial}{\partial t}(\psi^{*}A\psi)\mathrm{d\tau}\\\\
   &=\int(\frac{\partial\psi^{*}}{\partial t}A\psi+\psi^{*}\frac{\partial A}{\partial t}\psi+\psi^{*}A\frac{\partial\psi}{\partial t})\mathrm{d\tau}\\\\
   &=-\frac{1}{i\hbar}\int(\psi^{*}HA\psi-\psi^{*}AH\psi)\mathrm{d\tau}+\int \psi^{*}\frac{\partial A}{\partial t}\psi\mathrm{d\tau}\\\\
   &=\frac{1}{i\hbar}\int\psi^{*}[A,H]\psi\mathrm{d\tau}+\lang \frac{\partial A}{\partial t}\rang\\\\
   &=\frac{1}{i\hbar}\lang[A,H]\rang+\lang\frac{\partial A}{\partial t}\rang
   \end{aligned}
   $$

2. 位力定理证明

   利用埃伦费斯特定理证明如下
   $$
   \begin{aligned}
   \frac{\mathrm{d}}{\mathrm{dt}}\lang\vec{r}\cdot\vec{p}\rang&=\frac{1}{i\hbar}\lang[\vec{r}\cdot\vec{p},H]\rang\\\\
   [\vec{r}\cdot\vec{p},\frac{p^2}{2m}+V]&=[\vec{r}\cdot\vec{p},\frac{p^2}{2m}]+[\vec{r}\cdot\vec{p},V]\\\\
   &=\frac{1}{2m}[\vec{r},p^2]\cdot\vec{p}+[\vec{r}\cdot\vec{p},V]\\\\
   &=\frac{1}{2m}2i\hbar p^2-i\hbar\vec{r}\cdot\nabla V\\\\
   \Rightarrow\frac{\mathrm{d}}{\mathrm{dt}}\lang\vec{r}\cdot\vec{p}\rang&=\frac{1}{m}\lang p^2\rang-\lang\vec{r}\cdot\nabla V\rang
   \end{aligned}
   $$
   定态条件下$\frac{\mathrm{d}}{\mathrm{dt}}\lang\vec{r}\cdot\vec{p}\rang=0$，因此
   $$
   \frac{1}{m}\lang p^2\rang=\lang\vec{r}\cdot\nabla V\rang\Leftrightarrow2\lang T\rang=\lang\vec{r}\cdot\nabla V\rang
   $$

3. 赫尔曼-费曼定理证明

   
