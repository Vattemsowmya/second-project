###	Resources
-	**CSS** 
Contains all User Interface framework css and custom css.
    -	Bootstrap.min.css : Bootstrap Framework
    -	Bootstrape-theme.css : Bootstrap Framework
    -	Font-awesome.min.css : Font Awesome icons Framework
    -	login.css
-	**JS** 
Contains all java script files and angular controllers.
      -	AngularController : Contains all the JavaScript source files related to Angular js.
          -	 App.js
          -	 Blog.js
          -  Chat.js
          -	 Forum.js
          -	 IndividualBlog.js
          -	 IndividualForum.js
          -	 Profile.js
          -  Settings.js
      -  angular.min.js
      -  bootstrap.min.js
      -  jquery-3.1.0.min.js
      -  ng-file-upload.min.js
      -  lodash.min.js
      -  sockjs.min.js
      -  stomp.min.js
-	**Fonts** : Contains all the fonts files.
-	**Images** : Contains static image used in UI.

###	 WEB-INF
-	**Includes**
    -	Frameworks.jsp : Contains code for importing all the mandatory imports like css,angular controllers, custom j's files. This file is imported on the home page.
    -	Header.jsp : Contains the header navigation bar.
    -	Footer.jsp : Contains footer code.
    -	Modal registration : Contains code for modal registration.
    -	Modal login : Contains code for modal login.
-	**jsp** : Contains all the dynamic web pages which will be invoked by spring mvc.
-	**ApplicationContext Config.xml** : Contains data source information and hibernate configuration.
-	**Dispatcher-servlet.xml** : Contains all spring  MVC configuration.
-	**Spring-security.xml** : Contains all configuration related to spring security.
-	**Web.xml** : Deployment descriptor.
