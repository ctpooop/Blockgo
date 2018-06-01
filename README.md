## Blockgo区块链社群营销工具使用说明




为了方便用户使用Blockgo社群营销工具，我们将使用过程中可能遇到的问题及操作方法编写成为用户使用手册。

#### 一、关于Blockgo社群营销工具

**1、Blockgo支持哪些平台？**

Blockgo目前仅支持基于Telegram的社群建立和管理。

**2、Blockgo如何开始使用？**

购买Blockgo后，我们将会为对应的项目创建并开通系统使用账号，同时配置好权限。在此之前可以使用我们的测试账号进行测试及体验。

测试地址：https://www.blockgo.cc

账号：demo@nework.pro

密码：Abc123456

**3、使用Blockgo之前需要准备什么资料？**

使用Blockgo之前需要准备的资料可以下载**《Blockgo区块链社群营销工具信息收集表》**查看并填写。

具体内容包含如下：

> * 项目名称，如：Nework
> * 币的名称，如：NKC
> * 电报群地址，如：https://t.me/nework_pro
> * 活动开始时间，如：2018-02-04 18:45
> * 活动结束时间，如：2018-02-04 18:45
> * 入群奖励，如：1 
> * 邀请奖励，如：5
> * 网站标题，如：Nework Airdrops
> * 英文规则，如：You can get 5 NKC for each recommended friend joined this group!
> * 中文规则，如：每推荐一个好友入群，即可获得5个NKC！
> * 项目官网，如：www.nework.pro


#### 二、如何建立Telegram群？

1、使用Telegram桌面客户端或APP客户端，点击 New Group，选择需要拉群的用户，确认后即可创建完成；

2、群创建完成后，进入群首页，点击Edit，可以Set Group Photo，同时可以点击Convert to SuperGroup将群组提升为超级群获得群消息置顶，专属群链接等更高权限。

#### 三、如何创建Telegram机器人？

1、在Telegram中搜索并添加一个用户名为Botfather的官方账户。

2、和Botfather沟通，使用/newbot命令进入创建机器人流程。

3、创建过程中，系统会要求设置机器人名称及username，username唯一并且需要以bot结尾，设置完成后即可得到创建成功提示，系统会返回机器人Token，请妥善保存，该Token需要在Blockgo后台配置填写。

4、机器人创建完成后需要输入/setprivacy命令设置机器人隐私模式，输入完成后，系统将提示选择需要配置的机器人，此时点击选择上一步创建的机器人即可。

5、选择完成后，系统提示启用或禁用机器人隐私模式，系统默认启用状态，点击选择Disable，允许机器人接收全部群组消息。

6、将设置完成的机器人拉到已经组建的Group中并设置为管理员，并启用全部群管理权限，此时机器人已经配置完成。


#### 四、如何配置Blockgo后台参数？

1、Blockgo后台管理功能为Home，Bot，Member，Share Event，Change Password五部分组成，对应功能如下：

> * Home，展示空投糖果活动数据及初始邀请链接（Share Link），数据展示的维度包含当日参与用户数，当日发出货币数，累计参与用户数，累计发出货币数，活动数据曲线。
> * Bot，配置并管理项目机器人。
> * Member，列表展示全部参与空投糖果活动用户数据，包含用户ID，用户收币地址，Telegram用户名，用户获得的数字货币数。
> * Share Event，配置糖果空投活动整体参数及规则。
> * Change Password，修改系统后台账号的密码。

2、设置机器人，后台点击Bot，选择New a bot，将在Telegram中创建机器人时获取的token填入Bot Token中，Notes为非必填，Token填写完成后，点击Great user即可创建完成，设置完成的机器人会展示在Bot list中。

3、设置活动参数，后台点击Share Event即进入活动参数配置流程，该流程分为三步，分别为基础信息配置，活动规则信息配置，前台展示信息配置，分别如下：

> * 基础信息配置（Base information）
>> * 项目名称（Project Name）
>> * 货币名称（Coin Name）
>> * 项目Logo链接（Logo Url），Logo链接可以访问https://img.vim-cn.com/ 上传Logo文件获取，Logo格式要求为圆形，300px，PNG格式。
>> * 项目群链接（Group Url）

> * 活动规则信息配置（Event information）
>> * 活动开始时间（Start Time）
>> * 活动结束时间（End Time）
>> * 进群验证奖励数额（Admission Reward）
>> * 邀请好友进群验证奖励数额（Share Reward）
>> * 总发币数量限制（Coin Limit）
>> * 单个用户最多获得糖果数量限制（Member Coin Limit）
>> * 广告清除功能开关（Ads clean，1代表开启，0代表关闭）
>> * 广告敏感词清除配置（ad words）

Blockgo综合过往项目使用情况建议进群验证奖励数额应小于邀请好友进群验证奖励数额，以此鼓励用户邀请，同时建议单个邀请用户的成本控制在 ¥ 2~3 元适中。

> * 前台展示信息配置（Display information）
>> * 邀请链接网站英文标题（Site Title / EN）
>> * 中文标题（Site Title / CN）
>> * 英文活动规则说明（Event Rule / EN）
>> * 中文活动规则说明（Event Rule / CN）
>> * 项目官网（Website）
>> * 是否需要用户填写邮箱（Need email，1代表开启，0代表关闭）。

以上数据示例可参考**《Blockgo区块链社群营销工具信息收集表》**。

#### 五、注意事项

1、在空投活动开始前，需要项目方确认以下问题：

> * 对空投活动的详细说明，建议中英文对照，用于发在项目群中置顶说明；
> * 活动结束后发币的规则，包括发币的时间，发币的数额限制，如单个用户最多可获得 500 货币奖励；

2、活动推广可参考的运营规则及文案示例：

#### 群置顶消息示例：

全球贵金属数字化交易所区块链项目MEX新年送礼第一弹！ 

空降MEX糖果活动 (2018年2月8日-2月21日)
 
第一步: 

点击https://www.blockgo.cc/?i=78UG1EYTZRHSCJ6PC， 输入您的以太坊钱包地址，获取您的专属邀请链接和验证码

第二步:

点击https://t.me/joinchat/HKiVbxHm-7ndD2QeaMwg7w， 进入MEX官方电报群，输入您的验证码，立得5枚MEX！

第三步: 

分享您的专属链接，每有一个新用户通过您分享的链接加入我们的电报群，您将再获得8枚MEX！

备注：糖果奖励 50 MEX 起发，单个用户最高可得 500 MEX，所有奖励糖果将在活动结束后一个月内统一发放。

MEX Airdrop Round 1 is live! 

1. Go to：https://www.blockgo.cc/?i=78UG1EYTZRHSCJ6PC ,Enter your ETH address

2. Go to：https://t.me/joinchat/HKiVbxHm-7ndD2QeaMwg7w, Send your Identifying Codes, You can get 5 MEX by joining this group!

3. Copy your invitation link and send to your friend, You will get 8 MEX for every friend you invite!

Note: all awards will be distributed at the end of the activity.

#### 对外推广文案示例：

#### 1、规则说明型：

NKC Airdrop 空降NKC糖果活动 (2018年1月16日-24日)

只需三步，立得NKC:

第一步: 

前往 https://tele.nework.pro， 输入您的以太坊钱包地址，获取您的专属邀请链接和验证码。
 
第二步:

前往Nework官方电报群（https://t.me/neworkpro ）输入您的验证码，立得20枚NKC。
 
第三步: 

分享您的专属链接，每有一个新用户加入我们的电报群，您将再获得20枚NKC。


#### 2、数据吸引型：

Nework正在免费空投5万枚NKC，送完即止！

我已经抢到了332个NKC，要上车的赶紧来 https://tele.nework.pro?code=1MOHP0G19J2SN


#### 六、实际使用

系统账号开通后，支持用户私聊机器人查询邀请人数及获得的货币数，对应命令如下：

> * /my_coin     查询已获得的货币数
> * /my_invite   查询已邀请的好友数




