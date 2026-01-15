# для старых версий macOS необходимо первоначально запустить colima
Первый запуск с настройкой ресурсов: colima start --cpu 4 --memory 8
colima start	Запускает виртуальную машину с параметрами по умолчанию
colima stop	Останавливает запущенную виртуальную машину
colima status	Показывает текущий статус работы виртуальной машины

# для Docker:
docker compose up	Запуск всех сервисов из docker-compose.yml
docker compose up -d	Запуск в фоновом режиме (демон)
docker compose start	Запуск остановленных контейнеров
docker compose restart	Перезапуск всех сервисов
docker compose stop	Остановка всех сервисов
docker compose down	Полная остановка + удаление контейнеров
docker compose pause	Приостановка всех сервисов
docker compose unpause	Возобновление работы
docker compose ps	Список контейнеров проекта