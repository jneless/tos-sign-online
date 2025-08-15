# 火山引擎 TOS 在线签名工具

* 火山引擎 TOS 的在线签名工具(非官方，但可用)
* html js 单页应用，基于 github + vercel 自动化构建
* 源码完全可见，无aksk泄漏风险

--- 

## 主打功能
* 完整的输入参数支持，**支持签 body**
* 提供完整签名过程，follow TOS 官网文档
* 可视化输出结果，**输出中间状态每一步数据**，便于排查每个参数的流转过程
* 支持 **生成 curl 命令**，直接在 console 校验签名逻辑
* 提供 Go、Python、Java、Node.js 完整的 request 代码，copy 即可运行

---

## Appendix
* GET、HEAD、POST 请求都已经测试完成
* 可能存在bug，**承诺会修复和维护**
* 如果使用中遇到问题，请提 issue