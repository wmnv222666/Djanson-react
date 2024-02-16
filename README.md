 在虚拟的环境下安装Black 是一个自动代码格式化工具，可以帮助您确保 Python 代码符合一致的风格和格式。
 Pylint 是一个静态代码分析工具，用于检查 Python 代码中的错误、潜在问题和代码风格违规。与 Black 不同，Pylint 不仅可以帮助您确保代码格式正确，还可以检查代码质量和风格，并提供建议来改进代码。
 在下载一个request 查一下
 
 python -m pip install virtualenv
 python -m virtualenv venv 
 venv/scripts/activate
 <!-- python -m pip install flask -->
 python -m pip install django   or pip install Django==4.2LTS
 django-admin startproject foldername .    /*create name for forlder*/

 node.js download and install


 pip install djangorestframework
 django-admin startproject crud
 django-admin startapp api
 如果不小心关闭了terminal那还得venv/scripts/activate

 在crud settings.py进行修改
 然后进入api进行创建一个urls.py

 全部设置完后


        crud/urls.py: 这是项目的主URL配置文件。在这里，你导入了admin模块和include函数，然后设置了两个URL路径：

        admin/: 这是默认的Django管理员界面的URL路径，它会指向Django自带的管理站点。
        '': 这个空字符串路径将被include('api.urls')包含的URLs所处理。它实际上是项目的根路径。
        api/urls.py: 这是你创建的应用程序"api"的URL配置文件。在这里，你定义了一个URL路径：

        '': 这个路径是空字符串，它表示项目的根路径，因为在crud/urls.py中已经将项目的根路径指向了api.urls。所以，当用户访问项目的根路径时，会调用api.urls中定义的URL路由。
        api/views.py: 这是你的视图函数文件。在这里，你定义了一个名为home的视图函数，它接受一个请求对象作为参数，并返回一个简单的HTTP响应，内容为"This is the homepage"。

        综上所述，这些文件的组合使得当用户访问项目的根路径时，会调用api应用中的home视图函数，返回一个包含"This is the homepage"文本的HTTP响应。
 
 python manage.py makemigrations
 python manage.py migrate
 python manage.py runserver 启动后端项目进入到cd BACKEND  1.


 查看django的版本 就是1.venv/scripts/activate 2.python -m django --version  




 下面是前端react  安装
 1.npx create-next-app@latest frontend
 
 




