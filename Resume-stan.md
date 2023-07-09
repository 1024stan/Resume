

 # &emsp;&emsp;&emsp;苏 涛 &emsp; <span style="font-size: 18px">求职意向：c++算法工程师</span> <img align = "right" src="./resource/stan.jpg/" width="120px">





**学校**：武汉理工大学&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**学历**：硕士&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**专业**：自动化&emsp;&emsp;&thinsp;

**邮箱**：sutao_stan@163.com&emsp;&emsp; **电话**：15871409930&emsp;&emsp;&emsp;**毕业时间**：2022年




## <font color= #871F78 size=3 face="微软雅黑">🎓教育经历</font>

**武汉理大学** - 控制科学与工程 - 学术型硕士 - 自动化学院                              2019年07月 - 2022年06月

- 2021年 第三届北京高校人工智能论坛暨清华大学第621期博士生论坛 获**分论坛优秀口头报告奖**
- 2020年 中国研究生数学建模竞赛 获**国家三等奖**
- 2020年 西门子杯中国智能制造挑战赛华中赛区 获**省三等奖** 
- 2020年 “兆易创新杯”第十五届中国研究生电子设计竞赛 获**省三等奖** 
- 2020年 中国“互联网+”大学生创新创业大赛武汉理工大学赛区 获**三等奖** 
- 2019年 中国研究生数学建模竞赛 获**国家三等奖** 

相关课程：随机过程、矩阵论、计算机控制系统、机器学习、数据可视化

**武汉理工大学** - 自动化专业 - 本科 - 自动化学院                                            2015年09月 - 2019年06月

- 2018年 美国大学生数学建模竞赛 获**H奖（二等奖）** 
- 2017年 "北斗杯"全国大学生科技竞赛大学组 获**优秀奖** 
- 2017年 华中地区数学建模竞赛 获**三等奖** 
- 2016年 武汉理工大学"ASM"杯智能车竞赛 获**三等奖** 

相关课程：概率论、模式识别、图像处理、智能计算。谷歌机器学习课程（自学）。

## <font color= #871F78 size=3 face="微软雅黑">🎨工作经历</font>

**新一代音乐评测引擎**                                                                                     2022年08月 - 2022年08月

- **Situation：**线上音乐评测引擎架构混乱，技术老旧，亟需升级成深度学习技术和引擎架构；
- **Task：**开发音乐评测引擎，支持多路并发，三天完成10w+条数据评测，稳定运行三天无内存泄漏无崩溃；
- **Action 1：**推动多方协商，制定引擎的输出和输出功规；
- **Action 2：**学习CMake构建工程和C++ 11的编程基础；
- **Action 3：**基于AIOE口语评测引擎架构，实现音乐评测题型独立引擎；使用onnxinfer组件(基于onnxruntime)，实现基于c++端onnx模型的推理，并对齐c++端和python端一致性；
- **Result：**代码构建发版，快速入门c++开发并实践，为业务拓展百万商机。

**新一代音乐评测引擎安卓版**                                                                          2022年09月 - 2022年10月

- **Situation：**已完成音乐评测引擎升级，有端侧业务方要集成该功能；
- **Task：**构建新一代音乐评测引擎安卓版，稳定运行，无内存泄漏无崩溃；
- **Action 1：**以xlite组件替换onnxinfer组件实现端侧onnx模型的推理；
- **Action 2：**通过交叉编译，用Android NDK在Linux上编译Android系统armV8板子的动态库引擎；
- **Action 3：**实践出xlite组件的崩溃和一致性问题，同xlite组件开发人员一起修复问题；
- **Action 4：**使用adb技术完成端侧的一致性和稳定性验证；编译64位和32位两个版本的端侧引擎；

- **Result：**构建发版，掌握交叉编译技术，填补音乐引擎端侧空白。

**口语评测引擎python封装**                                                                             2022年10月 - 2022年11月

- **Situation：**口语评测引擎内部计算逻辑复杂，改动方案后不能验证全流程效果，将c++代码封装成python可import的site-pages；
- **Task：**封装AIOE引擎10个题型的13个模块，稳定运行三天无内存泄漏无崩溃；
- **Action 1：**使用pybind11，将口语评测引擎的plug插件模块封装成python库；

- **Action 2：**对齐一致性，实现多批次运行；
- **Result：**构建发版，促进研究—开发一体化。

**Mocha-Fa朗读题升级**                                                                                     2022年12月 - 2023年03月

- **Situation：**开发朗读题升级方案，但模型较复杂，单路单数据运行耗时严重;
- **Task：**开发Mocha-Fa方案，并开发batchflow组件提升时间效率;
- **Action 1：**开发BPE分词和GPA字词发音对齐方案;
- **Action 2：**由于onnx内涉及逻辑判断的算子一致性失效，使用python对onnx文件切图，将ED模型切成四个子图，对齐在线计算下每个子图的一致性；
- **Action 3：**开发batchflow组件的batchbuild部分，实现存储push数据等、拼多inst的batch数据、计算try attention等操作，开发beamsearch功能，拉通整体流程，对齐整体ED模型的一致性；
- **Result：**完成调度逻辑、在线逻辑十分复杂的batchflow组件的开发，实现朗读题整体识别方案升级。

**中文实时背诵跟踪引擎**                                                                                     2023年04月 - 2023年06月

- **Situation：**学习机使用识别引擎+match引擎+评测引擎达成背诵业务，现技术方案升级，以中文背诵跟踪引擎替代识别+match引擎的功能；
- **Task：**与多方对齐中文试卷功规和引擎输出功规，开发中文背诵跟踪引擎；
- **Action 1：**推动多方协商,制定引擎的输出和输出功规;
- **Action 2：**基于AIOE口语评测引擎架构,实现音乐评测题型独立引擎;使用onnxinfer组件(基于onnxruntime),实现基于c++端onnx模型的推理,并对齐c++端和python端一致性;
- **Result：**构建发版,测试三天无内存泄漏,无崩溃。



**新一代音乐评测引擎**                                                                                     2022年08月 - 2022年09月

- **Situation:** 线上音乐评测引擎架构混乱,技术老旧,亟需升级成深度学习技术和引擎架构;
- **Task:** 构建新一代音乐评测引擎,支持多路并发,三天完成10w+条数据评测,稳定运行三天无内存泄漏无崩溃;
- **Action 1:** 推动多方协商,制定引擎的输出和输出功规;

- **Action 2:** 基于AIOE口语评测引擎架构,实现音乐评测题型独立引擎;使用onnxinfer组件(基于onnxruntime),实现基于c++端onnx模型的推理,并对齐c++端和python端一致性;
- **Result:** 构建发版,测试三天无内存泄漏,无崩溃。










## <font color= #871F78 size=3 face="微软雅黑">🥇校园经历</font>

**SCI论文** 

1. **Tao Su**, Ying Shi, et al. Nonlinear compensation algorithm for multidimensional temporal data: A missing value imputation for the power grid applications[J]. Knowledge-Based Systems, 2021:106743, doi: 10.1016/j.knosys.2021.106743. (**SCI、EI 收录，IF:8.067**) 
2. **Tao Su**, Ying Shi * et al. A hybrid loss balancing algorithm based on gradient equilibrium and sample loss for understanding of road scenes at basic-level [J]. Pattern Analysis and Applications. (**SCI、EI收录，IF:2.580**) 
3. Y. Sun, Y. Shi, Q. Hu, C. Xie and **Tao. Su.** DTformer: An Efficient Digital Twin Model for Loss Measurement in UHVDC Transmission Systems[J]. IEEE Transactions on Power Systems, doi: 10.1109/TPWRS.2023.3278300.(**SCI、EI收录，IF:7.326**，**毕设**)
4. Du, Jiabao, Yue, Chang, Shi, Ying, Yu, Jicheng, Sun, Fan, **Su, Tao,** Xie, Changjun. A Frequency Decomposition-Based Hybrid Forecasting Algorithm for Short-Term Reactive Power[J]. Energies, 2021: 14(20):6606, doi:10.3390/en14206606. (**SCI、EI收录，IF:3.004**) 

**EI收录论文** 

1. Y. Huang and Tao. Su, "Optimizing Fruit Fly Algorithm to Solve TSP Problem," 2017 International Conference on Computer Systems, Electronics and Control (ICCSEC), Dalian, 2017, pp. 1409-1411, doi: 10.1109/ICCSEC.2017.8446833. 

**发明专利** 

1. 一种基于梯度均衡策略的多任务实例级道路场景理解算法（实质审查中） 
2. 一种基于样本损失的多检测框损失均衡的实例级道路场景理解算法（实质审查中）

**毕设：面向物理空间全映射的高压直流输电系统数字孪生模型研究**              2021年10月 - 2022年03月

- **确定需求：**跟甲方沟通交流确定数字孪生模型的需求和应用场景，并分析了已有的系统数据和计量损耗数据；
- **建立了全映射自构建数字孪生模型：**设计重点设备参数自适应感知、拓扑特征提取和编码-解码器 序列生成三大DTformer模型核心模块； 
- **提出了数字孪生全映射自构建算法：**融合掩码规则和序列数据处理，使本项目设计的DTformer模 型能实现多重映射函数的集合学习，并经迁移步骤后，形成更准确的映射模型； 
- **实现了模型的轻量化：**从优化模型运算和知识蒸馏两个方面，对模型的运算和结构进行优化，降低 了数字孪生模型的耗时； 
- **成果：**硕士毕业论文一篇，拟发表期刊论文三篇。

**线路损耗原因补偿计算** - 组长                                                                        2019年10月 - 2020年11月 

- **数据预处理：**对61个变电站的数据进行分割，整合每一个站点的输送端有功电量、无功电量等数 据； 
- **构建修正模型：**考虑负载率和输电线物理特性因素，构建线损计算公式的修正法，实现准确的实际 线损回归计算； 
- 提出独创的多维扰动系统快速插值补全缺失值的算法，撰写SCI一区论文一篇。

**其他项目经历**

- **马自达网络舆情动态监测：**对于短文本使用TextRNN、Transformer构建情感分类模型；对于长文 本，先搭建长文本提取摘要模型，再使用基于BERT、ALNet的文本情感分类模型区分文章的褒贬意义；
- **新能源汽车运行安全风险评估预警技术及系统研发：**将Transformer应用于多维时序数据分类中；
- **基于状态监测的在运电力互感器计量性能评估技术研究：**采用SVR,LightGBM，Bi-LSTM等模型回归计算角差和比差。为提升模型的可解释性，融合专家知识领域公式，构建环境参量和电气参量扰动补偿修正电压互感器的角差和比差，并采用改进PSO算法和蚁群算法分别确定扰动影响因子；
- **主导三次项目投标过程：**独立撰写多篇应答文件获取信息表、应答文件、商务标书、技术标书等投标相关材料和文件；熟练使用电商平台在线投标软件、网站和电子钥匙等工具；
- **712所十三五规划结题软件、数据库：**负责6个小组13个软件的总体事宜，与712所交流确定软件需求，并减少甲方多余的要求，负责所有13个软件后期的收尾和108个结题文件的验收。


## <font color= #871F78 size=3 face="微软雅黑">🎊实习经历</font>

**华为技术有限公司** - 软件工程师 光产品线                                                     2021年07月 - 2021年08月

- 学习OTN光产品时间同步的原理,IEEE 1588V2协议，并使用TCL命令和NCE网管成功适配OSN 9800 和OSN 8000 I 等多台网元的拓扑时间同步； 
- 第3周就处理现网问题，根据问题反馈和设备日志，排查故障问题；依据现网和配置信息，追溯 C++源码并生成问题解决报告1份； 
- 自制热补丁，生成o文件、pat文件和pkg文件，完成设备包加载升降级，打上自制热补丁后验证 功能可使用； 
- 解决多份DTS问题单，并MR补丁代码上库一份。 

**北京算丰征途科技有限公司** - 科技文档撰写员                                              2020年12月 - 2021年06月

- 学习毫米波雷达的信号、心率识别、姿态估计和手势识别等国内外研究现状和知识； 
- 完成 16 项发明专利的设计和撰写。



## <font color= #871F78 size=3 face="微软雅黑">🏆技能/证书及其他</font>

- **研究和实践领域：** 多维数据挖掘和分析；目标检测；实例分割；命名实体识别；文本情感分类；数字信号处理。

- **技能：** python（熟练），matlab（熟练），c++ 11（掌握），gdb（掌握），Cmake（掌握），opencv（掌握），Tensorflow（掌握），Pytorch（掌握），Excel / Word / PowerPoint（熟练），Visio（熟练），Latex（掌握），Tableau（掌握），PhotoShop（掌握），SPSS（掌握）

- **证书/执照：** 计算机二级

- **语言：** 英语（CET-6）



