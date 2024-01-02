FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Uche"

#remove default nginx config file 
RUN rm -rf /etc/nginx/conf.d/default.conf 
# copy the content of the new config file into the new vproapp.conf 
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
