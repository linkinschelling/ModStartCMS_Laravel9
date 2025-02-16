## 3.4.0

- 修复：用户名邮箱正则异常问题优化
- 优化：用户中心样式文件修改修改

---

## 3.3.0 用户名长度配置，VIP可见控制，优化注册方式

- 新增：用户名长度可后台配置（默认为3）
- 新增：禁止注册时允许设置以授权方式注册
- 新增：用户管理详情新增性别显示
- 新增：VIP用户等级新增可见字段，控制前端是否展示
- 优化：账号资料邮箱绑定绑定界面根据注册方式优化
- 优化：用户删除逻辑修复部分已知问题

---

## 3.2.0 VIP积分关联，多用户组判断，多处逻辑优化

- 新增：用户VIP开通赠送积分功能开启
- 新增：授权登录绑定手机和邮箱可配置
- 新增：用户注册处理器新增排序字段
- 新增：用户注册登录弹窗逻辑兼容处理
- 新增：是否多用户组判断方法inGroupIds
- 新增：用户手机登录时自动注册
- 新增：后台用户总数统计非删除用户数量
- 新增：已删除用户调用时显示为"已删除用户"
- 优化：当前用户组返回逻辑处理

---

## 3.1.0 手机快捷登录，VIP功能增强

- 新增：手机验证码快捷注册方式
- 新增：注销账号功能，用户可主动申请注销账号
- 新增：账号删除功能，后台可手动删除用户
- 新增：用户积分名称全局可修改（如修改为金豆）
- 新增：用户消息发送模板查找逻辑升级
- 新增：后台新增用户钱包流水详情列表
- 新增：后台新增用户积分流水详情列表
- 新增：后台管理用户批量禁用账户的功能
- 新增：后台管理用户信息查看列表新增用户ID
- 新增：授权登录头像为空时，显示默认头像
- 新增：登录失败提醒文案可跨定制
- 新增：会员新增时VIP过期时间调整为非必须
- 新增：文件上传和文件管理逻辑优化
- 新增：后台手动增加会员触发事件
- 新增：用户模型文件MemberUser
- 新增：用户钱包充值接口功能
- 新增：用户昵称可修改功能
- 优化：调整用户设置相关菜单到用户中心
- 优化：用户授权登录OpenId绑定key逻辑
- 优化：后台用户列表新增用户信息和修改账号操作
- 优化：后台用户管理创建和编辑界面重构完成
- 优化：用户中心功能设置界面重构
- 优化：用户VIP开通支付实现方式
- 修复：一处基础授权登录信息获取异常问题

---

## 3.0.0 手机快捷登录，登录URL安装校验

- 新增：手机验证码快捷登录方式
- 新增：用户默认登录方式可切换用户名密码或手机验证码
- 新增：用户登录完成默认跳转到用户中心
- 新增：用户登录跳转URL安全验证可配置

---

## 2.9.0 会员首页视图使用动态路径获取，可覆盖

- 优化：会员首页视图使用动态路径获取，可覆盖

---

## 2.8.0 钱包中心充值说哦名，钱包积分VIP启用逻辑简化

- 新增：后台链接选择增加用户开通VIP界面链接
- 新增：用户钱包中心新增钱包充值说明
- 优化：积分明细和钱包明细按照时间倒序排列
- 优化：积分启用、钱包启用、VIP启用使用单一模块功能控制

---

## 2.7.0 用户中心新增退出，授权异常处理

- 新增：用户中心新增退出登录
- 修复：授权登录手机端接口异常问题处理

---

## 2.6.0 用户VIP升级，管理布局优化

- 新增：用户VIP页面布局调整，主标题和副标题可配置
- 新增：用户VIP使用者抽象类
- 新增：用户VIP页面不登录访问不受限
- 新增：后台用户积分和用户余额变更功能
- 新增：后台链接选择找回密码
- 新增：授权登录失败时，增加重新跳转登录逻辑
- 优化：后台管理用户列表筛选布局优化

---

## 2.5.0 用户VIP优化，后台列显示定制

- 新增：支付对接方式升级
- 新增：用户VIP过期时间后台可修改
- 新增：后台用户列表自定义字段配置
- 优化：用户页面授权信息优化
- 优化：授权登录授权码兼容问题
- 优化：默认VIP等级显示优化

---

## 2.4.1 用户VIP修改不生效问题修复

- 修复：用户后台VIP列表修改不生效问题修复

---

## 2.4.0 用户VIP功能优化

- 新增：用户VIP为空时，默认初始化VIP等级
- 新增：用户VIP增加图标
- 新增：用户首页显示VIP数据信息
- 新增：适配Laravel9
