# Hello Magento

Módul de prova

## Clone

cd app/code/marrako
git clone https://github.com/alb3rts/HelloMagento.git

### Run the “setup:upgrade” command
Running this command makes your new module active, notifying Magento of its presence.

php bin/magento setup:upgrade

## Install
Insert in the composer.json file of the Magento 2 project, new repository: 

"alb3rts": {
    "type": "vcs",                                                                  
    "url": "https://github.com/alb3rts/HelloMagento/"                                      
}   

composer require alb3rts/HelloMagento