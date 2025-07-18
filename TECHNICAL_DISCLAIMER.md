### 技术工具声明 (Technical Tool Declaration)

1. **功能本质**  
   本仓库仅包含一个域名替换技术工具(`autoUrl.py`):
   - 输入：用户提供的JSON配置实例(`url.example.json`)
   - 处理：对配置中的域名进行镜像替换
   - 输出：生成新的技术配置文件

2. **内容中立性**  
   - 本工具不解析、不存储、不审查任何配置指向的实际内容
   - 工具不知晓也不会修改被代理内容的实质信息
   - 所有最终内容均由用户原始配置(`url.example.json`)决定

3. **技术责任局限**  
   | 责任类型 | 是否承担 | 说明 |
   |---|---|----|
   | 域名替换功能 | ✓ | 保证技术功能实现 |
   | 被代理内容 | ✗ | 完全由配置提供者负责 |
   | 用户使用方式 | ✗ | 用户自主行为责任 |

4. **无内容关联声明**  
   提及的任何域名替换服务(如ghproxy):
   - 仅为公开技术基础设施
   - 不代表开发者对其服务内容的认可
   - 使用者需自行验证代理服务的合法性