# Ansible Collection - my_own_namespace.yandex_cloud_elk

Documentation for the collection.

## Описание:
Пример написания собственного модуля в рамках обучения в Нетологии по курсу DevOPS

## Требования:
* ansible 2.10.8 или старше(на более ранних версиях не тестировалось)

## Переменные:

|Имя           |Значение по умолчанию | Описание |
|:------------:|:--------------------|:--------|
| path| /tmp/file  | Дирректория для записи файла|
| content| content | Текст, записываемый в файл|

## Описание процесса установки:

<code>
#Устанавливаем ansible
pip install ansible

#устанавливаем колеекцию
ansible-galaxy collection install -p ansible_collections my_own_namespace-yandex_cloud_elk-<version>.tar.gz
</code>