# Anton-Bondarenko_infra
Anton-Bondarenko Infra repository

##Подключение к внутреннему хосту через внешний с агентом аутентификации и псевдотерминалом.
ssh -i ~/.ssh/appuser -A appuser@178.154.215.147 ssh 10.128.0.24
##Создание алиаса в профиле консоли someinternalhost
alias someinternalhost='ssh -i ~/.ssh/appuser -A appuser@178.154.215.147 ssh 10.128.0.24'
