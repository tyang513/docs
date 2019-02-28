git提交备注规范
格式 | 说明
:----------- | :-----------
feature:JIRA-ID jira summary | 
bugfix:JIRA-ID jira summary |
docs:(JIRA-ID) message或jira summary | 1.没有jira任务可以不写jira id
style:(JIRA-ID) message或jira summary | 1.没有jira任务可以不写jira id <br> 2.格式化代码<br> 3.优化java import
refactor:(JIRA-ID) message或jira summary | 1.没有jira任务可以不写jira id <br> 2.重构代码 <br> 3.去掉未使用的变量、过时方法修改 <br> 4.需要写清楚影响范围
test:(JIRA-ID) message或jira summary | 1.没有jira任务可以不写jira id <br> 2.src/main/test包提交代码
chore:(JIRA-ID) message或jira summary | 1.没有jira任务可以不写jira id <br> 2.构建过程或辅助工具的变动 <br>maven修改，包括：version修改 plugin修改 <br> 4.安装脚本修改
