# devops-netology
New changes
Another changes
# .gitignore пока пустой
# terraform/.gitignore по шаблону terraform

# во всех подпапках все файлы каталога .terraform
**/.terraform/* 

# все файлы в корневом каталоге с расширением .tfstate и слюбым расширением, если имеет .tfstate. в названии
*.tfstate
*.tfstate.*

# Файл crash.log и все файлы в корневом каталоге по маске crash.*.log
crash.log
crash.*.log

# Все файлы в корневом каталоге с расширением .tfvars
*.tfvars

# Файлы override.tf и override.tf.json и все файлы в корневом каталоге, оканчивающиеся на _override.tf и _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Файлы в корневом каталоге .terraformrc и terraform.rc
.terraformrc
terraform.rc

#для коммита с IDE

