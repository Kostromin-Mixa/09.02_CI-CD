# 09.02_CI-CD
1. Перед выполнением задания была проведена подготовка всех инструментов.
2. Работа проводилась в ОС UBUNTU.
Sonarqub:
3. Анализатор sonar-scanner запускался в директории с fail.py с дополнительным ключем.
4. Были выявлены и исправлены две ошибки в коде.
Nexus:
5. В репозиторий maven-public загрузил артефакт с предложенными GAV параметрами.
Все файлы загрузились успешно.
Maven:
Был изменен pom.xml блок с зависимостями под артефакт из задания для Nexus.
Запуск команды mvn package в директории с pom.xml прошел успешно.
К успешно выполненному заданию приложены скриншоты и pom.xml 
