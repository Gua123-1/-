<！doctype html>
<超文本标记语言朗="zh-CN">
<头>
<元字符集="UTF-8">
<元姓名="视口" 内容="宽度=设备宽度，初始比例=1.0">
<标题>瓜瓜大王智能搜索平台</标题>
<脚本src="https://cdn.tailwindcss.com"></脚本>
<脚本>
//配置顺风自定义颜色和字体
顺风。配置={
主题: {
延伸: {
颜色: {
星: {
蓝色的：'#1E40AF'，
紫色的：'#7C3AED'，
粉红色：'#DB2777’
                        },
搜索: {
BG:'rgba(255,255,255,0.15)',
盘旋: 'rgba(255,255,255,0.25)'
                        }
                    },
fontFamily：{
间：['Inter'，'system-ui'，'无衬线']，['Inter'，'system-ui'，'无衬线'],
                    },
                }
            }
        }
脚本
<风格类型="text/tailwindcss">
@层实用程序{
.文本-阴影{
文本阴影：0010PXRGBA(255,255,255,0.8),0020PXRGBA(124,58,237,0.5);
            }
.search-input{
背景滤镜：模糊(8 PX)；
过渡：所有0.3s轻松；
            }
.search-btn{
过渡：所有0.3s轻松；
            }
.star-point{
位置：绝对；
边界半径：50%；
背景：白色；
动画：闪烁线性无限；
            }
@关键帧闪烁{
0%，100%{不透明度：0.3；}
50%{不透明度：1；}
            }
        }
</风格>
</头>
<身体班级="font-inter bg-gray-900min-h-屏幕溢出-x-隐藏">
<! -- 星空背景容器 -->
<div身份标识="星空"班级="固定插入-0Z-0"></div>

    <! -- 搜索主体内容 -->
    <div class="相对Z-10柔性伸缩柱项目-中心对齐-中心最小-h-屏幕px-4py-12">
    <! -- 标题 -->
    <h1class="text-[钳位(2rem，5vw，3.5rem)]字体-粗体文本-白色文本-阴影mb-12文本-中心">
    瓜瓜大王智能搜索平台
    </h1>

    <! -- 搜索框区域 -->
    <div class="w-full max-w-3xl mb-10">
    <div class="弹性项目-中心间隙-2bg-搜索-bg舍入-完全p-2悬停：bg-搜索-悬停过渡-所有持续时间-300">
    <! -- 搜索输入框 -->
    <输入
    type="text"
    占位符="快用你神奇的大问题填满我."
    班级="搜索-输入FLEX-1bg-透明边框-无边框-无文本-白色px-6PY-3文本-lg占位符：文本-白色/50"
    >
    <! -- 搜索按钮 -->
    <button class="search-btn bg-gradient-to-r从-星星-紫色到-星星-粉色文本-白色PX-8PY-3圆角-整体-中悬停：shadow-lg悬停：shadow-star-purple/30变换悬停：scale-105">
    开始搜索
    </button>
    </div>
    </div>

    <! -- 快捷搜索标签（已按需求替换+新增） -->
    <div class="w-full max-w-4xl网格列-2sm：网格列-4md：网格列-8间隙-3文本中心">
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    兑换码大全
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    Bug问题
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    十万个为什么
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    卡池列表
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    剧情问题
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    萌新入门指南
    </a>
    <！doctype html>
    全图矿点
    </a>
    <a href="#"class="text-white/80 hover:text-white PY-3 rounded-lg bg-search-bg hover:bg-search-hover transition-all">
    //配置顺风自定义颜色和字体
顺风。配置
主题

    颜色
    星
    蓝色的
    延伸
    粉红色

    搜索
    BG
    盘旋
    const sky=document.getElementById('starry-sky')；
</脚本>

    间
    文本
文本阴影：Const size=Math.random()*3+1；//星星大小：1-4px
Const PoSX=Math.random()*100；//X轴位置：0-100%
.search-inputConst posy=Math.random()*100；//Y轴位置：0-100%
背景滤镜：模糊
过渡：所有0.Const duration=Math.random()*10+5；//闪烁周期：5-15s
常数不透明度=Math.random()*0.7+0.3；//基础透明度：0.3-1

过渡：所有0.// 随机星星颜色（蓝/紫/粉）
<风格类型=['#1E40AF'，'#7C3AED'，'#DB2777'，' 白色']；
.star-pointConst randomColor=colors[Math.floor(Math.random()*颜色。长度)]层实用程序

    文本阴影：0010PXRGBA
    star.className='星点'；
    star.style.width='${size}px'；
    star.style.height='${size}px'；
    star.style.left="${PoSX}%"；
    star.style.top="${posy}%"；
    star.style.backgroundColor=randomColor；
    star.style.opacity=不透明度；
    star.style.animationDelay='${delay}s'；
    /风格>

<身体班级="font-inter bg-gray-900min-h-屏幕溢出-x-隐藏"
            }
<div身份标识="星空"

    // 页面加载时创建星空
    窗户。addEventListener('load'，createStarrySky)；
    //窗口调整大小时重新创建星空（适配屏幕变化）
    window.addEventListener('resize'，()=>{
    const sky=document.getElementById('starry-sky')；
    sky.innerHTML="；
    createStarrySky()；
        });
    </script>
</身体>
</超文本标记语言>

