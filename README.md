#VCoolor

### با استفاده از این پلاگین ما میتوانیم زمانی که کد نویسی میکنیم توی محط vim/neovim اگر خواستیم که یک رنگ خواسی را اعمال کنیم با این پلاگین ی پنجره برای ما باز میشه و ما میتونیم که رنگ مورد نظر خودمون رو انتخاب کنیم

### برای این کار ابتدا باید یکی از پکیج های zenity یا yad رو نصب کنیم

```
sudo apt install zenity
sudo apt install yad
```

### بعد از نصب کردن این موارد ما باید plugin پایین رو داخل .vimrc خودمون نصب کنیم

```
Plug 'KabbAmine/vCoolor.vim'
```

### الان برای استفاده کردن از اون کافیه ابتدا cursor رو جایی که میخوایم کد رنگ رو بنویسیم قرار بدیم بعد دستور :VCoolor رو توی مود command اجرا کنیم تا اون پنجره برای ما باز شه

```
:VCoolor
```

### علاوه بره :VCoolor ما میتونیم از کامند های پایین هم استفاده کنیم که تفاوت اون ها توی

```
:VCoolor
:VCoolIns r " For rgb color insertion
:VCoolIns h " For hsl color insertion
:VCoolIns ra " For rgba color insertion
```

#### [لینک منبع](https://github.com/KabbAmine/vCoolor.vim)
