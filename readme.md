xTranfer
一面 3/13 50min
主要围绕项目
自己写的表单组件如何做联动
SSR ISR
小程序如花优化体积，首屏打开速度 （cdn，subpackage
手写题
实现lodash get方法 如 get(obj, 'a[1].b')

二面 3/16 45min
在公司开发过的提效工具
微前端沙箱有用到吗
react fiber 
useLayoutEffect和useEffect区别
react18新加的hooks
vue nextTick
事件循环，浏览器渲染
手写题
传入任意个数参数计算累乘结果，不同顺序的参数（如1、2和2、1）结果需要缓存（计算2、1直接取缓存过的1、2的结果），缓存空间不能无限增大，需要对缓存空间进行优化
（我用了LRU+参数排序转字符串做key）

总结：面试难度不高，主要围绕项目，公司技术栈是react
反思：项目深度可能不够，最后手写题算是做出来了，但是react原理答得不好没过。没过的原因大概也是因为这个


小红书 （电商后台）
一面 3/21 45min
业务介绍，主要围绕项目展开，做过的组件等
微前端、微前端keep-alive，微前端的一些优化
手写题
判断最长无重复字符串（动态规划）
https://leetcode.cn/problems/wtcaE1/
总结：面试难度不高，主要围绕项目，面试官感觉也比较年轻，提问的问题比较笼统，而我回答时间也没有更好的展开。
反思：微前端不够了解，需要自己能够表达一些项目开发亮点、项目要做好复盘


云知声 
一面 3/22 40min
js类型 引用类型和通用类型存储方式，栈和堆的区别
js浮点数丢失问题，js数值的最长数位
箭头函数与普通函数区别 （arguments区别没答上
new一个对象的过程
严格模式下的this
递归底层调用，尾递归调用，涉及 map reduce底层使用
querySelect和getElementById获取到的结果区别 （前者静态，后者为动态
vue3 api customerRef和shallowRef
回流重绘
BFC
介绍CDN
webpack loader用过哪些，plugin和loader区别
vue双向绑定原理
浏览器缓存。强缓存和协商缓存
koa洋葱模型，用过哪些中间件

二面 3/22 30min
get请求缓存，（面试官意思是一分钟之内重复请求，get请求参数一样接口有缓存，拿不到最新值，需要用post？？？
有没有了解过原生小程序
虚拟列表实现 （反复把实现方式往错误方向上带，说我说的不对，实现方案不完整，感觉他自己也不清楚
组件按需引入 （简历挑刺，说这种也不算按需引入

HR面 3/22 10min
离职原因
当前薪资
对新公司期待点以及忌讳的点
是否有其他offer，是不是接到面试邀请就会参加面试
面试会偏向面试哪些行业的公司
介绍了公司情况

总结：一面考了很多八股文，也有不少冷知识。大部分都回答上了，但是没答上的，面试官有点不屑。题目感觉就是网上找的八股文来问的。二面面试官问题比较多，一副看不太起人的样子，也一直在误导、挖坑、往错误方向上带，最后和它快怼起来了。
小公司面试遇到趾高气扬的更多，需要放平心态。基本上是“答不上来对方看不起你，打上来了对方给不起你”，当做取面经就好。
反思：确实发现了一些八股文里不会的内容，也算查缺补漏了；应对技术理解有误，会误导人的面试官，要更从容一点，不要被带偏。


shein （电商C端 vue）
一面 3/25 55min
SSR做的过程中的一些优化
vue和react区别
vue3和vue2的区别，模板编译、diff dom优化
react fiber理解，为什要这么做
xxs xsrf （xsrf预防方式没说出来）
脚手架的意义
webpack做过那些优化
vite和webpack的区别，为什么vite更快
koa和express的区别
做过那些性能优化
工程化的理解
开发脚手架中扮演的角色
公司的发布流程
开发一些提效工具
ts用的如何
code review
日常如何学习

总结：面试官不纠结小问题，整体也问的比较全面。项目方面知道了那些地方需要补足一下。中大厂面试主要围绕项目展开，做过的项目一定要弄懂，弄清楚，提效点、项目复盘、工程化、项目中所作的优化可以写一篇文档来记录
反思：有些地方说的太啰嗦，性能优化这一块讲的太笼统；表述能力还要提高。ts没答好，总体还是需要把ts看的熟练一点，目前面试问的挺多，以防被提问。很多名词知道有此物，但叫不上名字，vue3和vue2差别了解也要清楚，模板编译优化、diff dom优化等等
PS：面向海外电商，独角兽，听说也有工时系统。面试前猎头要了毕业证的编号去验证学历（真的很离谱），还说涨薪最多15%，感觉这公司可能钱少事多。

拼多多 （商家后台）
一面 3/29 47min 
简历项目介绍（供应链系统
做过那些webpack优化
项目性能优化
动态表单组件如何实现联动
编程题：
数组转成树
深拷贝
反转链表
https://leetcode.cn/problems/UHnkqh/

二面 4/03  57min
项目问题
h5做过那些优化
h5如何和客户端做的通信
编程题：
promise.allsettled
实现一个迭代器，传入数组参数实例化后，调用next方法返回数组中的偶数、不传数组参数调用next则一直返回偶数（2 3 6 8...
设计一个搜索提示search组件（搜索引擎输入框
qiankun微前端原理（如何请求到这个页面的资源, html-import-plugin
线上的node服务不稳定，经常会挂，如何做兜底
sso登录过程
cookies有哪些属性， httpOnly是做什么的
webpack plugin loader区别
loader实现的东西是否plugin能实现，反过来呢
ts和babel的区别

三面 4/06 37min
业务介绍
https和http区别
cookies和localstorage区别
浏览器拿到url到渲染页面的过程
实现一个排序表格 vue
实现一个搜索列表 react

HR面 4/10 30min
常见套路
离职原因
期望薪资

反思：一面编程题基本是送分题，但是数组转成树就是卡住了，突然紧张了，脑子一片空白写不出来。越想面过越紧张
自我介绍，项目介绍，性能优化、等细节点需要好好背诵一下。


百姓网 （新部门 AI C端）
一面 3/30 50min
项目介绍
判断 '汉ying字wen' 字符串长度、汉字长度为2、字母为1
数组去重，不借用es6的两种方法，indexOf有什么坑
呼吸灯动画效果实现，如何设置动画帧
解释一下CDN，以及用了CDN之后可以优化的点s
跨域实现 cors底层，流程
vue3和vue2使用上的区别
nextTick原理，什么情况下使用
为什么vue3删除了filter方法（自己挖的坑
elementUI使用体验，遇到的坑
介绍typescript 枚举类型 emnu

二面 4/6 23min
线上遇到白屏问题，如何解决
去除大小王的52张扑克牌，少了一个牌，如何快速找到（先排序，之后再做标记、或者排序后用二分法）
前公司三个优点和缺点 （ 最好还是别答得太实在，我就是觉得稳过了，说了几句实话）

总结：两位面试官感觉比较专业，少数会自我介绍的面试官，资历感觉应该比较久，业务介绍很详细；不会的点也能给出提示。
反思：cors原理了解的不够详细，还有css动画，都是没有复习到的点，表达能力还是要增强
最后给我说简历匹配度不够，没过🙄


携程 （打车部门）
一面 3/31 57min
自我介绍
（都是根据简历里问的）
项目组件库的问题
业务组件库、物料组件
（扩展问题：虚拟下拉列表，如果数据需要分组怎么处理）
npm包版本 z.y.x 代表的含义，什么时候要更新x，y，z
npm devDependence 和 preDependence、dependence区别
npm是否会装beta版本的包，npm包的^ ~ 和没有标识的区别
组件库是如何做版本升级的，如何管理版本号的问题
组件库提供给其他团队使用，更新、用户体验是如何收集的
组件库的按需引入怎么做（babel插件，antd/input
webpack插件优化了哪里
除了用ignorePlugin还有别的方式优化moment（contextReplacePlugin，换dayjs。面试官说还有种用babel的方式
sentry是如何收集报错的，如何自己实现一个性能埋点监控
性能监控都做了哪些，有哪些场景，都是如何优化的（接口、页面写的差，由此引入到了react的问题
react useMemo、useEffect是用来做什么的、react memo 
react生命周期，class和hooks的一些区别
react-native有用过嘛，说下大概的原理，如何与客户端交互（用了小程序的那一套答的，面试官说差不多是这样
react增量更新、和批量更新（没听仔细，我听到增量更新，给扯到webpack增量更新了
webpack 热更新原理
redux和mobx，区别。类比vuex
接口缓存，协商缓存如何判断，有哪些请求头中的字段
cache-control中的 no-cache和no-storage有什么区别（后面那个没听过
babel编译原理，是否写过插件
为什么要升级babel preset ，对es6新语法的了解
import和require的区别
变量提升，变量提升要解决的问题，优缺点，优先级
let、const和var的区别
介绍了一下之前做的node项目
个人感兴趣的方面 （工程化、架构，跨端，node
tree-shaking原理 （接着上问题，对工程化感兴趣的扩展

总结：面试官感觉年龄和我差不多，不过感觉对方知识量很足，尤其babel应该是很了解，问题都是跟着项目展开的，或者根据话题进行的，很多也是自己挖的坑
这的可以算是查缺补漏的一次面试
反思：react知识需要补足，redux和mobx忘光了，还是要把简历上写的东西全部搞懂搞透才行


极兔
一面 4/07 30min
项目介绍
签署合同项目，手写签名如何提取
webpack plugin loader区别
babel转义原理
git流程、特殊命令。fast-forward是什么
小程序优化
你是如何面进得物的
得物卖的谢是真的吗

二面 4/11 20min
自我介绍
项目优化介绍，介绍下项目中的难点
什么时候可以入职
如何看待休息日有工作电话过来（对方希望能立刻解决

HR面 4/11 30min
做的成功的项目
看见别人犯错会不会主动提示，如果对方不高兴怎么办
离职原因
期望薪资

总结
一面面得挺随便的，半个小时面试官直接问什么时候有空现场面，全程还在哼歌，挺惬意的emmmm，最后两个问题也很emmmm
二面感觉就是防水过得样子。大概率还是在薪资上被pass了，所以也没啥好反思的

申通快递
一面 4/07 40min
防抖和节流是什么、区别
为什么会有跨域、跨域的几种方式、实现
flex布局 flex： 1 0 0 每个属性的区别
async await底层原理
浏览器事件循环、和node事件循环的差异
强缓存、协商缓存
react 如何调用父组件的方法
react fiber
如何不用useState、useReduce更新组件 
如何实现react中的keep-alive 
webpack loder执行顺序
tree-shaking原理、SideEffects是什么
babel-import如何实现按需引入
为什么有tree-shaking 还要用babel-import删除多余组件
做过那些webpack优化
项目中做过的提效点和优化
ts中的infer是什么
types和interface的区别

二面 4/18 40min
手写题
给一堆树状结构数据，实现一个菜单，并做菜单搜索 （递归解析树，直接用antd画菜单）
介绍下项目中的难点
期望薪资

总结：
一面对于申通来说，我觉得有点逆天了，反问环节我问面试官这些问题，他也答得磕磕巴巴
二面技术面比较容易，面试官问完期望薪资之后，和我说三面面试官有事今天面不了了，让我回去了
（之前hr都过来接人了），不过也是因为薪资的原因，没啥好在意的

字节pico 
一面 4/13 46min
微前端沙箱、css如何实现隔离
shadow dom是什么 
项目中webpack做了哪些优化
webpack、vite差别，vite为何更快，生产环境打包做了哪些优化
cdn原理，cdn是如何选取最近的节点的
treeshaking原理
commonjs和esmodule区别
缓存原理、协商缓存、强缓存
内部切换技术栈的原因、如果自己作为项目的技术选型者，如何在技术选型间做取舍
taro为什么可以做语法转换、原理
composition api生命周期和vue2的变化
react 里面能否使用setTimeout更新state
const A = () => {
    const [count, setCount] = useState(0)
    setInterval(() => setCount(preCount => preCount+1), 1000)
    return <div>{count}</div>
}
团队有没有封装过 useInterval、useTimeout用来做轮询
hooks为什么只能在顶层调用，不能在判断语句里调用
ts题：
下面几种类型的含义 区别
    unknown
    any
    never
Pick<T, K> Omit<T, K> 含义
实现下面的功能
interface A {
    a: string;
    b: boolean;
}


Pick<A, 'a'>  => 
interface A {
    a: string;
}


type MyPick<T, K> = // your code
<!-- ts不会，面试官说可以用js写 -->
function pick(obj: Record<string, unknown>, keys: string[]) {


}
总结：这场面试基本没准备，实在是面不动了，react的几个问题实际上不算难；vite和webpack能看出面试官是希望能说的
更深一点的；ts题基本是凉了，平时用的太少了
