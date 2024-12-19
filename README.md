# youyou_poc
佑友防火墙集合-后台执行与越权访问漏洞

**需要安装支持库**  
pip install requests  

python youyou_poc.py -h                        

                                                                                                 _ (`-.
                                                                                             ( (OO  )
          ,--.   ,--..-'),-----.  ,--. ,--.     ,--.   ,--..-'),-----.  ,--. ,--.           _.`     \ .-'),-----.    .-----.
           \  `.'  /( OO'  .-.  ' |  | |  |      \  `.'  /( OO'  .-.  ' |  | |  |          (__...--''( OO'  .-.  '  '  .--./
         .-')     / /   |  | |  | |  | | .-')  .-')     / /   |  | |  | |  | | .-')         |  /  | |/   |  | |  |  |  |('-.
        (OO  \   /  \_) |  |\|  | |  |_|( OO )(OO  \   /  \_) |  |\|  | |  |_|( OO ) (`-.   |  |_.' |\_) |  |\|  | /_) |OO  )
         |   /  /\_   \ |  | |  | |  | | `-' / |   /  /\_   \ |  | |  | |  | | `-' /(OO  )_ |  .___.'  \ |  | |  | ||  |`-'|
         `-./  /.__)   `'  '-'  '('  '-'(_.-'  `-./  /.__)   `'  '-'  '('  '-'(_.-',------.)|  |        `'  '-'  '(_'  '--'\
           `--'          `-----'   `-----'       `--'          `-----'   `-----'   `------' `--'          `-----'    `-----'

usage: youyou_poc.py [-h] [-u URL] [-f FILE]  

华夏 ERPV3.3 信息泄漏漏洞  

optional arguments:  
  -h, --help            show this help message and exit  
  -u URL, --url URL     添加url信息  
  -f FILE, --file FILE  添加txt文件  

example:  
        python3 XETUX_POC.py -u http://xxxx.xxxx.xxxx.xxxx  
        python3 XETUX_POC -f x_url.txt  
