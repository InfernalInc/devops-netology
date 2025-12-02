# devops-netology

Первые данные

В рамках создания файла `.gitignore` будут проигнорированны следующие данные:
1. будет проигнорированна папка .terraform и ее содержимое
2. будут проигнорированные фалы в конце имени которых есть:
    - *.tfstate
    - *.tfvars
    - *.tfvars.json
    - *_override.tf
    - *_override.tf.json
3. Полность будут проигнорированные следующие файлы:
    - crash.log
    - override.tf
    - override.tf.json
    - .terraform.tfstate.lock.info
    - .terraformrc
    - terraform.rc
4. А так же будут проигнорированные файлы в которых есть упоминание (часть) данной конструкции, где * это любой символ:
    - \*.tfstate.\*
    - crash.*.log
