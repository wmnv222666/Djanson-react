 python -m pip install virtualenv
 python -m virtualenv venv 
 venv/scripts/activate
 python -m pip install django   or pip install Django==4.2LTS

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

 https://www.youtube.com/watch?v=F5OUT3ijk8M


 下面是前端react  安装
 1.npx create-next-app@latest frontend
 
 

https://www.youtube.com/watch?v=d_oPnD8A-lI&t=3138s



