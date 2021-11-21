# Исключить все файлы с расширением .tfvars, которые могут содержать конфиденциальные данные, такие как пароли, ключи шифрования
# и иную закрытую информацию. Они не должны быть частью системы контроля версий т.к. являются точками данных, которые потенциально
# чувствительны и подвержены изменению в зависимости от окружения
*.tfvars

# Игнорировать файлы переопределения т.к. они обычно используются для локального переопределения ресурсов и не регистрируются
override.tf
override.tf.json
*_override.tf
*_override.tf.json

