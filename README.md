
## Santander Dev Week 2023 | [DIO](https://web.dio.me/)
[Click here](https://alexandrelorena.github.io/index.html) to access my online resume.

---
Java RESTful API criada para a Santander Dev Week.

## Principais Tecnologias

---
- **Java 21**
- **Spring Boot 3**
- **Spring Data JPA**
- **OpenAPI (Swagger)**
- **Railway**
---

## Diagrama de classes

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News

``` 

---
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>

<img src="https://i.imgur.com/h1q7oo1.jpg" width="785" height="5">

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=@alexandrelorena&v=2&theme=react" height="125" alt="languages graph"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=alexandrelorena&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=react&hide_border=false&order=2" height="125" alt="languages graph" />
  <img src="https://github-readme-stats.vercel.app/api?username=alexandrelorena&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=react&locale=en&hide_border=false&order=1" height="125" alt="stats graph"/>
</div>
<img src="https://i.imgur.com/h1q7oo1.jpg" width="785" height="5">

<div>
  <a href="mailto:alexandre.lorena@gmail.com" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/gmail" alt="Gmail" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://www.instagram.com/alexandre_lorena/" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/instagram" alt="Instagram" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/alexandrelorena-developer/" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/linkedin" alt="LinkedIn" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://x.com/alefaith" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/x" alt="Twitter" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://www.youtube.com/@alefaith2008/featured" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/youtube" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://steamcommunity.com/id/alexandrelorena/" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/steam/gray" width="32" height="32"></a>&nbsp;&nbsp;
  <a href="https://discord.com/channels/alelorena" style="text-decoration: none;">
    <img src="https://cdn.simpleicons.org/discord" width="32" height="32"></a>
</div>
</body>
</html>
