## mirai-devicejs-generator

生成 `Mirai` 运行时需要的 `device.json` 信息

**页面不校验填写的属性是否正确，请按照页面提示填写**

在线使用：https://ryoii.github.io/mirai-devicejs-generator/

### 说明

`device.json` 数据来着于登录设备，请在了解生成 `device.json` 的作用再进行操作，否则可能危害账号安全

### 作用

为首次使用 `Mirai bot` 的账号提供高信任度的 `device.json` 数据。

请将Bot在正常环境下登录一段时间后，获取登录设备的信息，填写到生成器中生成 `device.json` 信息。

当Bot发生设备迁移时，一并携带 `device.json` 迁移，可以提高Bot登录的成功率。

