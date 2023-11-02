# Django-
初學Django,慢慢進步

## 系統環境建置
可用pycharm直接創建Django環境
不同系統建置方法：https://developer.mozilla.org/zh-TW/docs/Learn/Server-side/Django/development_environment

## 初始化
![image](https://github.com/hank31169638/Django-/assets/128702246/82c46516-0345-4801-a5ab-fc72199bc7af)

創建完後請找到和manage.py同資料夾的地方打開cmd
然後打 py manage.py runserver   若沒py這個指令的可以試試python or python3 或是你沒將環境建置到path內
![image](https://github.com/hank31169638/Django-/assets/128702246/355058cc-7859-45a9-a27c-2b657b8b4758)

使用pycharm建置有可能會出現這種情況，請進入setting.py內找到
![image](https://github.com/hank31169638/Django-/assets/128702246/517b45ab-91ff-46cb-a359-d55283dd6017)

並將BASE_DIR / 'templates' 的 / 改成 ,

然後對cmd彈出的網址ctrl + 左鍵
即可看見最簡單的環境建置成功了！

## 基本的設定
可以開啟setting.py 設定
後端的語言和時區
請找到
![image](https://github.com/hank31169638/Django-/assets/128702246/19797a40-427b-4c05-9437-a2b898a1d079)
將LANGUAGE_CODE = 'en-us' 改成 LANGUAGE_CODE = 'zh-hant' 表示繁體中文
然後將時區 TIME_ZONE = 'UTC' 改成 TIME_ZONE = 'Asia/Taipei'
這樣在之後使用TimeZone上就不會有慢8個小時的情況出現
