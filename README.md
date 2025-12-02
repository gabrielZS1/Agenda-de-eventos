📅 Agenda de Eventos – Aplicativo Android

Este projeto é um aplicativo Android simples criado em Kotlin com interface definida em XML, exibindo uma lista de eventos em formato de cards com layout moderno e responsivo.

✨ Funcionalidades:

Exibição de um título principal (“Agenda de Eventos”)<br>
Lista de eventos em cartões individuais<br>

Cada card possui:<br>
🔹Ícone circular com data<br>
🔹Título do evento<br>
🔹Descrição do evento<br>
🔹Interface inspirada em um design limpo e minimalista<br>
🔹Uso de RelativeLayout para organização dos elementos<br>

🛠️ Tecnologias Utilizadas<br>
🔹Android Studio<br>
🔹Kotlin<br>
🔹XML (UI Layout)<br>
🔹API 36 (Android 15) – configurável<br>
🔹Drawables personalizados (ícone circular laranja)<br>

📂 Estrutura do Projeto:<br>
app/<br>
 ├── manifests<br>
 ├── kotlin+java/<br>
 │    └── MainActivity.<br>
 ├── res/<br>
 │    ├── drawable/<br>
 │    │    ├── orange22.png<br>
 │    │    ├── ic_launcher_background.xml<br>
 │    │    └── ic_launcher_foreground.xml<br>
 │    ├── layout/<br>
 │    │    └── activity_main.xml<br>
 │    ├── mipmap/<br>
 │    ├── values/<br>
 │    └── xml/<br>
 └── Gradle Scripts/<br>

 

🖼️ Interface do Aplicativo

A tela principal contém:<br>
🔹Um título centralizado<br>
🔹Três cartões de eventos<br>
🔹Layout baseado em RelativeLayout<br>
🔹Exemplo de cards exibidos:<br>
🔹Meetup de Tecnologia – 25 Jul<br>
🔹Feira de Negócios – 03 May<br>
🔹Conferência de Design – 12 Aug<br>

📑 Arquivos Importantes:
🔹 activity_main.xml<br>

Define a interface principal, contendo:
🔹Título<br>
🔹Cards estruturados com RelativeLayout<br>
🔹ImageView para o círculo com a data<br>
🔹TextView para título e descrição<br>

MainActivity.kt:

🔹Classe principal responsável por carregar o layout.
