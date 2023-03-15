
## 🌎 English Tutor


This project is a simple spelling correction API from ChatGPT, which has a unique and efficient method to correct misspelled English texts. When sending a text with errors as a query param named \"text\", the API returns the same text, but with all necessary corrections made.

The following technologies were used in this project:
- C#;
- ASP .NET Core;
- .NET 7.0;
- ChatGPT.

## 📫  Routes

### English Tutor Controller

<img src="https://img.shields.io/badge/-GET-%2361AFFE" height="30" />

**"/api/english-tutor"**

_Get the text entered in corrected form using ChatGPT_

**query params:**

`text: string`

**response:**
```
string
```

## 🌐 Status
<p>Finished project ✅</p>

## 🧰 Prerequisites

- .NET 7.0 or +

- User secrets named "ChatGptSecretKey"


## 🔧 Installation
`$ git clone https://github.com/AllanDutra/english-tutor-chat-gpt.git`

`$ cd english-tutor-chat-gpt`

`$ dotnet restore`

`$ dotnet run`

**Server listenning at  [http://localhost:5256](http://localhost:5256)!**

## 🔨 Tools used

<div>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="80" /> 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" width="80" />
<img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" width="80" />
</div>
