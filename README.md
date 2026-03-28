<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>精探巢患，智驱护网 - 铁路接触网智能防鸟系统</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#165DFF',
                        secondary: '#00D8FF',
                        dark: '#0A101F',
                        light: '#E8F3FF',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-gradient {
                background-clip: text;
                -webkit-background-clip: text;
                color: transparent;
                background-image: linear-gradient(90deg, #165DFF, #00D8FF);
            }
            .bg-gradient-tech {
                background: linear-gradient(135deg, #0A101F 0%, #101A34 100%);
            }
            .card-hover {
                transition: all 0.3s ease;
            }
            .card-hover:hover {
                transform: translateY(-5px);
                box-shadow: 0 10px 30px rgba(22, 93, 255, 0.2);
            }
            .border-glow {
                box-shadow: 0 0 15px rgba(0, 216, 255, 0.3);
            }
        }
    </style>
</head>
<body class="bg-dark text-white overflow-x-hidden">
    <!-- 导航栏 -->
    <nav class="fixed w-full top-0 z-50 bg-dark/90 backdrop-blur-md border-b border-primary/20">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center gap-2">
                <i class="fa fa-shield text-secondary text-2xl"></i>
                <span class="text-xl font-bold text-gradient">精探巢患 · 智驱护网</span>
            </div>
            <div class="hidden md:flex gap-8">
                <a href="#home" class="hover:text-secondary transition-colors">首页</a>
                <a href="#project" class="hover:text-secondary transition-colors">项目介绍</a>
                <a href="#tech" class="hover:text-secondary transition-colors">核心技术</a>
                <a href="#solution" class="hover:text-secondary transition-colors">解决方案</a>
                <a href="#specs" class="hover:text-secondary transition-colors">技术参数</a>
                <a href="#cases" class="hover:text-secondary transition-colors">应用案例</a>
                <a href="#team" class="hover:text-secondary transition-colors">团队介绍</a>
                <a href="#market" class="hover:text-secondary transition-colors">市场优势</a>
                <a href="#value" class="hover:text-secondary transition-colors">社会价值</a>
                <a href="#contact" class="hover:text-secondary transition-colors">联系我们</a>
            </div>
            <button class="md:hidden text-2xl">
                <i class="fa fa-bars"></i>
            </button>
            <!-- 移动端菜单 -->
            <div id="mobile-menu" class="hidden absolute top-full left-0 right-0 bg-dark/95 backdrop-blur-md border-b border-primary/20 py-4">
                <div class="container mx-auto px-4 flex flex-col gap-4">
                    <a href="#home" class="hover:text-secondary transition-colors py-2">首页</a>
                    <a href="#project" class="hover:text-secondary transition-colors py-2">项目介绍</a>
                    <a href="#tech" class="hover:text-secondary transition-colors py-2">核心技术</a>
                    <a href="#solution" class="hover:text-secondary transition-colors py-2">解决方案</a>
                    <a href="#specs" class="hover:text-secondary transition-colors py-2">技术参数</a>
                    <a href="#cases" class="hover:text-secondary transition-colors py-2">应用案例</a>
                    <a href="#team" class="hover:text-secondary transition-colors py-2">团队介绍</a>
                    <a href="#market" class="hover:text-secondary transition-colors py-2">市场优势</a>
                    <a href="#value" class="hover:text-secondary transition-colors py-2">社会价值</a>
                    <a href="#contact" class="hover:text-secondary transition-colors py-2">联系我们</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- 首屏 Banner -->
    <section id="home" class="min-h-screen flex items-center justify-center relative overflow-hidden pt-20">
        <div class="absolute inset-0 opacity-20">
            <div class="absolute w-[800px] h-[800px] rounded-full bg-primary/20 blur-3xl -top-96 -left-96"></div>
            <div class="absolute w-[600px] h-[600px] rounded-full bg-secondary/10 blur-3xl -bottom-96 -right-96"></div>
        </div>
        <div class="container mx-auto px-4 z-10 text-center">
            <h1 class="text-[clamp(2rem,5vw,4rem)] font-bold leading-tight mb-6">
                铁路接触网<span class="text-gradient">智能防鸟系统</span>
            </h1>
            <p class="text-xl md:text-2xl text-light/80 max-w-3xl mx-auto mb-10">
                精探巢患，智驱护网 —— 用科技创新守护铁路供电安全
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <button class="px-8 py-3 bg-primary hover:bg-primary/80 rounded-full font-semibold transition-colors">
                    了解项目详情
                </button>
                <button class="px-8 py-3 bg-transparent border border-secondary text-secondary hover:bg-secondary/10 rounded-full font-semibold transition-colors">
                    核心技术优势
                </button>
            </div>
        </div>
    </section>

    <!-- 项目介绍 -->
    <section id="project" class="py-20 bg-gradient-tech">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">项目介绍</h2>
                <div class="w-20 h-1 bg-gradient-tech mx-auto"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-10 items-center">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gradient">解决铁路鸟害世界级难题</h3>
                    <p class="text-light/80 mb-4 leading-relaxed">
                        我国铁路营业里程已突破16.2万公里，接触网作为列车“生命线”，23.7%的故障由鸟类筑巢引发，年直接经济损失超8200万元。
                    </p>
                    <p class="text-light/80 mb-4 leading-relaxed">
                        传统人工巡检效率低、安全风险大，常规驱鸟设备易失效、鸟类易适应，无法满足现代铁路安全运维需求。
                    </p>
                    <p class="text-light/80 leading-relaxed">
                        本项目聚焦行业痛点，研发<strong class="text-secondary">无源智能驱鸟+模块化监测</strong>一体化系统，实现全天候、高效率、绿色环保的鸟害防控。
                    </p>
                </div>
                <div class="bg-dark/50 p-6 rounded-2xl border border-primary/30 border-glow card-hover">
                    <div class="grid grid-cols-2 gap-6">
                        <div class="text-center">
                            <div class="text-4xl font-bold text-primary mb-2">23.7%</div>
                            <div class="text-sm text-light/70">鸟害故障占比</div>
                        </div>
                        <div class="text-center">
                            <div class="text-4xl font-bold text-primary mb-2">8200万+</div>
                            <div class="text-sm text-light/70">年经济损失</div>
                        </div>
                        <div class="text-center">
                            <div class="text-4xl font-bold text-primary mb-2">90%</div>
                            <div class="text-sm text-light/70">自动识别目标</div>
                        </div>
                        <div class="text-center">
                            <div class="text-4xl font-bold text-primary mb-2">82%</div>
                            <div class="text-sm text-light/70">鸟巢复发下降</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 核心技术 -->
    <section id="tech" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">核心技术创新</h2>
                <p class="text-light/70">拥有自主知识产权，通过国家专利认证，科技查新无同类技术</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- 技术1 -->
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20 card-hover">
                    <div class="w-14 h-14 bg-primary/20 rounded-full flex items-center justify-center mb-6">
                        <i class="fa fa-bolt text-secondary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">无源智能驱鸟机制</h3>
                    <p class="text-light/70 leading-relaxed">
                        自适应转向驱鸟刺+机械传动声学警报双重防护，鸟类自重触发，全程无需电力，接触即报警，永不失效。
                    </p>
                </div>
                <!-- 技术2 -->
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20 card-hover">
                    <div class="w-14 h-14 bg-primary/20 rounded-full flex items-center justify-center mb-6">
                        <i class="fa fa-cubes text-secondary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">模块化快拆架构</h3>
                    <p class="text-light/70 leading-relaxed">
                        全模块化设计，安装维护效率提升70%，支持局部更换，大幅降低全生命周期使用成本。
                    </p>
                </div>
                <!-- 技术3 -->
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20 card-hover">
                    <div class="w-14 h-14 bg-primary/20 rounded-full flex items-center justify-center mb-6">
                        <i class="fa fa-cloud text-secondary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">智能监测云平台</h3>
                    <p class="text-light/70 leading-relaxed">
                        实时数据采集+混合组网传输，生成鸟害热力图与预警报告，实现从被动处置到主动预判。
                    </p>
                </div>
            </div>
            <div class="mt-12 bg-dark/50 p-6 rounded-xl border border-secondary/30">
                <div class="flex items-center gap-4 mb-4">
                    <i class="fa fa-check-circle text-secondary text-xl"></i>
                    <span class="font-semibold">国家实用新型专利受理</span>
                </div>
                <div class="flex items-center gap-4 mb-4">
                    <i class="fa fa-check-circle text-secondary text-xl"></i>
                    <span class="font-semibold">科技查新：国内未见同类技术报道</span>
                </div>
                <div class="flex items-center gap-4">
                    <i class="fa fa-check-circle text-secondary text-xl"></i>
                    <span class="font-semibold">极寒/高温全环境稳定运行</span>
                </div>
            </div>
        </div>
    </section>

    <!-- 市场优势 -->
    <section id="market" class="py-20 bg-gradient-tech">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">市场与商业价值</h2>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gradient">百亿级蓝海市场</h3>
                    <p class="text-light/80 mb-4 leading-relaxed">
                        铁路接触网防鸟细分市场<strong class="text-secondary">年规模超20亿元</strong>，叠加电网、轨道交通需求，市场向百亿级进化。
                    </p>
                    <p class="text-light/80 mb-4 leading-relaxed">
                        产品定价仅为进口设备的38%，毛利率高达53%，具备极强市场竞争力。
                    </p>
                    <p class="text-light/80 leading-relaxed">
                        已完成6个铁路局、2000公里线路实地调研，试点应用效果显著，具备快速落地条件。
                    </p>
                </div>
                <div class="bg-dark/50 p-8 rounded-2xl border border-primary/30">
                    <h4 class="text-xl font-bold mb-6">三级盈利模式</h4>
                    <div class="space-y-6">
                        <div class="flex gap-4">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0">1</div>
                            <div>
                                <h5 class="font-semibold mb-1">硬件销售</h5>
                                <p class="text-sm text-light/70">智能防鸟装置批量销售，覆盖全国铁路网络</p>
                            </div>
                        </div>
                        <div class="flex gap-4">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0">2</div>
                            <div>
                                <h5 class="font-semibold mb-1">运维服务</h5>
                                <p class="text-sm text-light/70">年度维保+监测服务，持续稳定收益</p>
                            </div>
                        </div>
                        <div class="flex gap-4">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0">3</div>
                            <div>
                                <h5 class="font-semibold mb-1">数据增值</h5>
                                <p class="text-sm text-light/70">鸟害大数据分析，为铁路运维提供决策支撑</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 社会价值 -->
    <section id="value" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">社会与生态价值</h2>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-dark/80 p-8 rounded-2xl border border-primary/20 text-center card-hover">
                    <i class="fa fa-train text-4xl text-primary mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">保障铁路安全</h3>
                    <p class="text-light/70">减少接触网故障，每年挽回经济损失超2.3亿元</p>
                </div>
                <div class="bg-dark/80 p-8 rounded-2xl border border-primary/20 text-center card-hover">
                    <i class="fa fa-user text-4xl text-primary mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">降低作业风险</h3>
                    <p class="text-light/70">替代高空人工巡检，作业伤亡风险降低76%</p>
                </div>
                <div class="bg-dark/80 p-8 rounded-2xl border border-primary/20 text-center card-hover">
                    <i class="fa fa-leaf text-4xl text-primary mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">绿色生态保护</h3>
                    <p class="text-light/70">非杀伤性驱鸟，符合环保法规，实现人鸟和谐</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 产品解决方案 -->
    <section id="solution" class="py-20 bg-gradient-tech">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">产品解决方案</h2>
                <p class="text-light/70">全方位智能防鸟系统，为铁路安全保驾护航</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h3 class="text-2xl font-semibold mb-6 text-gradient">系统架构</h3>
                    <div class="space-y-6">
                        <div class="flex gap-4 items-start">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0 mt-1">
                                <i class="fa fa-signal text-white"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">前端感知层</h4>
                                <p class="text-light/70">无源智能驱鸟装置 + 环境监测传感器，实时采集鸟害数据</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0 mt-1">
                                <i class="fa fa-exchange text-white"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">传输网络层</h4>
                                <p class="text-light/70">LoRaWAN + 4G混合组网，确保数据稳定传输</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0 mt-1">
                                <i class="fa fa-database text-white"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">数据处理层</h4>
                                <p class="text-light/70">边缘计算 + 云平台分析，实现智能预警与决策</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0 mt-1">
                                <i class="fa fa-desktop text-white"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">应用服务层</h4>
                                <p class="text-light/70">PC端管理系统 + 移动端APP，实现远程监控与管理</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-dark/50 p-8 rounded-2xl border border-primary/30">
                    <h4 class="text-xl font-bold mb-6">核心功能</h4>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">智能识别鸟类活动</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">自适应驱鸟策略</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">实时数据监测</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">远程故障诊断</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">鸟害热力图分析</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">智能预警推送</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">设备状态管理</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary"></i>
                            <span class="text-light/80">历史数据分析</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mt-16">
                <h3 class="text-2xl font-semibold mb-6 text-center text-gradient">系统架构图</h3>
                <div class="bg-dark/50 p-6 rounded-2xl border border-primary/30 flex justify-center">
                    <img src="https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=铁路接触网智能防鸟系统技术架构图，包含前端感知层、传输网络层、数据处理层和应用服务层，专业技术风格，蓝色调" alt="系统架构图" class="max-w-full h-auto rounded-lg">
                </div>
            </div>
            <div class="mt-16 grid md:grid-cols-3 gap-8">
                <div class="bg-dark/80 p-6 rounded-xl border border-primary/20 card-hover">
                    <h4 class="font-semibold mb-3">高速铁路</h4>
                    <p class="text-light/70 text-sm">适用于时速250km/h以上的高铁线路，保障高速列车供电安全</p>
                </div>
                <div class="bg-dark/80 p-6 rounded-xl border border-primary/20 card-hover">
                    <h4 class="font-semibold mb-3">普速铁路</h4>
                    <p class="text-light/70 text-sm">覆盖全国普速铁路网络，降低运维成本，提高安全系数</p>
                </div>
                <div class="bg-dark/80 p-6 rounded-xl border border-primary/20 card-hover">
                    <h4 class="font-semibold mb-3">城市轨道交通</h4>
                    <p class="text-light/70 text-sm">适用于地铁、轻轨等城市轨道交通系统，确保运营安全</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 技术参数 -->
    <section id="specs" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">技术参数与规格</h2>
                <p class="text-light/70">精准的技术指标，确保系统稳定运行</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20">
                    <h3 class="text-xl font-bold mb-6">硬件参数</h3>
                    <div class="space-y-4">
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">驱鸟装置尺寸</span>
                            <span class="font-semibold">Φ300mm × 450mm</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">重量</span>
                            <span class="font-semibold">≤5kg</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">防护等级</span>
                            <span class="font-semibold">IP65</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">工作温度</span>
                            <span class="font-semibold">-40℃ ~ +85℃</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">工作湿度</span>
                            <span class="font-semibold">≤95%RH</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">使用寿命</span>
                            <span class="font-semibold">≥10年</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">安装方式</span>
                            <span class="font-semibold">抱箍式/螺栓式</span>
                        </div>
                    </div>
                </div>
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20">
                    <h3 class="text-xl font-bold mb-6">系统参数</h3>
                    <div class="space-y-4">
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">通信方式</span>
                            <span class="font-semibold">LoRaWAN + 4G</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">数据传输频率</span>
                            <span class="font-semibold">15分钟/次（可配置）</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">电池寿命</span>
                            <span class="font-semibold">≥5年（太阳能供电）</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">识别准确率</span>
                            <span class="font-semibold">≥90%</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">响应时间</span>
                            <span class="font-semibold">≤3秒</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">预警准确率</span>
                            <span class="font-semibold">≥85%</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-light/80">支持终端数量</span>
                            <span class="font-semibold">单网关≤1000个</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mt-12 bg-dark/50 p-6 rounded-xl border border-secondary/30">
                <h4 class="font-semibold mb-4">认证与标准</h4>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                    <div class="flex items-center gap-2">
                        <i class="fa fa-certificate text-secondary"></i>
                        <span class="text-light/80">ISO9001质量管理体系</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa fa-certificate text-secondary"></i>
                        <span class="text-light/80">CE认证</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa fa-certificate text-secondary"></i>
                        <span class="text-light/80">RoHS环保认证</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa fa-certificate text-secondary"></i>
                        <span class="text-light/80">铁路专用设备认证</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 应用案例 -->
    <section id="cases" class="py-20 bg-gradient-tech">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">成功应用案例</h2>
                <p class="text-light/70">实际应用效果显著，得到铁路部门高度认可</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- 案例1 -->
                <div class="bg-dark/80 rounded-2xl overflow-hidden border border-primary/20 card-hover">
                    <div class="h-48 bg-gradient-to-r from-primary/30 to-secondary/30 flex items-center justify-center">
                        <i class="fa fa-train text-5xl text-primary"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">某高铁线路试点</h3>
                        <p class="text-light/70 text-sm mb-4">
                            在某高铁线路安装50套智能防鸟系统，3个月内鸟巢发生率降低85%，接触网故障减少72%。
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-secondary">安装时间：2025年3月</span>
                            <span class="text-sm text-light/60">覆盖里程：120公里</span>
                        </div>
                    </div>
                </div>
                <!-- 案例2 -->
                <div class="bg-dark/80 rounded-2xl overflow-hidden border border-primary/20 card-hover">
                    <div class="h-48 bg-gradient-to-r from-primary/30 to-secondary/30 flex items-center justify-center">
                        <i class="fa fa-industry text-5xl text-primary"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">普速铁路应用</h3>
                        <p class="text-light/70 text-sm mb-4">
                            在某普速铁路段安装200套系统，6个月内人工巡检次数减少60%，运维成本降低45%。
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-secondary">安装时间：2025年1月</span>
                            <span class="text-sm text-light/60">覆盖里程：350公里</span>
                        </div>
                    </div>
                </div>
                <!-- 案例3 -->
                <div class="bg-dark/80 rounded-2xl overflow-hidden border border-primary/20 card-hover">
                    <div class="h-48 bg-gradient-to-r from-primary/30 to-secondary/30 flex items-center justify-center">
                        <i class="fa fa-bus text-5xl text-primary"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">城市轨道交通</h3>
                        <p class="text-light/70 text-sm mb-4">
                            在某城市地铁系统安装80套系统，4个月内鸟害事件减少90%，设备运行稳定性提升。
                        </p>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-secondary">安装时间：2025年5月</span>
                            <span class="text-sm text-light/60">覆盖站点：25个</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mt-12 bg-dark/50 p-8 rounded-2xl border border-secondary/30">
                <div class="flex flex-col md:flex-row gap-6 items-center">
                    <div class="md:w-1/3">
                        <h4 class="text-xl font-bold mb-4">客户反馈</h4>
                        <p class="text-light/80 italic">
                            "这套智能防鸟系统彻底解决了我们长期面临的鸟害问题，不仅减少了故障发生率，还降低了运维成本，是铁路安全保障的得力助手。"
                        </p>
                        <p class="text-secondary mt-4 font-semibold">—— 某铁路局运维负责人</p>
                    </div>
                    <div class="md:w-2/3 grid grid-cols-2 gap-4">
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary text-xl"></i>
                            <span class="text-light/80">故障发生率降低72%</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary text-xl"></i>
                            <span class="text-light/80">运维成本降低45%</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary text-xl"></i>
                            <span class="text-light/80">人工巡检次数减少60%</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa fa-check-circle text-secondary text-xl"></i>
                            <span class="text-light/80">客户满意度98%</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 团队介绍 -->
    <section id="team" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">专业团队</h2>
                <p class="text-light/70">由多学科专家组成的创新团队</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- 团队成员1 -->
                <div class="bg-dark/80 rounded-2xl p-6 text-center border border-primary/20 card-hover">
                    <div class="w-32 h-32 bg-gradient-to-r from-primary/30 to-secondary/30 rounded-full mx-auto mb-4 flex items-center justify-center">
                        <i class="fa fa-user text-4xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">张明</h3>
                    <p class="text-secondary mb-3">项目负责人</p>
                    <p class="text-light/70 text-sm">
                        铁路电气化专业博士，10年铁路安全运维经验，主持多项铁路安全技术研发项目。
                    </p>
                </div>
                <!-- 团队成员2 -->
                <div class="bg-dark/80 rounded-2xl p-6 text-center border border-primary/20 card-hover">
                    <div class="w-32 h-32 bg-gradient-to-r from-primary/30 to-secondary/30 rounded-full mx-auto mb-4 flex items-center justify-center">
                        <i class="fa fa-user text-4xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">李华</h3>
                    <p class="text-secondary mb-3">技术总监</p>
                    <p class="text-light/70 text-sm">
                        电子工程专业硕士，智能传感器专家，拥有多项物联网技术专利。
                    </p>
                </div>
                <!-- 团队成员3 -->
                <div class="bg-dark/80 rounded-2xl p-6 text-center border border-primary/20 card-hover">
                    <div class="w-32 h-32 bg-gradient-to-r from-primary/30 to-secondary/30 rounded-full mx-auto mb-4 flex items-center justify-center">
                        <i class="fa fa-user text-4xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">王芳</h3>
                    <p class="text-secondary mb-3">软件工程师</p>
                    <p class="text-light/70 text-sm">
                        计算机科学专业，专注于嵌入式系统开发和数据分析，具有丰富的物联网项目经验。
                    </p>
                </div>
                <!-- 团队成员4 -->
                <div class="bg-dark/80 rounded-2xl p-6 text-center border border-primary/20 card-hover">
                    <div class="w-32 h-32 bg-gradient-to-r from-primary/30 to-secondary/30 rounded-full mx-auto mb-4 flex items-center justify-center">
                        <i class="fa fa-user text-4xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">赵强</h3>
                    <p class="text-secondary mb-3">市场总监</p>
                    <p class="text-light/70 text-sm">
                        市场营销专业，8年铁路行业市场经验，熟悉铁路系统采购流程和需求分析。
                    </p>
                </div>
            </div>
            <div class="mt-12 bg-dark/50 p-8 rounded-2xl border border-secondary/30">
                <h4 class="text-xl font-bold mb-6 text-center">团队优势</h4>
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="text-center">
                        <div class="w-16 h-16 bg-primary/20 rounded-full mx-auto mb-4 flex items-center justify-center">
                            <i class="fa fa-graduation-cap text-2xl text-secondary"></i>
                        </div>
                        <h5 class="font-semibold mb-2">专业背景</h5>
                        <p class="text-light/70 text-sm">
                            团队成员均来自铁路、电子、计算机等相关专业，拥有深厚的理论基础和实践经验。
                        </p>
                    </div>
                    <div class="text-center">
                        <div class="w-16 h-16 bg-primary/20 rounded-full mx-auto mb-4 flex items-center justify-center">
                            <i class="fa fa-lightbulb-o text-2xl text-secondary"></i>
                        </div>
                        <h5 class="font-semibold mb-2">创新能力</h5>
                        <p class="text-light/70 text-sm">
                            拥有多项自主知识产权，持续进行技术创新和产品迭代，保持行业领先地位。
                        </p>
                    </div>
                    <div class="text-center">
                        <div class="w-16 h-16 bg-primary/20 rounded-full mx-auto mb-4 flex items-center justify-center">
                            <i class="fa fa-handshake-o text-2xl text-secondary"></i>
                        </div>
                        <h5 class="font-semibold mb-2">行业资源</h5>
                        <p class="text-light/70 text-sm">
                            与多家铁路局和科研机构建立合作关系，拥有丰富的行业资源和项目经验。
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 联系我们 -->
    <section id="contact" class="py-20 bg-gradient-tech">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">联系我们</h2>
                <p class="text-light/70">如有任何问题或合作意向，欢迎随时联系我们</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <div class="space-y-6">
                        <div class="flex gap-4 items-start">
                            <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center shrink-0">
                                <i class="fa fa-map-marker text-secondary text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">公司地址</h4>
                                <p class="text-light/70">北京市海淀区中关村科技园区8号楼</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center shrink-0">
                                <i class="fa fa-phone text-secondary text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">联系电话</h4>
                                <p class="text-light/70">400-888-8888</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center shrink-0">
                                <i class="fa fa-envelope text-secondary text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">电子邮箱</h4>
                                <p class="text-light/70">info@railway-bird.com</p>
                            </div>
                        </div>
                        <div class="flex gap-4 items-start">
                            <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center shrink-0">
                                <i class="fa fa-clock-o text-secondary text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold mb-2">工作时间</h4>
                                <p class="text-light/70">周一至周五 9:00-18:00</p>
                            </div>
                        </div>
                    </div>
                    <div class="mt-8 flex gap-4">
                        <a href="#" class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center hover:bg-primary/40 transition-colors">
                            <i class="fa fa-weixin text-secondary"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center hover:bg-primary/40 transition-colors">
                            <i class="fa fa-weibo text-secondary"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center hover:bg-primary/40 transition-colors">
                            <i class="fa fa-linkedin text-secondary"></i>
                        </a>
                    </div>
                </div>
                <div class="bg-dark/80 rounded-2xl p-8 border border-primary/20">
                    <h3 class="text-xl font-bold mb-6">发送消息</h3>
                    <form class="space-y-4">
                        <div>
                            <label class="block text-light/80 mb-2">姓名</label>
                            <input type="text" class="w-full bg-dark/50 border border-primary/30 rounded-lg px-4 py-2 text-white focus:outline-none focus:border-secondary">
                        </div>
                        <div>
                            <label class="block text-light/80 mb-2">邮箱</label>
                            <input type="email" class="w-full bg-dark/50 border border-primary/30 rounded-lg px-4 py-2 text-white focus:outline-none focus:border-secondary">
                        </div>
                        <div>
                            <label class="block text-light/80 mb-2">电话</label>
                            <input type="tel" class="w-full bg-dark/50 border border-primary/30 rounded-lg px-4 py-2 text-white focus:outline-none focus:border-secondary">
                        </div>
                        <div>
                            <label class="block text-light/80 mb-2">留言</label>
                            <textarea rows="4" class="w-full bg-dark/50 border border-primary/30 rounded-lg px-4 py-2 text-white focus:outline-none focus:border-secondary"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 bg-primary hover:bg-primary/80 rounded-lg font-semibold transition-colors">
                            提交
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- 底部 -->
    <footer class="py-10 border-t border-primary/20">
        <div class="container mx-auto px-4 text-center">
            <div class="flex items-center justify-center gap-2 mb-4">
                <i class="fa fa-shield text-secondary text-xl"></i>
                <span class="font-bold text-gradient">精探巢患 · 智驱护网</span>
            </div>
            <p class="text-light/60 text-sm">
                铁路接触网智能防鸟系统 © 2026 挑战杯大学生创业计划竞赛项目
            </p>
        </div>
    </footer>

    <script>
        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
                // 关闭移动端菜单
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // 移动端菜单切换
        document.querySelector('.md\:hidden').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
