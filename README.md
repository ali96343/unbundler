# unbun

py4web tools

The python script makes the py4web app from angular-vue-react bundle

-----------------------------------------------------

how to run  https://github.com/akveo/ngx-admin on py4web ?

cp unbun to ~/bin && chmod +x ~/bin/unbun 

1 cd py4web/apps && cp -a _scaffold ngx

2 cd ngx/static && mkdir tte && cd tte

3 git clone https://github.com/akveo/ngx-admin && cd ngx-admin

4 npm i && npm run build

5 cd to ngx/static/tte  && unbun

The script takes a long time: up to 10min.

6 run py4web 

firefox localhost:8000/ngx

--------------------------------------------------------

optional advice: disable map-file generation before running the script

unbun was tested with vue-react-angular projects 

look into examples https://github.com/ali96343/facep4w

this is very experimental code 

thanks in advance for letting me about problems, errors ... 

-----------------------------------------------------
of course the script cannot take into account all the mistakes made by the authors of nodejs applications when setting up their project

-----------------------------------------------------

un-test: test app-urls,  run it from tte directory



