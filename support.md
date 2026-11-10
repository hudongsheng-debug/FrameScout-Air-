# FrameScout Air 支持
最后更新：2026-11-10

## 联系方式
hudongsheng356@gmail.com
请在邮件主题中写明“FrameScout Air 支持”，并提供应用版本、iPad 型号、iPadOS 版本及复现步骤。请只发送你愿意分享的截图和最小示例；不要发送密码或无关敏感资料。

## 快速开始
- 从首页选择导入图像，通过系统“文件”选择二维 FITS。
- 在缩略图列表中选择图像，检查预览，标记保留或剔除。
- 按需填写备注或添加批注。
- 导出选择时指定目标文件夹，检查生成的 FITS 副本与 CSV。

## 数据和使用边界
支持未压缩二维 FITS 图像，不支持压缩 FITS 或数据立方体。预览及统计基于采样，不用于全分辨率测光。批注单独保存在本机，不写入原 FITS，也不包含在本版导出中。

## 保存与备份
导入的 FITS 副本、筛选状态、备注和 PencilKit 批注保存在应用本地空间。恢复列表受应用设置控制；删除列表记录只处理应用副本，不删除原始文件。
卸载或删除应用前，请先导出重要资料并保留原始文件。仅卸载应用与删除应用的系统行为可能不同；请按 iPad 的实际选项确认。

## 常见问题

### 批注会进入导出的 FITS 吗？
不会。批注独立保存在本机，本版也不把它们加入导出。

### 为什么图像读不出来？
请先确认是支持的未压缩二维 FITS，文件已从云端完整下载，且未超过 512 MiB。

### 文件选择器里找不到文件，或云文件无法读取？
先在系统“文件”中确认文件已完整下载、你有访问权限，且格式受本应用支持。重试时优先使用“我的 iPad”中的本地副本。扩展名相同不保证内部数据结构一致。

### 怎样报告问题？
说明你执行的操作、预期结果与实际结果，并提供不含敏感信息的截图。若需要样例，优先构造小型合成文件。没有源文件也可以先报告，我们会根据描述继续沟通。

## 隐私
本应用不要求账户，主要处理在设备本机完成。请阅读同目录的隐私政策，了解本地存储、文件服务和主动支持邮件的处理方式。

---

# FrameScout Air Support
Last updated: 2026-11-10

## Contact
hudongsheng356@gmail.com
Use “FrameScout Air Support” in the subject. Include the app version, iPad model, iPadOS version, and reproduction steps. Send only screenshots and minimal examples you are comfortable sharing. Do not send passwords or unrelated sensitive information.

## Quick start
- Choose Import Images and select 2D FITS files through Files.
- Select a thumbnail, inspect the preview, and mark it Keep or Reject.
- Add a note or annotation if needed.
- Export the selection to a folder and inspect the FITS copies and CSV.

## Data and scope
Supports uncompressed 2D FITS images, not compressed FITS or data cubes. Previews and statistics are sampled and are not full-resolution photometry. Annotations stay separate from the source FITS and are not included in this version’s exports.

## Saving and backups
Imported FITS copies, review states, notes, and PencilKit annotations are stored in the app’s local container. List restoration follows the app setting. Removing a list entry affects the app copy, not the original source file.
Export important work and retain source files before offloading or deleting the app. Offload App and Delete App can have different effects; check the actual system option on your iPad.

## Frequently asked questions

### Are annotations written into exported FITS files?
No. Annotations are local and separate, and this version does not include them in exports.

### Why will a file not open?
Confirm it is a supported uncompressed 2D FITS file, is fully downloaded from its provider, and is no larger than 512 MiB.

### A file is missing from the picker, or a cloud file will not open
In Files, confirm the file is fully downloaded, accessible, and in a supported format. Try a local copy under On My iPad. A matching filename extension does not guarantee a supported internal structure.

### How should I report a problem?
Describe the action, expected result, and actual result, with screenshots free of sensitive information. If an example is needed, prefer a small synthetic file. You may report the problem without a source file first; we can follow up from your description.

## Privacy
No account is required and core processing takes place on your device. Read the privacy policy in this folder for local storage, file services, and voluntary support communications.
