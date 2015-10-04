vroom
=====

Video conf based on [SimpleWebRTC.js](https://github.com/HenrikJoreteg/SimpleWebRTC)

* Multi party audio+video
* Text Chat
* Optional Etherpad-Lite integration
* Screen Sharing (Google Chrome and Mozilla Fireofx)
* Reserved and persistent rooms
* Email notifications and invitations
* Password protected rooms
* Chairman features (mute/pause/kick other)
* Internationalization (english and french for now)
* Works with Mozilla Firefox, Google Chrome and Opera
* Works on Windows, Linux, Android (probably MAC OSX too)
* Responsive interface, working on smartphones, pads and desktops
* Fully opensource

You can try our demo instance here: https://vroom.im

Check documentation [here](https://vroom.im/documentation)

You can also subscribe to the dev mailing list [here](http://list.vroom.im/mailman/listinfo/vroom-dev)

Ubuntu install instructions:
sudo apt-get install libmime-lite-perl libmime-encwords-perl libdbi-perl libdbd-mysql-perl libarray-diff-perl libtest-pod-coverage-perl libtest-perl-critic-perl libmojolicious-perl libmodule-build-perl libjavascript-minifier-perl libfile-slurp-perl libcss-minifier-perl libtest-simple-perl libregexp-common-perl libpod-simple-perl libfile-sharedir-perl libtest-pod-perl libtest-minimumversion-perl libtest-cpan-meta-perl perl-base perl-modules libjson-perl perl libcpan-meta-perl libcrypt-saltedhash-perl libemail-valid-perl libexcel-writer-xlsx-perl liblocale-maketext-lexicon-perl libconfig-simple-perl libdatetime-perl
sudo cpan -i Mojolicious::Plugin::Mail 
sudo cpan -i Mojolicious::Plugin::Database 
sudo cpan -i Mojolicious::Plugin::StaticCompressor 
sudo cpan -i Mojolicious::Plugin::RenderFile 
sudo cpan -i Protocol::SocketIO 
sudo cpan -i Protocol::Redis Mojo::Redis2 
sudo cpan -i Session::Token 
