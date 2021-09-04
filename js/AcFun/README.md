配置
[rewrite_local]
^https:\/\/api\-ipv6\.app\.acfun\.cn\/rest\/app\/user\/personalInfo url script-request-header https://raw.githubusercontent.com/P-Zone-GH/Quantumultx/main/js/AcFun/Acfun.cookie.js

[task_local]
1 0 * * * https://raw.githubusercontent.com/P-Zone-GH/Quantumultx/main/js/AcFun/Acfun.js

说明
打开 APP, 访问下‘我的’，获取cookie
