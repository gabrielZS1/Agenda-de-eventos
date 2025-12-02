📅 Agenda de Eventos – Aplicativo Android

Este projeto é um aplicativo Android simples criado em Kotlin com interface definida em XML, exibindo uma lista de eventos em formato de cards com layout moderno e responsivo.

✨ Funcionalidades:

Exibição de um título principal (“Agenda de Eventos”)
Lista de eventos em cartões individuais

Cada card possui:
🔹Ícone circular com data
🔹Título do evento
🔹Descrição do evento
🔹Interface inspirada em um design limpo e minimalista
🔹Uso de RelativeLayout para organização dos elementos

🛠️ Tecnologias Utilizadas
🔹Android Studio
🔹Kotlin
🔹XML (UI Layout)
🔹API 36 (Android 15) – configurável
🔹Drawables personalizados (ícone circular laranja)

📂 Estrutura do Projeto:
app/
 ├── manifests/
 ├── kotlin+java/
 │    └── MainActivity.kt
 ├── res/
 │    ├── drawable/
 │    │    ├── orange22.png
 │    │    ├── ic_launcher_background.xml
 │    │    └── ic_launcher_foreground.xml
 │    ├── layout/
 │    │    └── activity_main.xml
 │    ├── mipmap/
 │    ├── values/
 │    └── xml/
 └── Gradle Scripts/

 

🖼️ Interface do Aplicativo

A tela principal contém:
🔹Um título centralizado
🔹Três cartões de eventos
🔹Layout baseado em RelativeLayout
🔹Exemplo de cards exibidos:
🔹Meetup de Tecnologia – 25 Jul
🔹Feira de Negócios – 03 May
🔹Conferência de Design – 12 Aug

📑 Arquivos Importantes:
🔹 activity_main.xml

Define a interface principal, contendo:
🔹Título
🔹Cards estruturados com RelativeLayout
🔹ImageView para o círculo com a data
🔹TextView para título e descrição

MainActivity.kt:

🔹Classe principal responsável por carregar o layout.
