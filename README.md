# MobX 08-01

## -D-D-
* npm i mobx mobx-react
* npm i -D babel-plugin-transform-decorators-legacy babel-plugin-transform-class-properties

## Рекомендация
Те, кто работает в VS Code и высвечивается предупреждение у имени класса и переменной, где мы присвоили декораторы @observer и @observable, ошибка 'Experimental support for decorators is a feature that is subject to change in a future release. Set the 'experimentalDecorators' option to remove this warning', можно исправить это следующим образом:

1. выберите пункт меню Файл => Параметры => Параметры (File => Preferences => Settings)

2. Найдите параметр experimentalDecorators и задайте ему значение true. 
(Этот параметр может переопределяться в файле jsconfig.json или tsconfig.json, которые находятся в корне проекта)

3. В правой части должна появиться строка
javascript.implicitProjectConfig.experimentalDecorators": true,

4. Сохраните файл настроек

## Kava
* npm i --dev @babel/plugin-proposal-decorators
* npm i --dev mobx-react-devtools

npm i
@babel/core
@babel/plugin-proposal-class-properties
@babel/plugin-transform-runtime
@babel/preset-env
@babel/preset-react
@babel/preset-stage-2