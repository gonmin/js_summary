###generator安装方法
1.generator并不随着yeoman安装，需单独安装。安装方法为generator+安装包的名字，比如angular的generator的安装包为`npm install -g generator-angular`
###yeoman
1.更新yeoman的方法`npm install -g yo to update`

2.用yeoman生成项目的方式是yo + 什么项目+项目名称，比如`yo angular +项目名称`，生成angular的项目。

3.生成项目时，需要选择包是，空格代表选择和取消选择。

###bower
1.bower安装文件bower install +名称，比如`bower install jquery`

2.如果没有注册，可以通过githubxie短写安装。

3.如果没有bower.json的话，通过bower init生成。

4.在如果要添加到devdepences,则使用bower install --save-dev

5.增加到生产环境的话 则使用 bower install --save。

6.说到使用script的麻烦

7.在bower中说到了bower生成文件。bower install ,然后是生成bower.json,然后引用script的时候说要结合grunt来说。

###grunt
第一节重点介绍gruntfile.js