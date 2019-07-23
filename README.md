# scrpay
>## scrapy的流程
>## scrapy入门及使用
>>### 创建一个scrapy项目
         scrapy startproject spiderName
>>### 生成一个爬虫
         scrapy genspider itcast 'itcast.cn'
        
>## logging模块的使用 
>>### scrapy
        setting中设置LOG_WARNING='WARNING'
        seting中设置LOG_FILE='./a.log':设置日志文件保存的位置，设置后终端不会显示日志内容
        import logging实例化logger的方式在任何文件中使用logger输出内容
>>###  在普通项目中
        import logging
        logging,basicConfig(..):设置日志输出的样式，格式
        实例化一个logger = logging.getlogger(__name__)
        在任何py文件中调用logger即可
