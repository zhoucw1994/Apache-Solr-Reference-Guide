日志记录页面显示此Solr节点记录的最近消息。

当你单击“日志记录”的链接时，将显示类似于下面的页面：

![](/assets/logging.png)
_主日志页面，包括由于客户端发送的坏文档而导致的错误的示例_

虽然此示例仅显示一个核心的日志消息，但如果你在单个实例中有多个核心，则每个核心都会列出，并列出每个核心的级别。

# 选择日志级别

当你选择左侧的Level菜单时，你会看到实例的类路径和类名的层次结构。以黄色突出显示的行表示该类具有日志记录功能。单击突出显示的行，将出现一个菜单，以允许你更改该类的日志级别。以粗体显示的字符表示该类不会受到对根的级别更改的影响。

![](/assets/level_menu.png)