# neimengguculture 非遗活动交流管理系统 非遗文化管理系统 内蒙古非遗美术交流系统 

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。
<font style="color:#117CEE;">🎈</font><font style="color:#117CEE;">系统亮点：协同过滤算法、内蒙古地图、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">前后端分离</font>

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue.js；UI库：ElementUI； </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis plus、Spring boot框架； </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2023.3.3版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现(部分截图)</font>
## 2.1用户
### 2.1.1 登录
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514055660-9c44f938-add0-446d-9677-7e73b8d4c9d6.png)

### 2.1.2 首页
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514062601-fab46306-5ea7-4923-a65b-60c07499d80a.png)

![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514064078-31199850-cb4c-46be-9c39-29ff59a4755d.png)

### 2.1.3 传人
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514073469-427073d6-1ce2-4713-ada4-e7b29c23e895.png)

![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514324831-11d7ca41-3263-4e67-9491-edafe93f8c5e.png)

### 2.1.4 资讯
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514076939-afa5116b-f3c7-48f4-9c7b-98de42c0f10e.png)

### 2.1.5 非遗话题
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514080879-23b7257b-9ff7-417d-b298-93a112ea2230.png)

### 2.1.6话题详情
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514084826-85e5ee49-688a-4db7-85c9-5a19ea5633af.png)

### 2.1.7非遗活动
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514093121-78d35a1a-e416-4dfc-87f4-481514164616.png)

### 2.1.8 活动详情


![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514096705-5a58a446-d42a-48cd-bc98-cad65c017479.png)

### 2.1.9 美术展厅
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514099322-b357fe5e-987a-400d-a1e9-abee4d73b996.png)

### 2.1.10 视频详情
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514100788-cb2800ed-8ee5-449d-ac04-41944ab8ba8f.png)

### 2.1.11 参加的活动
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514103439-39d24afb-cbb7-4d98-9354-29f207646d0f.png)

### 2.1.12 非遗申报
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514106432-e1a62fbe-7293-4625-8353-95834c3c96f0.png)

## 2.2 管理员
### 2.2.1 数据分析
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514108947-60ccf5f4-e689-4022-9d87-6143b6f97781.png)

### 2.2.2 用户管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514221604-67963815-6ed1-4c41-9c94-820deb7cd156.png)

### 2.2.3 活动管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514208839-a18bf40f-75ea-46e6-9e6f-2ae264b71af5.png)

### 2.2.4 活动记录
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514198451-64d4b3e9-dc27-419b-93f6-8a65f505659c.png)

### 2.2.5活动风采
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514191137-ea4fcf07-44b2-424f-a122-5a7b7529bdfd.png)

### 2.2.6非遗文化
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514244104-95538635-3f50-4f46-9963-65f0a1b3d324.png)

### 2.2.7 非遗传人
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514249243-e1e9d340-bb62-4f9b-9c25-db442915e64c.png)

### 2.2.8 非遗文化申请
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514253035-a299cd69-3e88-4d90-8803-ea5007de6185.png)

### 2.2.9 视频展览
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514259932-cf28712a-e6a2-4e6b-a2de-bfe426c6d24c.png)

### 2.2.10资讯
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514266184-046ad1ce-1cfd-4507-9e4f-3471e7b00301.png)

### 2.1.11 非遗话题
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514270166-1027db22-d7cb-4205-a7e7-a50855eeccea.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## 3.1 前端
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514274344-8b2cd5a1-506b-4fc8-ad99-82ed84e693e1.png)

## 3.2后端
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514277040-978b6c05-4713-4ca8-9f9c-8d616c21b02c.png)

## 3.3 数据库
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1760514280727-c389cc48-cc74-4101-8d57-9aa1a7dc11a0.png)

# <font style="color:rgba(72,179,120,1);">四.</font><font style="color:rgb(26, 173, 25);">系统代码获取</font>
<font style="color:rgb(0, 0, 0);">1.系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.由本人开发，如需源码，请后台直接联系我。q:2112698948;</font>

<font style="color:rgb(0, 0, 0);">3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

