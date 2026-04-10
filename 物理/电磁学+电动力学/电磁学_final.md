## 第一章：静电场
1. 库仑定理：$F=1 /()4 pi  epsilon_0) frac(q_1q_2)(r^2) vec(r_(1, 2))$，其中 $arrow(r_{1, 2)}$ 为两个粒子的单位矢量
2. 在小球内或是巨大物体产生电场中的粒子受到球的合力为零，万有引力同理。详见[[费曼物理学讲义学习]]里第十三章的 3、4。
3. 电力叠加原理：，或 $F=int dF=\frac{q_0}pi epsilon_0integral (arrow(r))/(r^2)dq$
4. 库仑定理的成立条件：**静止**，或者说只有静止点电荷（施力者）对运动或者静止的电荷（受力者）适用，一旦施力者运动便不在适用，详见[[费曼物理学讲义学习]]十五章：狭义相对论。
5. 除此外，其作用力与速度有关，展示了一种推迟效应，也与狭义相对论有关。
6. 库仑定律的适用条件在其他教材中的真空环境实际并不需要。
7. 电荷的性质：电荷守恒。电荷是粒子或是物质的性质而非独立的物质，不存在不吸附于任何粒子或是物质的电荷。电荷有量子性，其是稳定的，无相对论原理，不会发生衰变。
8. 量子场论（Quantum Field Theory, QFT），自然界的每种基本粒子，都对应一种场（如电子场、光子场、希格斯场等）。粒子不是独立存在的“小球”，而是场在某处的“激发”或“扰动”。例如，光子是电磁场的激发态，电子是电子场的激发态。
9. 关于势与场可以参照[[费曼物理学讲义学习]]的十四章
10. **电场（矢量）**：$E=(F)/(q)=(F)/(q_0)=(1)/(4pi epsilon_0)(q)/(r^2)arrow(r)$，同理，$arrow(r)$ 是单位矢量。其方向与正电荷所受方向一致。同样存在**电场叠加原理**，：$E=Sigma_i F_i=(1)/(4pi epsilon_0)Sigma_i(q_i)/(r^2)arrow(r_i)$，或 $E=integral dE=(1)/(4pi epsilon_0)integral (arrow(r))/(r^2)dq$，即是说电场是单位电荷产生的力。
11. **电偶极子**：等量异号的一堆带电体系。其中定义其电矩 $arrow(p)=qarrow(l)$,，其中在远处 $r>>l$ 的场强与 $r^3$ 正比，$E$ 与 $arrow(p)$ 相关。
    于延长线上 $E=(1)/(4piepsilon_{0)} (2ql)/(r^3)$
    于中垂面上：$E=(1)/(4piepsilon_{0)} (ql)/(r^3)$
12. 高斯定理前置：源是喷发流体的地方，汇是宣泄流体的地方。首尾相接则称为有漩涡。
13. **高斯定理**：通过任意闭合曲面 S 的电通量 $\Phi_E=integral arrow(E)dot darrow(S)=(1)/(epsilon_0)Sigma q$
14. 对于高斯定理，我们常**这样使用**：对于球对称的电荷（如点电荷），我们选择构造一个球面；对于无限长的直导线，我们选择一个同轴圆柱面。对于无限大的带电平面，我们选择垂直的柱面。
15. 例如这样一个题：一个无限大的带电平面，其面密度为 $sigma$，求其在任意一点的场强。
	首先我们构造一个一圆柱体，则在这个圆柱体上通过的电通量可分为三部分：侧面和上下两面。侧面为 0 不必考虑，上下两面可按照公式看作 $2ES$，则我们按照公式得到 $\Phi=2ES=(sigma S)/epsilon_0$,，由这个等式我们可以得到：$E=(sigma)/(2epsilon_0)$。我们发现其场强与所处的位置无关，与其离面的距离无关，任意一处的 E 均为此值。
17. 环路定理：静电场力对十天电荷所做的功与路径无关。
18. 球面度 (sr)：由弧度 rad = 弧长/半径，则定义球面度=面积/半径^2
19. **电势差**（标量）：静电场中单位正电荷从 P 电沿着任意路径移动到 Q 点时，静电力所做的功，即是 $U_{PQ}=\frac{W_{PQ}}{q_{0}}=integral ^Q_{P}E dot dl$，即是说势是单位电荷在电场中的电势差，也即是电场对其做的功。我们定义以无穷远处的电势为 0，则任意一点 P 的电势为 $U_{p}=U_{P}-U_{infty}=integral^infty_{P}E dot dl$
20. 同样，电势可定义为：$U_{P}=integral ^{infty} _{r_{p}}Edr= (q)/(4pi epsilon_{0)}integral^{infty} _{r_{p}} (dr)/(r^2)=(q)/(4pi epsilon_{0)r_{P}}$
21. 电势叠加原理：$U_{P}=(1)/(4pi epsilon_{0)}Sigma_{i} \frac{q_{i}}{r_{Pi}}$, 或者 $U_{P}=(1)/(4pi epsilon_{0)}integral (dq)/(r_{P)}$ （注意，此为标量叠加，电场为矢量叠加） 
22. 对于电势的求法，有一例题：
	试求均匀带电球壳产生的静电场中电势的分布，已知球壳带电总量为 Q，半径为 R.
	*方法一（电势定义）*：$r>R$ 时，$E=(4)/(4pi epsilon_0r^2)$, $r<R$ 时 $E＝0$
	对于球壳外的电势，
	由定义，$U_P=integral ^infty_PE dot dl=integral ^infty_rEdr=(Q)/(4piepsilon_0)integral^infty_r(dr)/(r^2)=(Q)/(4pi epsilon_0r)$
	对于球壳内的电势，由于其内外场强分布不同，需要分两段积分。
	$U_P=integral^R_rEdr+integral^infty_REdr=0+(Q)/(4pi epsilon_0)integral^infty_R(dr)/(r^2)=(Q)/(4piepsilon_0)$
	*方法二*（电势叠加原理）：根据均匀带电球壳电荷分布的对称性，取球心 O 为坐标原点，以外部所求的 P 点，OP＝r 为轴，把球面分割成许多环状窄带。窄带每部分和 P 点的距离均为 x，环带上各部分和 O 点的连线与 OP 的夹角均为 $theta$, 环带的角宽度为 dθ，宽度则为 Rdθ。周长为 $2pi Rsin theta$, $S=2pi Rsin theta dot Rdtheta$ 环带上的电量 $dq=sigmadot 2pi Rdtheta$, $sigma=Q/4pi R^2$，为球壳的面电荷密度，则由电势叠加原理可得一个环带在 P 处产生的静电荷场在 P 点的电势为 $dU=(d)/(4pi epsilon_0x)=(sigma dot2pi Rsin theta dot Rdtheta)/(4pi epsilon_0 x)$。但是由于θ是未知量，我们需要由 R、r 和 x 的关系将其消除。由此我们想到了余弦定理：$x^2=R^2-2Rrcos theta$ 。此时我们对其全微分，得到：$2xdx= 2Rrsin theta dtheta$ （此处补充一下全微分的知识，全微分没有统一的自变量，使用全微分只是寻找 x、R、r、θ之间微小变化量的关系，即是说对右边求导需要类似隐函数求导一样需要每个变量独立出来，则其全过程应该是 $2xdx= 2RdR+2rdr-2Rcostheta dr+\dots +2Rrsin theta$，但是由于其为恒定量 dR＝dr＝dx＝0，此处直接忽略）。将上式代入 dU，则由电势叠加原理，将所有环场微分（上下限为这个环在球上的位置到 P 点的距离 x），则有以下式子：当 P 在球外时 $U_P=integral dU_P=(sigma dot 2pi R)/(4pi epsilon_0r)integral ^{r+R}_{r-R}dx=(sigma dot 2pi R dot 2R)/(4pi epsilon_0r)=(Q)/(4pi epsilon_0r),\ r>R$，当 P 在球内时，上下限变化，总式子不变，$U_P=integral dU_p=(sigma dot 2pi R)/(4pi epsilon_0r)integral^{R+r}_{R-r}dx=(Q)/(4pi epsilon_0R)r<R$。
23. **常见的带点导体在某点的电场强度**：
	- 无限长导线：$E=(lambda)/(2pi epsilon_{0)r}$
	- 无限大平面：$E=(sigma)/(2epsilon_{0)}$
	- 带电球壳/体：$E=(Q)/(4pi epsilon_{0)R^2}$

24. 静电场的能量做功：
	1. 移动电荷需要功为 $W=arrow(Q)arrow(V)(arrow(r))$
	2. 点电荷分布的能量：$W=(1)/(2)Sigma^n_{i=1}q_{i}V(r_{i})$
	3. 对于连续电荷分布的能量：$W= (1)/(2 )integral V dr=\frac{varepsilon_{0}}{2}integral E^{2}dr$
	4. 
## 第二章：静电场中的导体和电介质
1. **静电感应的性质**： 当一个导体放在一个静电场中时，其内部的电场强度处处为零，且其内部与表面处处电势相等。
2. 静电平衡导体外附近场强大小与其面电荷密度成正比。
3. **导体空腔**：导体为一个封闭的金属壳时，其将空间分割为壳内和壳外。
	- 其内部**无带电体**时，一切性质同上。
	- 其外部有带电体完全不影响结论，由于电场其无法穿透导体，其对内部不会造成任何影响，则称之为静电屏蔽。
	- **范德格拉夫起电机**：通常来说，但是利用静电平衡。可以正电荷从低电势传向高电势。原理：例如给一个金属球壳充电，当它的电荷足够多的时候将会排斥外部的电荷，这时从球壳内部给它输电，将会很轻松。
	- 其内部**有带电体**的时候：由于静电平衡时，其内表面带点和内部电荷的代数和为零，空腔内各点的场强分布由空腔内电荷和内表面的电荷分布唯一地确定。
4. 静电场边值问题的唯一性定理：前置知识
	-   $nabla$ 是矢量微分算子，用来表示每个方向的微分结果的矢量。其乘上一个场即是此场的散度
	- $nabla dot E= (q)/(epsilon_{0)}$，散度，表示此处有无源或汇。
	- $nabla times E=0$ ，旋度，它衡量的是电场在空间中的**旋转程度**，结果为 0, 即是没有漩涡，为保守场。
	- 当对 U 求 $nabla$ 算子的时候，其结果即是-E，则 $nabla ^2 U= -(rho)/(epsilon_{0)}$。称之为泊松方程。
	- 边界条件：已知导体中各导体的形状、大小、位置和电量，求场强分布。
	- 而结果是：边界条件可以将静电场的。
5. **电容**：$C=(Q)/(U)=4piepsilon_{0}R$ （孤立导体电容器），$C=\frac{epsilon_{0}S}{d}$ （平行板电容器）。$C=\frac{4pi epsilon_{0}R_{A}R_{B}}{R_{B}-R_{A}}$ （同心球电容器），$C=\frac{2pi epsilon_{0}L}{ln{\frac{R_{B}}{R_{A}}}}$ （同轴圆柱）$C=\frac{pi epsilon_{0}}{ln{(d)/(r)}}$ （无限长平行导线，距离 d, 半径r）
6. 电容的串并联：串联时 $(1)/(C)=Sigma {(1)/(C_{i)} }$，并联时 $C=Sigma C_{i}$
7. 极化：当一个电介质（即绝缘体），不存在宏观上自由移动的电荷，处于静电场时会随之产生远弱于导体的电荷分布并产生附加电场。
8. 极化原理：从远处任何正电荷和负电荷之和可被等效替代到一点，分别有正负电荷的“重心”，则任何分子其可被看作一个电偶极子。自然存在一个 $arrow(p)=q\vec {l}$
	- $p = 0$ 的，称之为无极分子，反之称之为有极分子。
	- 对于无极分子，其正负电荷受到相反的作用力，则“重心”被拉开，则产生宏观上的电荷分布，称之为“位移极化”或“电子位移极化”。
	- 对于有极分子。由于其固有的电子极矩不为零，但是由于分子的无规则热运动。导致 p 取向随机，宏观上互相抵消。但是由于电场的存在其大致取向沿电场方向排列，称之为“取向极化”。
9. 极化强度矢量：极化的强度定量描述，$\vec P=(1)/(Delta V)Sigma_{in Delta V}\vec p=σ_p$，其中 $σ_p$ 为表面极化电荷密度。
10. **电介质中的静电场与高斯定理**：
	-   引入**电位移矢量** $arrow(D) = epsilon_0 arrow(E) + arrow(P)$。对于各向同性线性电介质，有 $arrow(P) = chi_e epsilon_0 arrow(E)$，其中 $chi_e$ 为电极化率。定义相对介电常数 $epsilon_r = 1 + chi_e$，则 $arrow(D) = epsilon_0 epsilon_r arrow(E) = epsilon arrow(E)$。
	-   **有介质时的高斯定理**：$integral.cont_S arrow(D) dot darrow(S) = Sigma Q_{0}$，其中 $Q_{0}$ 为高斯面 $S$ 内包围的**自由电荷**的代数和。该形式避免了直接处理复杂的束缚电荷。
11.  **电容器的能量与静电场的能量**：
	-   电容器储存的静电能：$W_e = (1)/(2)CU^2 = (1)/(2)QU = (Q^2)/(2C)$。
	-   静电能储存在电场中。对于任意电场分布，静电场的能量密度为：$w_e = (1)/(2) arrow(D) dot arrow(E)$
	-   整个电场的总能量：$W_e = integral.integral.integral_V w_e dV = integral.integral.integral_V (1)/(2) arrow(D) dot arrow(E) dV$，积分遍及整个电场空间。
## 第四章：恒定磁场
1. 毕奥-萨伐尔定律：任意一电流元对单位磁极的作用力 $dH=k (Idarrow(l)times hat(arrow(r)))/(r^2)$
2. 安培定理：在 4.1 式的基础上发展出了线代形式的比萨定理 $darrow(B)=\frac{mu_{0}}{4pi} (Idarrow(l)times hat(arrow(r)))/(r^2)$
3. 无源有旋，即满足 $integral.contarrow(B)dot d arrow(l)=integral.cont nabla dot arrow(B) \ darrow(V)=0$ 且 $integral.cont arrow(B)dot darrow(l)=mu_{0} Sigma I$ 
4. **磁矢势**：由于 $nabla ⋅ B = 0$ 且对于任何一个矢量场 `A`，它的旋度 `∇ × A` 的散度永远为零。则 $nabla dot(nabla times A)=0$，则定义 $B=nabla times A$，其中 A 为磁矢势。同时由于 A 加上任意一个函数其仍然满足上式，则同时另 A 满足 $nabla dot A=0$。则环路定理可被表述为 $nabla^2A = -mu_{0}J$, 其中 J 为电流密度（可参考[[矢量微积分基础]] 第一条）
5. **毕奥-萨伐尔定律的应用**（常见电流分布的磁场）：
	- 无限长直载流导线：$B=\frac{mu_{0}I}{2pi r}$，方向沿以导线为轴的圆周切线
	- 载流圆线圈轴线上（距圆心 $x$）：$B=\frac{mu_{0}IR^2}{2(R^2+x^2)^{3/2}}$
		- 圆心处（$x=0$）：$B=\frac{mu_{0}I}{2R}$
	- 无限长直螺线管内部（单位长度匝数 $n$）：$B=mu_{0}nI$（均匀场）
	- 载流螺绕环内部（总匝数 $N$，平均半径 $R$）：$B=\frac{mu_{0}NI}{2pi R}$
6. 磁场的高斯定理：通过任意闭合曲面 $S$ 的磁通量恒为零，$integral.cont_{S}arrow(B)dot darrow(S)=0$
	- 微分形式：$nabla dot arrow(B)=0$，表明磁场是无源场（涡旋场）
	- 物理意义：不存在磁单极子，磁感应线是闭合曲线
7. **安培环路定理的详细表述与应用条件**：
	- 积分形式：$integral.cont_{L}arrow(B)dot darrow(l)=mu_{0}Sigma I_{{内}}$，其中 $I_{{内}}$ 为环路 $L$ 所包围的电流代数和
	- 电流正负由右手定则判定：四指沿积分方向，拇指方向电流为正
	- 适用条件：恒定电流（稳恒磁场），与静电场 $integral.contarrow(E)dot darrow(l)=0$ 形成对比
	- 微分形式：$nabla times arrow(B)=mu_{0}arrow(J)$，其中 $arrow(J)$ 为电流密度

8. **安培环路定理的典型应用**（利用对称性选安培环路）：
	- 无限长圆柱导体（半径 $R$，电流 $I$ 均匀分布）：
		- 外部（$r>R$）：$B=\frac{mu_{0}I}{2pi r}$
		- 内部（$r<R$）：$B=\frac{mu_{0}Ir}{2pi R^2}$（与 $r$ 成正比）
	- 无限大均匀平面电流（面电流密度 $j_{s}$）：$B=\frac{mu_{0}j_{s}}{2}$，两侧方向相反
9. **磁矢势 $arrow(A)$ 的完整讨论**：
	- 定义：由 $nabla dot arrow(B)=0$ 和 $nabla dot (nabla times arrow(A))equiv 0$，引入 $arrow(B)=nabla times arrow(A)$
	- 规范自由度：$arrow(A)'=arrow(A)+nablachi$ 不改变 $arrow(B)$，因 $nablatimes(nablachi)=0$
	- 库仑规范：附加条件 $nabla dot arrow(A)=0$ 以唯一确定 $arrow(A)$
	- 在库仑规范下满足：$nabla^{2}arrow(A)=-mu_{0}arrow(J)$（矢量泊松方程）
	- 物理意义：$arrow(A)$ 的环量 $integral.contarrow(A)dot darrow(l)$ 等于通过以该环路为边界的曲面的磁通量

10. **磁场对电流的作用力**：
	- 安培力公式：电流元 $Idarrow(l)$ 受力 $darrow(F)=Idarrow(l)timesarrow(B)$
	- 均匀磁场中直导线（长度 $L$）：$arrow(F)=Iarrow(L)timesarrow(B)$
	- 均匀磁场中任意闭合载流线圈：合力 $arrow(F)=0$，但有力矩 $arrow(\tau)=arrow(m)timesarrow(B)$
		- 其中 $arrow(m)=Iarrow(S)$ 为线圈磁矩，$arrow(S)$ 为面积矢量（方向按右手定则）
11. **磁场对运动电荷的作用**（洛伦兹力）：
	- $arrow(F)=qarrow(v)timesarrow(B)$，力垂直于速度，不做功
	- 均匀磁场中带电粒子的运动：
		- $v\perp B$：匀速圆周运动，半径 $R=(mv)/(qB)$，周期 $T=(2pi m)/(qB)$（与 $v$ 无关）
		- $v$ 与 $B$ 成 $theta$ 角：螺旋运动，螺距 $h=v_{\parallel}T=(2pi m vcostheta)/(qB)$
12. **磁偶极子**：
	- 磁偶极矩：$arrow(m)=Iarrow(S)$
	- 在均匀磁场中：势能 $W=-arrow(m)dotarrow(B)$，力矩 $arrow(\tau)=arrow(m)timesarrow(B)$
	- 在远处产生的磁场（类比电偶极子）：
		- 轴线上：$Bapprox\frac{mu_{0}}{4pi}(2m)/(r^{3)}$
		- 中垂面上：$Bapprox\frac{mu_{0}}{4pi}(m)/(r^{3)}$
13. **霍尔效应**：
	- 现象：载流导体在磁场中产生横向电势差
	- 霍尔电势差：$U_{H}=(IB)/(nqd)$，其中 $n$ 为载流子浓度，$q$ 为载流子电荷，$d$ 为厚度
	- 霍尔系数：$R_{H}=(1)/(nq)$，符号判断载流子类型
14. **恒定磁场的边界条件**（两磁介质界面，无自由面电流时）：
	- 法向分量连续：$B_{1n}=B_{2n}$
	- 切向分量连续：$H_{1t}=H_{2t}$ 或 $\frac{B_{1t}}{mu_{1}}=\frac{B_{2t}}{mu_{2}}$
15. 磁力矩: $bold(\tau) = bold(m) times bold(B)$ 
## 第五章：磁介质
1. **磁化强度矢量**: 单位体积内分子磁矩的矢量和 $arrow(M)= (1)/(Delta  V) Sigma arrow(p_{m)}$
2. 由于在加上磁场对其磁化后，其存在一个宏观上的磁化电流 $arrow(I_{M)}$，从而产生了磁化磁场。此时的 $arrow(B)=arrow(B_{0)}+arrow(B^{')}$ 
3. $arrow(I_{M)}$ 与 $arrow(M)$ 的关系：$integral.cont arrow(M) dot darrow(l)=Sigma arrow(I_{M)}$ ，也可表述为 $nabla times arrow(M)=arrow(j_{m)}$，其中的 $arrow(j_{m)}$ 为磁化电密度。
4. $arrow(M)$ 与 $arrow(i_{m)}$ (磁化电流面密度) 的关系：$arrow(i_{m)}=arrow(M) timesarrow(n)$ 或 $M_{i}=i_{M}$，其中 $arrow(n)$ 为磁介质表面外法向量的单位矢量，$i_{M}$ 为单位长度上的磁化电流，$M_{i}$ 为 $M$ 磁介质表面的分量。
5. $arrow(M)$ 与 $arrow(B)$ 的关系：$arrow(M)= \frac{chi_{m}}{mu_{0}mu_{r}}arrow(B)$，其中 $mu_{r}=1+chi_{m}$
6. **磁介质存在时，磁场的高斯定理和安培环路定理**：由于磁场无源有旋，其安培定理为：$integral.contarrow(B)dot darrow(l)=mu_{0}Sigma I_{0}+mu_{0}Sigma I_{M}$，由于其磁场 B 和 $I_{M}$ 相互关联，则用 $arrow(M)$ 来代替，即 $integral.cont( (arrow(B))/(mu_{0)} -arrow(M)  ) dot darrow(l)=Sigma I_{M}$，其中我们定义 $arrow(H) =(arrow(B))/(mu_{0)} -arrow(M)$，则 $integral.cont arrow(H) dot darrow(l)=Sigma I_{0}$
7. **B 与 H 的关系**（仅限线性磁质）：由 $arrow(M)=chi_{m}arrow(H)$，则 $arrow(B)=mu_{0}(arrow(H)+arrow(M))=mu_{0}mu_{r}arrow(H)=muarrow(H)$，其中 $mu=mu_{0}mu_{r}$，$mu_{r}=1+chi_{m}$ 
8. 铁磁质（强磁质）：其 $arrow(M)$ 与 $arrow(H)$ 非线性关系，5.7 的式子边不再适用。其 $arrow(M)$ 和 $arrow(B)$ 随 $arrow(H)$ 的变化存在着起始的缓慢再急剧再平稳到饱和的规律。整个变化称为起始磁化曲线。其满足 $arrow(B)=mu_{0}(arrow(H)+ arrow(M))$
## 第六章：电磁感应
1. 法拉第电磁感应定律：$varepsilon=-(d\Phi)/(dt)$
2. 动生电动势：$varepsilon=integral(arrow(v)times arrow(B))darrow(l)$（可看作洛伦兹力对电子做功形成的电动势）
3. 感生电动势：$varepsilon=arrow(E_{旋)}dot darrow(l)=-integral.integral (partialarrow(B))/(partial t)dot darrow(S)$ ，$arrow(E_{旋)}=-(partial A)/(partial t)$，$arrow(B)=nabla times arrow(A)$
4. 自感系数：$\Phi=LI$，自感电动势 $varepsilon=-L(darrow(I))/(dt)$ 
5. **楞次定律**：感应电流的方向总是使得它所产生的磁场阻碍引起感应电流的磁通量的变化。这是能量守恒定律在电磁感应中的体现。
6. **互感**：当线圈1中的电流变化时，在线圈2中产生感应电动势的现象。
	- 互感系数 $M$：$\Phi_{21} = M I_1$，$\Phi_{12} = M I_2$，且 $M_{12}=M_{21}=M$
	- 互感电动势：$varepsilon_2 = -M (dI_1)/(dt)$，$varepsilon_1 = -M (dI_2)/(dt)$
	- 两个线圈串联时的总自感：同向串联 $L = L_1 + L_2 + 2M$，反向串联 $L = L_1 + L_2 - 2M$
7. **磁场的能量**：
	- 自感线圈储存的磁能：$W_m = (1)/(2) L I^2$
	- 互感线圈系统的磁能：$W_m = (1)/(2) L_1 I_1^2 + (1)/(2) L_2 I_2^2 + M I_1 I_2$
	- 磁场的能量密度：$w_m = (1)/(2) arrow(B) dot arrow(H) = (B^2)/(2mu)$（在线性介质中）
	- 总磁能：$W_m = integral.integral.integral_V w_m dV = integral.integral.integral_V (1)/(2) arrow(B) dot arrow(H) dV$
8. **RL电路的暂态过程**：
	- 电路接通（$t=0$ 时合上开关）：
		$$ I = (varepsilon)/(R)(1 - e^{-(R)/(L)t}) $$
		- 时间常数 $\tau = L/R$，表示电流达到稳定值的63%所需时间
	- 电路断开（$t=0$ 时断开开关）：
		$$ I = I_0 e^{-(R)/(L)t} $$
		- $I_0$ 为断开前的电流
9. **涡电流（傅科电流）**：
	- 大块导体在变化磁场中产生的感应电流，呈涡旋状
	- 热效应：涡电流产生焦耳热，应用于感应加热（电磁炉）
	- 阻尼效应：导体在磁场中运动时，涡电流产生的磁场阻碍相对运动，应用于电磁阻尼（磁悬浮、仪表阻尼）
10. **电磁感应的典型应用**：
	- 发电机：机械能→电能，基于动生电动势
	- 变压器：交流电压变换，基于互感原理
	- 感应电动机：旋转磁场驱动转子
	- 电磁流量计：$U = Blv$，测导电液体流速
11. **电磁感应中的能量转换**：
	- 动生电动势：机械能→电能，洛伦兹力不做功但起传递能量作用
	- 感生电动势：变化磁场的能量→电能
	- 总满足能量守恒：$W_{{外}} = Delta W_m + Q$（外做功=磁能增加+焦耳热）
12. **趋肤效应**：高频交流电在导体中分布不均匀，趋于表面流动
	- 趋肤深度 $delta = sqrt{(2)/(omega mu sigma)}$，其中 $omega$ 为角频率，$sigma$ 为电导率
	- 频率越高，趋肤深度越小

## 第八章：麦克斯韦方程组
1.  早期感生电动势：$epsilon = - oint frac(partial vec(A),partial t) cdot d vec(l)=  -integral.cont vec(E_{旋})dot darrow(l)=- (d\Phi)/(dt)=-(d)/(dt)integral.integral arrow(B)dot darrow(S)$ .
2. 洛伦兹力：$arrow(F)=qarrow(E)+qarrow(v)times arrow(B)$.
3. 总电场的高斯定理：$integral.cont arrow(D)dot darrow(S)=q_{0}$，其中 $arrow(D)=varepsilon_{0}varepsilon_{r}arrow(E)$，E 同下，包含两个部分。
4. 总电场的安培环路定理：$integral.cont arrow(E)dot darrow(l)=-integral.integral (partialarrow(B))/(partial t)dot darrow(S)$，其中 $E=E_{势}+E_{旋}$，表明总体的电场有源有旋。
5. 关于 I 的补充知识：位移电流：电介质存在的情况下，存在极化电流 $I_{P}$，将其与变化电场之和为总位移电流密度 $J_D = (dD)/(dt) = varepsilon_{0}( (dE)/(dt) ) + (dP)/(dt)$
6. 总磁场的高斯定理：由于包含传导电流 $I_{0}$ 和磁化电流 $I_{M}$ 所产生的 $B_{1}$ 和位移电流 $I_{D}$ 所产生的 $B_{2}$ 同样无源，则 $B=B_{1}+B_{2}$ 同样满足 $integral.cont arrow(B)dot darrow(S)=0$
7. 总电磁场的安培环路定理：由于存在位移电流，则满足 $integral.cont arrow(H)dot darrow(l)=I_{0}+integral.integral (partialarrow(D))/(partial t)darrow(S)$
8. 综上，**麦克斯韦方程组的积分形式**可表述为：$$ 

{

integral.cont arrow(D)dot darrow(S) &= q_{0} ,
integral.cont arrow(E)dot darrow(l) &=-integral.integral (partialarrow(B))/(partial t)dot darrow(S) ,
integral.cont arrow(B)dot darrow(S)&=0 ,
integral.cont arrow(H)dot darrow(l) &= I_{0}+integral.integral (partialarrow(D))/(partial t)darrow(S)

}

$$ 且同时存在介质方程组 
$$

{

arrow(D) &= varepsilon_{r}varepsilon_{0}E_{0}c ,
arrow(B) &= mu_{r}mu_{0}arrow(H) ,
arrow(j_{0)} &= sigma arrow(E)

}

$$
利用矢量分析中的高斯定理和斯托克斯定理，可将麦克斯韦方程组的积分形式导出其微分形式：$$

{

nabla dot arrow(D) &= rho_{0},
nabla times arrow(E) &= - (partialarrow(B))/(partial t),
nabla dot arrow(B) &=0,
nabla times arrow(H)&= arrow(j_{0)} +(partialarrow(D))/(partial t)

}

$$
其中 $rho_{0}$ 为自由电荷的体密度，$j_{0}$ 为传导电流密度。
9. 上式仅适用于连续可微情况，遇到两个表面时，与边界条件结合即可，满足：
   $$

{

E_{1t} &= E_{2t},
H_{1t} &= H_{2t},
D_{1n} &= D_{2n},
B_{1n} &= B_{2n}

}

$$
10. 电磁波（光波）是横波。
11. 电磁场的能量密度公式：$w=(1)/(2)(arrow(D)dot arrow(E)+arrow(B)+arrow(H))$
12. 电磁场的能流密度矢量：$arrow(S)=arrow(E)times arrow(H)$
13. 电磁波的动量密度：$vec(g)=frac(1,c^2)\ vec(S)=frac(1,c^2) vec(E) times vec(H)$


# 待补充笔记
1. 关于电场边界条件，我们先假设一个无限大的带电平面，对其求高斯定理，则存在这样的一个关系 $integral.cont E dot dS = (Q)/(epsilon_{0)}$ ，此时的 $E=E_{up}-E_{down}$ ，因为 $V=integral Edot dl$，我们将这个积分的范围减缩到几乎为 0，此时的 $V_{up}=V_{down}$，但是 $E=nabla V$，意味着  $nabla V$ 具有同样的不连续性，即是说 $nabla V_{Up}-nabla V_{down}=- (1)/(epsilon_{0)} sigma hat(n)$ ，即是说，法向分量产生了跃变