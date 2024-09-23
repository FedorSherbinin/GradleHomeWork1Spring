# GradleHomeWork1Spring

Это простое веб-приложение на Spring Boot, созданное с использованием Gradle. Приложение демонстрирует базовые возможности Spring Boot и предоставляет API для обработки HTTP-запросов.

## Стек технологий

- Java 17
- Spring Boot 3.2.1
- Gradle
- Log4j
- Commons Codec
- Telegram Bots API

## Установка

1. **Клонируйте репозиторий**:

   ```bash
   git clone <URL-вашего-репозитория>
   cd GradleHomeWork1Spring
Соберите проект:

Убедитесь, что у вас установлен Gradle. Выполните команду:

bash
Копировать код
gradle build
Запустите приложение:

Выполните команду:

bash
Копировать код
gradle bootRun
Откройте браузер и перейдите по адресу:

bash
Копировать код
http://localhost:8080/hello
Вы должны увидеть сообщение "Hello, World!".

Описание проекта
Этот проект является примером простого веб-приложения, использующего Spring Boot. Он включает:

Основной класс приложения с аннотацией @SpringBootApplication.
Контроллер, который обрабатывает запросы к /hello.
Зависимости
Проект использует следующие зависимости:

log4j:log4j:1.2.17
commons-codec:commons-codec:1.15
org.telegram:telegrambots:6.8.0
org.springframework.boot:spring-boot-starter-web
lombok (для упрощения кода)
