# unbun

unbun - unbunde angular-vue-react app run it on py4web

-----------------------------------------------------

how to run  https://github.com/akveo/ngx-admin  on py4web ?

cp unbun to ~/bin && chmod +x ~/bin/unbun 

0 cd py4web/apps

1 cp -a _scaffold ngx

2 cd ngx/static && mkdir tte && cd tte

3 git clone https://github.com/akveo/ngx-admin && cd ngx-admin

4 npm i && npm run build

5 cd to ngx/static/tte  && unbun

The script takes a long time, 1 to 7 min.

please wait

firefox localhost:8000/ngx

--------------------------------------------------------

unbun - is a search-replace program.

some advice - disable map-file generation before running the script

unbun was tested with some vue-react-angular projects 

examples here https://github.com/ali96343/facep4w

this is very experimental code, but it works for me

