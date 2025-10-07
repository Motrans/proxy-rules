# proxy-rules

本项目为作者自用的网络代理规则配置，旨在通过网络代理服务对互联网访问进行智能分流。它能够区分在中国大陆可直接访问的网站（主要为境内网站）与被中国国家防火墙（GFW）屏蔽的网站，从而确保更顺畅的网络体验。  

用户可以使用 [subconverter](https://github.com/tindy2013/subconverter) 等代理配置转换工具，通过本项目提供的 **远程配置链接**，将原有网络代理配置文件转换为基于本项目规则的分流配置文件。  

**远程配置链接：**  
[https://raw.githubusercontent.com/Motrans/proxy-rules/main/rules.ini](https://raw.githubusercontent.com/Motrans/proxy-rules/main/rules.ini)  

> ⚠️ 注意：远程规则内容可能随原仓库更新而变化，本项目不对内容变动负责。

---

## 外部引用说明

本项目引用了以下开源项目：

- [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/tree/master) — 该项目基于 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议发布。  

> 本项目仅通过 URL 方式引用上述项目内容，**未复制、修改或分发**原项目的任何文件。

---

## 开放源代码许可证

本项目遵循 [MIT License](https://github.com/Motrans/proxy-rules/blob/main/LICENSE) 发布。  
若需要对本项目进行修改或分发，请在副本中保留原作者的版权声明和许可证文本。  

---

## 使用注意事项与免责声明

1. 本项目仅提供网络代理规则配置文件，不提供任何网络访问服务。  
2. 用户在使用本项目提供的配置文件时，应自行承担所有风险，包括但不限于网络安全风险、数据泄露风险及法律风险。  
3. 本项目特别提示：中国大陆境内使用网络代理服务需遵守《中华人民共和国网络安全法》《中华人民共和国电信条例》等相关法律法规。任何违反当地法律法规的行为均与本项目作者无关。  
4. 使用本项目的配置文件、远程规则或其生成的 YAML 文件，应完全遵守所在国家或地区的法律法规。禁止将其用于任何违法用途。  
5. 通过本项目远程引用的规则内容仍受原项目（ACL4SSR/ACL4SSR）[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议约束。用户在生成或使用相关配置文件时，应遵守原项目的许可条款。  
6. 作者不对因使用本项目规则导致的任何直接或间接损失承担责任，包括网络访问失败、数据损坏、法律责任等。  
7. 本项目对远程规则内容的更新、删除或不可用情况不承担任何责任。用户在使用时应自行核实内容的可用性和合规性。
