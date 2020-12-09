# 计算机科学概论

# Chapter 1 the big picture
Abstraction 抽象					Computing System 计算系统
Computer hardware 计算机硬件 		Computer software计算机软件

Central Processing Unit中央处理器 
Memory 存储器 			Main Memory 主存/内存 	Secondary/Auxiliary memory辅助存储器
Disk drive磁盘驱动器  	Magnetic Disk磁盘	Hard disk硬[磁]盘	Floppy disk软[磁]盘
Peripheral device外围设备 	Terminal 终端	Keyboards 键盘		Monitors显示器 
magnetic tape drives 磁带机   Card reader 卡片阅读器 	Punched card 穿孔卡	Line printer行打印机

Circuit boards电路板 			chips 芯片		Microchips 微芯片		Wires 导线
Integrated Circuits (ICs) 集成电路			Transistors晶体管		Vacuum tubes 真空管
Magnetic cores 磁芯	  		Magnetic Drum 磁鼓				
Large-scale Integration (LSI) 大规模集成 	Very Large-scale Integration(VLSI) 超大规模集成

Representation 表示		GUI (Graphic User Interface) 图形用户界面

Microcomputer 微型计算机	Personal Computer（PC）个人计算机	Compatible machines 兼容机
Workstations 工作站		File Server 文件服务器
RISC (Reduced Instruction Set Computer) 精简指令集计算机 
CISC (Complex Instruction Set Computer) 复杂指令集计算机
Parallel computing 并行计算		Parallel architecture 并行体系结构
SIMD (Single-Instruction Multiple-Data-stream) 单指令流多数据流)
MIMD (Multiple-Instruction Multiple-Data-stream) 多指令流多数据流
Embedded system 嵌入式系统

Operating System (OS) 操作系统 	Time sharing 分时		Time slice 时间片

Utility program 实用程序	Spreadsheets 电子表单	  Word processors 字处理程序   
Database management systems 数据库管理系统

BASIC（Beginner’s All-Purpose Symbolic Instruction Code）初学者多功能符号指令代码

Turing machine 图灵机
 

- Chapter 2 Binary Value and Number Systems
binary digit 二进制数字
positional notation 位置记数法 	place value 位值
base 基数 
Base 10, Decimal  十进制 
Base 2, Binary  二进制 		Base 8, Octal, 八进制 		Base 16, Hexadecimal  十六进制

number 数值，数 integer  整数 natural number  自然数 negative number 负数 rational number  有理数

bit (b小写) 位,比特   Byte (b大写)  字节 	word 字  word length字长
KB/MB/GB	（Kilobyte/Megabyte/Gigabyte）千字节/兆字节,百万字节/十亿字节

- Chapter 3 Data Representation
Analog data 模拟数据    Digital data 数字数据  
Digitize 数字化 Pulse Code Modulation (PCM) 脉冲编码调制 
Multimedia 多媒体 		 Bandwidth 带宽
Compression ratio 压缩比/率			Data compression 数据压缩
Compression 压缩  decompression 解压缩
Lossless compression 无损压缩 		Lossy compressions有损压缩 

numeric data 数值数据 		Radix point小数点 		Overflow 溢出
Signed-magnitude representation 符号数值表示法  		Complement 补码 	
floating-point 浮点 			Exponent 指数			Mantissa尾数

Text 文本 Character set字符集  
ASCII (American Standard Code for Information Interchange) 美国标准信息交换代码
Unicode  统一码/万国码/单一码

Encoding 编码  decoding 解码 
Keyword encoding  Run-length encoding 行程编码 Huffman encoding 哈夫曼编码 

Audio 音频 Sound wave 声波 Sampling 采样 Sampling Rate采样率 Bit Rates 比特率

Picture (Image/photograph) 图像 	Graphic 图形 
Resolution分辨率/解像度 	PIXELS (PICTure Element)像素  Color Depth 颜色的深度 TrueColor 真彩色 
Raster-graphics/bitmaps 光栅图/位图  Vector graphics 矢量图/向量图

Video视频		Codec编解码器 = Compressor编码器 / DECompressor 解码器
Redundancy冗余 	Temporal compression 时间压缩 	Spatial compression 空间压缩
 

The Hardware Layer
Chapter 4 Gates and Circuits
Transistor 三极管/晶体管/半导体 		Gate 门 	
Semiconductor 半导体 				Conductor 导体 				Insulator 绝缘体

Circuit电路，门电路					Integrated circuit集成电路
Combinational circuit 组合[逻辑]电路		Sequential circuit 时序[逻辑]电路

Adder加法器		Full Adder 全加器		Half Adder半加器 			Multiplexer 多路选择器
S-R latch S-R锁存器

Boolean algebra布尔代数				Logic Diagram逻辑图			Truth Table真值表
Circuit Equivalence 等值电路

Chapter 5 Computing Components
Computer Systems Organization 计算机系统组成/计算机组成原理 

Von Neumann Architecture 冯·诺依曼体系结构
Processor/CPU	处理器			Control Unit控制单元		Arithmetic/Logic Unit	算术/逻辑单元
Primary Memory	主存		Secondary Memory	 辅存	Input/Output	输入/输出	bus 总线

Register 寄存器				op code 操作码			Operand操作数
Instruction cycle or processing cycle指令周期	
Fetch the next instruction取指令		
Decode the instruction	翻译指令	
Get data if needed	必要时从内存取数据
Execute the instruction	执行指令

Cell	单元					Physical Address 物理地址
RAM = Random Access Memory 随机访问存储器			ROM = Read Only Memory 只读存储器
Sequence access顺序访问		direct access 直接访问
Platter盘片					Capacity容量

Synchronous同步				Pipelining流水线
 

The Programming layer
Chapter 6
Algorithm 算法 				Algorithmic Thinking 算法思维
Control structure 控制结构	Data abstraction数据抽象		Procedure abstraction过程抽象

Program程序		Programming language 编程语言
Structured Programming 结构化程序设计	 	Object-Oriented Design 面向对象设计
Top-down approach自顶向下方法				Bottom-up approach 自底向上方法 			

Abstraction class 抽象类		Class 抽象类
Information hiding 信息隐蔽		Encapsulation 封装		Inheritance 继承		Polymorphism 多态

Desk Checking 桌面检查 	Inspection代码审查	Walk through代码走查		Review技术评审

Module 模块		Semantic 语义		Syntax句法		Sorting 分类		Sort Key分类键

Chapter 7
Machine language 机器语言		Assembly language 汇编语言 		
Assembler 汇编程序	Editor 编辑程序	  Loader 加载程序   Language translators 语言翻译程序
Comment 注释

Test plan 测试计划  		Test cases 测试用例
Code-coverage(clear-box) testing 代码覆盖(白盒)测试
Data-coverage(black-box) testing 数据覆盖(黑盒) 测试

Chapter 8
Compiler 编译器		Interpreters 解释器/程序
Linker 链接程序 	 

Parameter 参数		Parameter list 参数表	
Reference Parameter  引用参数		value parameter值参数		

Object 对象			Object class 对象类		case 用例
Encapsulation 封装		Inheritance 继承			Polymorphism 多态

Imperative or procedural model 命令型/过程型	Functional model 函数式语言
Logic Model 逻辑型 	Object-oriented Model 面向对象型

Boolean expression 布尔表达式
assertion 断言		Reserved word 保留字		Recursion 递归
variable 变量			data type 数据类型		strong typing 强类型
assignment statements 赋值语句	conditional statements 条件语句	looping statements 循环语句
subprogram 子程序		procedure 过程		function 函数

Chapter 9 (Not Required)
 

The Operating System Layer
Chapter 10
Operating System (OS) 操作系统 

Process 进程		PCB (Process Control Block)进程控制块	Process Management 进程管理

CPU Scheduling  CPU调度 			First-Come, First-Served (FCFS) 先来先服务
Shortest Job Next (SJN) 最短作业/进程优先 	Round Robin 轮转/循环调度
Turnaround Time周转时间		Average Turnaround Time 平均周转时间 

Memory Management 内存管理		Address Binding 地址绑定
Single Contiguous 单一连续分配	
Partition Approach 分区 	Fixed Partition 固定分区分配	Dynamic Partition 动态分区分配

Physical Address 物理地址(绝对地址) 		Logical Address 逻辑地址(相对地址)

Paging分页	Frames 块	Fixed-Pages 固定页面 	Pmt (Page Map Table)页表
First Fit 首次适应算法	Best Fit 最佳适应算法	Worst Fit 最坏适应算法 

Multiprogramming 多道程序设计		Batch Processing批处理	
Timesharing分时					Real-Time System实时	

Chapter 11
Directory 目录		Directory tree目录树	Root directory 根目录
Working directory  工作目录

File 文件			File type 文件类型		File extension 文件扩展名
Path 路径		Absolute path 绝对路径		relative path 相对路径
Binary file 二进制文件
Direct file access直接文件系统访问		Sequential file access顺序文件访问

Disk scheduling 磁盘调度
Shortest-Seek-Time-First (SSTF) 最短寻道时间优先		SCAN 扫描调度
 
The Applications Layer ( not required)  
Chapter 12
Chapter 13
Chapter 14
 

The Communication Layer
Chapter 15 
Networking 联网 		Client/Server (C/S) 客户/服务器		Browser/Server (B/S) 浏览器/服务器
Local-area network (LAN) 局域网 		Wide-area network (WAN) 广域网
Network topology 网络拓扑结构 		Ring/Star/Bus topology令牌环/星形/总线拓扑结构
Ethernet 以太网  	Internet 因特网  	internet 互连网 	
Broadband 宽带	Gateway 网关		Router路由器	 	Repeater 中继器 Packet switching 包交换
Internet Service Provider（ISP）因特网服务提供商
Modem (from modulator-demodulator) 调制解调器		 Cable Modem有线调制解调器
DSL (Digital Subscriber Line)数字用户线  ADSL(Asymmetric Digital Subscriber Line)非对称数字用户线
Download 下载		 Upload 上传

Protocol 协议
TCP/IP (Transmission Control Protocol /Internet Protocol) 传输控制协议/网际协议
ICMP (Internet Control Message Protocol) 网间控制报文协议
UDP (User Datagram Protocol) 用户数据报协议 		FTP (File Transfer Protocol) 文件传输协议
Telnet远程登录		port 端口		

SMTP (Simple Mail Transfer Protocol) 简单邮件传送协议
IMAP (Internet Message Access Protocol Internet) Internet消息访问协议/交互邮件访问协议
MIME(Multipurpose Internet Mail Extensions) 多用途网络邮件扩展

HTTP (Hyper Text Transfer Protocol) 超文本传输协议
HTML (Hyper Text Make-up Languages) 超文本标记语言
HTTPS (Hyper Text Transfer Protocol Secure安全超文本传输协议

Firewall 防火墙	
Hostname	主机名	IP Address	IP地址		DNS(Domain name system) 域名服务器

Chapter 16
World Wide Web (WWW, 3W) 万维网		URL (Uniform Resource Locator) 统一资源定位符
Search engine 搜索引擎		Instant messaging 即时通信		Metalanguage 元语言
Web log 	Web日志		Tag 标签		Link 链接	Hyperlink 超链接		Attribute 属性
cookies存储在本地计算机上的用户访问网络的一段文本信息，含有用户的浏览偏好等信息记录

XML (Extensible Markup Language) 可扩展标记语言	XML(eXtensible Stylesheet Language) 可扩展样式表语言
DTD（Document Type Definition）文档类型定义
 
In Conclusion
Chapter 17
Limitations of Computing 计算的限制
Polynomial 多项式的 Exponential 指数的  Factorial 阶乘的
Class P problems  P类问题 		Class NP problems  NP类问题
Big-O notation complexity 大O时间复杂度度量
Turing machine 图灵机
Halting problem 停机问题  unsolvable problem 不可解问题
