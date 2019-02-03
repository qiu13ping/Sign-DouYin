[Switch to Tiktik/Musical.ly](https://github.com/JokeAI/Sign-Tiktok)

## Demos
Demos can only be requested for limited times. if you need more, pls email jokeai@yandex.com

#### 1. Generate as/cp/mas parameters
```
curl -X "POST" "https://jokeai.zongcaihao.com/douyin/v292/sign" \
     -H 'Content-Type: application/json' \
     --insecure \
     -d $'{
  "url": "https://aweme.snssdk.com/aweme/v1/feed/?type=0&max_cursor=0&min_cursor=-1&count=6&volume=0.3333333333333333&pull_type=2&need_relieve_aweme=0&filter_warn=0&req_from&is_cold_start=0&js_sdk_version=1.2.2&app_type=normal&manifest_version_code=321&_rticket=1541682949911&ac=wifi&device_id=59121099964&iid=50416179430&os_version=8.1.0&channel=gray_3306&version_code=330&device_type=ONEPLUS%20A5000&language=zh&vid=C2DD3A72-18E8-490e-B58A-86AD20BB8035&resolution=1080*1920&openudid=27b34f50ff0ba8e26c5747b59bd6d160fbdff384&update_version_code=3216&app_name=aweme&version_name=3.3.0&os_api=27&device_brand=OnePlus&ssmix=a&device_platform=android&dpi=420&aid=1128"
}'
```

#### 2. Generate device info(install_id,device_id)
[https://jokeai.zongcaihao.com/douyin/v292/device](https://jokeai.zongcaihao.com/douyin/v292/device)

#### 3. API demos:

New algorithm can be used with more new APIs... 

| |  new as/cp/mas  | old 1.6.9 as/cp |
| ------------- | ------------- | ------------- |
| Home feeds  | [/v2/feed](https://jokeai.zongcaihao.com/douyin/v292/feed)  | [/v1/feed](https://jokeai.zongcaihao.com/douyin/v169/feed)  |
| x's videos  | [/v2/aweme/post](https://jokeai.zongcaihao.com/douyin/v292/aweme/post?user_id=83774364341&max_cursor=0&count=20)  | [/v1/aweme/post](https://jokeai.zongcaihao.com/douyin/v169/aweme/post?user_id=83774364341&max_cursor=0&count=20)  |
| x's likes  | [/v2/aweme/favorite](https://jokeai.zongcaihao.com/douyin/v292/aweme/favorite?user_id=83774364341&max_cursor=0&count=20)  | [/v1/aweme/favorite](https://jokeai.zongcaihao.com/douyin/v169/aweme/favorite?user_id=83774364341&max_cursor=0&count=20)  |
| x's info  | [/v2/user](https://jokeai.zongcaihao.com/douyin/v292/user?user_id=83774364341)  | [/v1/user](https://jokeai.zongcaihao.com/douyin/v169/user?user_id=83774364341)|
| x's followeings  | [/v2/user/following/list](https://jokeai.zongcaihao.com/douyin/v292/user/following/list?user_id=83774364341&max_time=1541202996)  | [/v1/user/following/list](https://jokeai.zongcaihao.com/douyin/v169/user/following/list?user_id=83774364341&max_time=1541202996)  |
| x's followers  | [/v2/user/follower/list](https://jokeai.zongcaihao.com/douyin/v292/user/follower/list?user_id=83774364341&max_time=1541473941)  | [/v1/user/follower/list](https://jokeai.zongcaihao.com/douyin/v169/user/follower/list?user_id=83774364341&max_time=1541473941)  |
| v's coments  | [/v2/comment/list](https://jokeai.zongcaihao.com/douyin/v292/comment/list?aweme_id=6615981222587796743&cursor=0)  | [/v1/comment/list](https://jokeai.zongcaihao.com/douyin/v169/comment/list?aweme_id=6615981222587796743&cursor=0)  |
| hot topics | [/v2/category/list](https://jokeai.zongcaihao.com/douyin/v292/category/list?cursor=0)  | [/v1/category/list](https://jokeai.zongcaihao.com/douyin/v169/category/list?cursor=0)   |
| topics list| [v2/challenge/aweme](https://jokeai.zongcaihao.com/douyin/v292/challenge/aweme?ch_id=1617915729448973&cursor=0)  | [v1/challenge/aweme](https://jokeai.zongcaihao.com/douyin/v169/challenge/aweme?ch_id=1617915729448973&cursor=0)   |
| topic info| [v2/challenge/detail](https://jokeai.zongcaihao.com/douyin/v292/challenge/detail?ch_id=1617915729448973)  | [v1/challenge/detail](https://jokeai.zongcaihao.com/douyin/v169/challenge/detail?ch_id=1617915729448973)   |
| search user| [v2/search/discover](https://jokeai.zongcaihao.com/douyin/v292/search/discover?keyword=lucas&cursor=0)  | [v1/search/discover](https://jokeai.zongcaihao.com/douyin/v169/search/discover?keyword=lucas&cursor=0) |
| search music| [v2/search/music](https://jokeai.zongcaihao.com/douyin/v292/search/music?keyword=lucas&cursor=0)  | [v1/search/music](https://jokeai.zongcaihao.com/douyin/v169/search/music?keyword=lucas&cursor=0) |
| search topic| [v2/search/challenge](https://jokeai.zongcaihao.com/douyin/v292/search/challenge?keyword=lucas&cursor=0)  | [v1/search/challenge](https://jokeai.zongcaihao.com/douyin/v169/search/challenge?keyword=lucas&cursor=0) |
| search video| [v2/search/item](https://jokeai.zongcaihao.com/douyin/v292/search/item?keyword=lucas&cursor=0)  |   |
| goods list  | [/v2/user/promotions](https://jokeai.zongcaihao.com/douyin/v292/user/promotions?user_id=93712507975&cursor=0)  |   |
| live list  | [/v2/room/feed](https://jokeai.zongcaihao.com/douyin/v292/room/feed?cursor=0)  |   |
| hot topics | [v2/hotsearch/word](https://jokeai.zongcaihao.com/douyin/v292/hotsearch/word)  |   |
| hot videos| [v2/hotsearch/aweme](https://jokeai.zongcaihao.com/douyin/v292/hotsearch/aweme)  |   |
| hot energy| [v2/hotsearch/energy](https://jokeai.zongcaihao.com/douyin/v292/hotsearch/energy)  |   |



