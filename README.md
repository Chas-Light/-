1. # 基于SSM搭建的点餐系统（前台+后台）
    
    #### 介绍
    
    Maven+Idea+Spring+SpringMVC+MyBatis+JSP实现的点餐系统（前台+后台）  
 
   
    
    #### 使用说明
    
    前台：http://localhost:8080/qiantai
    后台：http://localhost:8080/admin
    
    meal_ordering_system  
    ├─ .gitignore  
    ├─ README.md  
    ├─ apsfc 20150727 2133.sql  
    ├─ pom.xml  
    └─ src  
           └─ main  
                  ├─ java  
                  │    └─ com  
                  │           └─ example  
                  │                  └─ meal_ordering_system  
                  │                         ├─ controller  
                  │                         │    ├─ AdminController.java  
                  │                         │    ├─ FileController.java  
                  │                         │    ├─ MainController.java  
                  │                         │    ├─ MenusController.java  
                  │                         │    ├─ NoticeController.java  
                  │                         │    ├─ OrdersController.java  
                  │                         │    ├─ TypesController.java  
                  │                         │    └─ UsersController.java  
                  │                         ├─ dao  
                  │                         │    ├─ AdminDao.java  
                  │                         │    ├─ MenusDao.java  
                  │                         │    ├─ NoticeDao.java  
                  │                         │    ├─ OrdersDao.java  
                  │                         │    ├─ TypesDao.java  
                  │                         │    └─ UsersDao.java  
                  │                         ├─ entity  
                  │                         │    ├─ Admin.java  
                  │                         │    ├─ Menus.java  
                  │                         │    ├─ Notice.java  
                  │                         │    ├─ Orders.java  
                  │                         │    ├─ Page.java  
                  │                         │    ├─ Pages.java  
                  │                         │    ├─ ShoppingCart.java  
                  │                         │    ├─ Types.java  
                  │                         │    └─ Users.java  
                  │                         ├─ interceptor  
                  │                         │    ├─ AdminLoginInterceptor.java  
                  │                         │    └─ UserLoginInterceptor.java  
                  │                         ├─ service  
                  │                         │    ├─ AdminService.java  
                  │                         │    ├─ MenusService.java  
                  │                         │    ├─ NoticeService.java  
                  │                         │    ├─ OrdersService.java  
                  │                         │    ├─ TypesService.java  
                  │                         │    ├─ UsersService.java  
                  │                         │    └─ impl  
                  │                         ├─ test  
                  │                         │    └─ testmybatis.java  
                  │                         └─ util  
                  │                                └─ AdviceUtil.java  
                  ├─ resources  
                  │    ├─ applicationContext.xml  
                  │    ├─ log4j.properties   
                  │    ├─ mapper  
                  │    │    ├─ AdminDao.xml  
                  │    │    ├─ MenusDao.xml  
                  │    │    ├─ NoticeDao.xml  
                  │    │    ├─ OrdersDao.xml  
                  │    │    ├─ TypesDao.xml  
                  │    │    └─ UsersDao.xml  
                  │    ├─ springMVC.xml  
                  │    └─ sqlMapConfig.xml  
                  └─ webapp  
                         ├─ WEB-INF   
                         │    └─ web.xml  
                         └─ public  
                                ├─ admin   
                                └─ qiantai    
    
    #### 常见问题：
    
    1. 启动tomcat时，过滤器无法生效？  
       建议使用tomcat 8.5.65版本。
