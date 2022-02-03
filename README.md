# html_template
html_template
simpl html template allowing qwick start html page.

Стили scss компилируются в папку /css с помощью расширения VSCode Live Sass Compiler в низу нажать Watch Sass. В настройках расширения
 -  Extention Setting прописать, меняя scss будет появляется через время css, если в main.scss прописан @import, то не нужные файлы в css монжно удалить
{
    "workbench.colorTheme": "Default Dark+",
    "liveServer.settings.donotShowInfoMsg": true,
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded", //можно compressed, если нужен минимизированный css
            "extensionName": ".css",  //можно .min.css если указано compressed
            "savePath": "/css"  //можно dist/css
        }

    ],
    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 2 versions"
    ],
    "liveSassCompile.settings.generateMap": true,  //или false

}

