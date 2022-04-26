# coding =utf8                                                                                                                       
                                                                                                                                     
FROM ubuntu:18.04                                                                                                                    
                                                                                                                                     
RUN apt update; apt install -y gnupg2                                                                                                
                                                                                                                                     
RUN apt install -y python3-pip                                                                                                       
                                                                                                                                     
#WORKDIR /home/radhikardotihal/miniproject2-container/webserver/app/                                                                 
                                                                                                                                     
COPY ./app /app                                                                                                                      
                                                                                                                                     
COPY requirements.txt /tmp/requirements.txt                                                                                          
                                                                                                                                     
RUN pip3 install -r /tmp/requirements.txt                                                                                            
                                                                                                                                     
RUN pip3 install flask                                                                                                               
                                                                                                                                     
ENTRYPOINT ["python3"]                                                                                                               
                                                                                                                                     
COPY ./run.py ./run.py                                                                                                               
                                                                                                                                     
CMD ["run.py"]         
