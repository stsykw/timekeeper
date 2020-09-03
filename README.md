# 物理学会向け

物理学会向けに講演番号表示をつけました。デフォルト時間も物理学会に合わせています。
タイマー画面が座長のカメラに写り込むようにすれば時間管理が楽になると思います。

阪大理 湯川諭

以下、オリジナルのREADMEです。

# Time Keeper
HTML5 and JavaScript based timer with notification chime for academic conference.

### How to Use?
Access
http://maruta.github.io/timekeeper/  
or you can use local copy of this repository.

**:bangbang: Be careful to turn off screen savers and automatic screen cut :bangbang:**

### How to Save the Settings?
All current settings are included in URL.
Just use bookmark to preserve your settings.

When you are using Chrome and running local copy of Time Keeper,
Chrome does not permit to update the URL due to a security reason.
Time Keeper logo on left-top is the link to the URL with the current setting, and can be used to get the URL.

### How to Customize Appearance?

 * Edit timekeeper/theme/default.css
 * By using class added to the body tag, the appearance can be changed according to the phase and state of the timer.
 * Theme can be specified via URL as  
   http://maruta.github.io/timekeeper/#th=example  
   In this case, timekeeper/theme/example.css will be loaded in place of default.css.

### License
Timekeeper is open-sourced software licensed under The MIT License.

This repository contains codes from
 * [jQuery](https://jquery.org/license/) licensed under MIT License
 * [jQuery Timer plugin](http://www.mattptr.net/) licensed under BSD License
 * [Bootstrap](https://github.com/twbs/bootstrap/blob/master/LICENSE) licensed under MIT License
