##如何使用这份翻译

####拉取到本地

    git pull https://github.com/bingoku/Django-Docs-Chinese.git

####进入目录后执行

    sphinx-intl update-txconfig-resources --pot-dir _build/locale/ --transifex-project-name django-docs --locale-dir locale && tx pull -l zh_CN && sphinx-intl update --language=zh_CN && sphinx-build -b dirhtml -n -d _build/doctrees -D language=zh_CN . _build/html

####如何参与翻译

    > 注册并加入翻译团队：https://www.transifex.com/django/django-docs/language/zhCN/

