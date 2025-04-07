作为大模型巨头之一的 Anthropic 终于发布了他们的全新模型—— Claude 3.7 Sonnet 。
作为业界首个混合推理模型，Claude 3.7 sonnet不仅保持了Claude一以贯之的强大编程能力，还增加了推理能力。

然而国内使用Claude，尤其是Claude 3.5，由于其严格的访问限制和对新用户注册的控制，需要采取一些特定的方法才能搞定。
**以下是6种主要的使用策略：**

## 1.通过AWS的 Claude API
这个方法主要适用技术群体，因为可能大部分人连API是个啥都可能不清楚~作为Anthropic的投资者之一，Amazon和Anthropic是深度合作的。
今天，我们宣布扩大与 Amazon Web Services (AWS) 的合作，深化我们共同开发和部署先进人工智能系统的工作。此次扩大的合作伙伴关系包括 Amazon 新增的40亿美元投资，并将 AWS 确立为我们的主要云和培训合作伙伴。这将使亚马逊对 Anthropic 的总投资达到80亿美元，同时保持其少数股东的地位。 

![image](https://github.com/user-attachments/assets/530e6b87-14b0-4bf4-9672-8a7814c6c288)

同样的，在Claude 3.7 sonnet发布之后，第一时间在Amazon Bedrock和Google Cloud’s Vertex AI中就可以使用了。
需要注意的是，页面语言要切换到英文，才能看到Claude 3.7 sonnet的相关模型和介绍。

![image](https://github.com/user-attachments/assets/d1c09d00-e181-4612-b5b0-8245282bbb6b)

## 2.借助海外资源直接使用
虽然Claude保持了严格的风控政策，但是借助一些海外资源和方法还是能注册和使用Claude的：
### ①关于注册
相较于ChatGPT，目前Claude注册多了一重海外手机号验证的环节，因此你需要准备好：
网络：稳定的家用网络，不然基本上就是见光没（我试过）。
邮箱：需要是海外邮箱，比如Gmail、ProtonMail。
海外手机号：海外手机号可以通过第三方服务获取。
具体可以看这儿：
[Claude国内注册使用及升级指南（超详细）](https://mp.weixin.qq.com/s/taYP2ZTZ544_ez9Z728nqg)

![image](https://github.com/user-attachments/assets/54c69eb2-a0f8-480b-8dfc-c1d1a1fe4dc2)

### ②关于充值升级Pro
相较于ChatGPT，Claude对于免费用户可谓相当不友好，对用户风控严格就算了，而且如果你不是Pro用户，每次对话额度限制也十分严苛，问题长一些可能就没额度了。
这里可以通过野卡平台来解决，也可以用苹果的礼品卡，但是实测下来这个步骤要简单一点，像是ChatGPT、cursor、midjourney都可以用它来订阅，包括前面提到的AWS。
[Claude国内注册使用及升级指南（超详细）](https://mp.weixin.qq.com/s/taYP2ZTZ544_ez9Z728nqg)

![image](https://github.com/user-attachments/assets/859f1c0f-abe9-4c4c-9353-ca6c12e2ff2d)

## 3.通过谷歌云使用Claude API
前面提到，在官方发布的文档中就说了，他们第一时间就支持了Amazon Bedrock和Google Cloud’s Vertex AI，所以除了AWS之外，我们还可以通过谷歌云去使用。
目前谷歌云是有一些福利的，方式也是跟AWS一样，需要将页面语言切换为英文才能看到。

![image](https://github.com/user-attachments/assets/5b739d5b-faf3-43f0-9473-58c014b2e39c)

## 4. OpenRouter
OpenRouter作为一个一站式的AI模型平台，集合了几乎所有AI大语言模型的API。
相较于AWS和谷歌云，OpenRouter的优点是注册和使用相对简单，而且可调用的大模型API很多，包括DeepSeek R1，更重要的是提供直接使用的入口。
[OpenRouter怎么用？国内使用ChatGPT、Claude还不怕封的好方法](https://mp.weixin.qq.com/s/QAbJJt2Ta73o51Xem6h-1g)

![image](https://github.com/user-attachments/assets/fd95ab49-69d1-4701-943f-dd1e949a8ddf)

## 5.Poe等AI聚合站
考虑到Claude动不动就要review一下找人去封，Poe和you点com这种聚合站也不失为一种不错的选择，而且这些综合性平台，除了Claude之外，还能使用ChatGPT、Gork、Gemini、Flux、Luma等等不同的大模型。
这种平台比较适合想要尝鲜或者是有综合需求的朋友，缺点就是无法做到百分百还原完整的原版体验。
[Poe国内使用指南（超详细）｜无限次使用ChatGPT、Claude等大模型](https://mp.weixin.qq.com/s/ZybS5vDNec-ZATNh9pj3FQ)
![image](https://github.com/user-attachments/assets/da58e6bf-c879-4525-b424-d13d1c576ca5)

## 6.国内直连服务
如果大家懒得去搞定网络，也可以考虑使用国内的壳平台，这些平台也提供ChatGPT或者Claude的服务，且直接兼容国内网络环境，无封号风险，无需魔法工具。
例如，有的平台通过对接Claude的企业账号，提供稳定访问如[2233.ai](https://2233.ai/i/LINGAI)、[银河录像局](https://nf.video/dTJsp)、302ai之类的。
这类服务的特点包括：
无封号风险：直接使用，不用担心账户被封。
国内直连：无需科学上网工具，直接访问。
原生体验：支持最新版本的Claude功能。
隐私保护：独立对话存储，保障用户隐私。

## 7.注意事项
使用海外服务时，确保网络稳定，避免频繁更换IP，减少封号风险。
考虑到成本和隐私安全，国内替代平台可能是更经济、安全的选择，尤其是对于非频繁使用者。

其实不管是写代码或者文章写作，Claude目前的表现都十分出色，一定程度上要优于ChatGPT的，尤其是结合Artifacts之后，能创造的想象空间就更大了。
比如之前的汉语新解、thinking Claude等，都展示出Claude还有很大的使用潜力可以挖掘，个人体验下来也是觉得要更好。

![image](https://github.com/user-attachments/assets/c219e2ea-e593-4f2a-b9e2-cf37a5804cd1)

