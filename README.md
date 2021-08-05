# 09.02_CI-CD
1. Перед выполнением задания была проведена подготовка всех инструментов.
2. Работа проводилась в ОС UBUNTU.
3. Sonarqub:
4. Анализатор sonar-scanner запускался в директории с fail.py с дополнительным ключем.
5. Были выявлены и исправлены две ошибки в коде. [Sonarqub](https://github.com/Kostromin-Mixa/09.02_CI-CD/blob/main/SonarQube.png)
6. Nexus:
7. В репозиторий maven-public загрузил артефакт с предложенными GAV параметрами.
8. Все файлы загрузились успешно. [maven-public](https://github.com/Kostromin-Mixa/09.02_CI-CD/blob/main/maven-metadata.xml)
9. Maven:
10. Был изменен pom.xml блок с зависимостями под артефакт из задания для Nexus.
11. Запуск команды mvn package в директории с pom.xml прошел успешно.[mvn package](https://github.com/Kostromin-Mixa/09.02_CI-CD/blob/main/Nexus.png)
12. К успешно выполненному заданию приложены скриншоты и pom.xml 
