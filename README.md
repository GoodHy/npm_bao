# npm_bao
1,测试的npm包
#username:jiahongyi
#password:jiabingyan1
#email:goodmenhy@163.com

2,##发布流程
npm login
npm publish

3,#撤销发布24小时内
npm unpublish
npm unpublish --force 强制删除

4,#添加npm用户
npm adduser

5.管理员权限
（1）查看管理包的所有者
npm owner ls <package name>

(2)添加/删除包的拥有者
npm owner add <user> <package name>
npm owner rm <user> <package name>

6.分析包
使用<npm ls>，可分析出当前路径下能够通过模块路径找到的所有包，并生成依赖树。
