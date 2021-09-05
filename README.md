# unbun

unbunder for nodejs angular-vue-react app  

-----------------------------------------------------

how to run  https://github.com/akveo/ngx-admin  on py4web ?

cp unbun to ~/bin && chmod +x ~/bin/unbun 

1 cd py4web/apps && cp -a _scaffold ngx

2 cd ngx/static && mkdir tte && cd tte

3 git clone https://github.com/akveo/ngx-admin && cd ngx-admin

4 npm i && npm run build

5 cd to ngx/static/tte  && unbun

The script takes a long time: 1min to 7min.

please wait

firefox localhost:8000/ngx

--------------------------------------------------------

some optional advice: disable map-file generation before running the script

unbun was tested with some vue-react-angular projects 

examples here https://github.com/ali96343/facep4w

this is very experimental code, it works for me

-----------------------------------------------------
of course the script cannot take into account all the mistakes made by the authors of nodejs applications when setting up their project




