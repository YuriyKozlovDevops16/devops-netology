# devops-netology
Hi! It's READMI.md

Благодаря файлу terraform/.gitignore будут проинрориваны следующие файлы:

Файлы состояний, имя которых заканчивается на .tfstate, либо содержащее .tfstate.

Файлы логов с именем crash.log, либо файлы, имя которых начинается на crash. и заканчивается на .log

Файлы, имя которых заканчивается на .tfvars

Файлы с именем override.tf и override.tf.json, а так же файлы, имя которых заканчивается на _override.tf или _override.tf.json

Файлы с имеем .terraformrc или terraform.rc