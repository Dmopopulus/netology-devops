first line

С помощью файла .gitignore будет проигнорированы следующие файлы:

1. расположенние которых отвечают условию  **/terraform/*
2. с расширением .tfstate и .tfstate.*
3. логи crash.*
4. с расширением .tfvars
5. файлы с названием override.tf,override.tf.json и *_override.tf, *_override.tf.json
6. файлы конфигурации с расширением .terraformrc и terraform.rc
