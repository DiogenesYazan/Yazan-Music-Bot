# 🤖 Yazan Jr. (Discord Music Bot)
> Yazan Jr é um Discord Music Bot construído com discord.js

## Requisitos

1. Discord Bot Token **[Guia](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. Chave da API de dados do YouTube v3 **[Guia](https://developers.google.com/youtube/v3/getting-started)**
2.1 **(Opcional)** ID do cliente Soundcloud **[Guia](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v16.0.0 ou mais recente

## 🚀 Começando

Se estiver implantando no Heroku, certifique-se de criar variáveis ​​de configuração

```
git clone https://github.com/DiogenesYazan/YazanJr
cd YazanJr
npm install
```

Após a conclusão da instalação, você pode usar o `node index.js` para iniciar o bot.

## ⚙️ Configuração

Copie ou renomeie `config.json.example` para `config.json` e preencha os valores:

⚠️ **Observação: nunca comprometa ou compartilhe suas chaves de token ou API publicamente** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "LOCALE": "en",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

As localidades atualmente disponíveis são:
- Inglês (pt)
- Francês (fr)
- Espanhol(es)
- Turco (tr)
- Coreano (ko)
- Português Brasileiro (pt_br)
- Chinês simplificado (zh_cn)
- Chinês tradicional (zh_tw)
- Marque [Contribuindo](#-contribuindo) se quiser ajudar a adicionar mais idiomas!

## 📝 Recursos e comandos

> Nota: O prefixo padrão é '/'

* 🎶 Reproduza música do YouTube via url

`/play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Reproduza músicas do YouTube por meio de consulta de pesquisa

`/play under the bridge red hot chili peppers`

* 🎶 Reproduza música do Soundcloud via url

`/play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Pesquise e selecione a música para tocar

`/pesquisar Pearl Jam`

Responda com o número da música ou números separados por vírgula que você deseja tocar

Exemplos: `1` ou `1,2,3`

* 📃 Reproduza listas de reprodução do youtube via url

`/playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Reproduza listas de reprodução do youtube por meio de consulta de pesquisa

`/playlist linkin park meteora`
* Em Execução (/np)
* Sistema de filas (/queue, /q)
* Loop/Repetição (/loop)
* Embaralhar (/shuffle)
* Controle de volume (/volume, /v)
* Letra (/lyrics, /ly)
* Pausa (/pausa)
* Retomar (/resume, /r)
* Saltar (/skip, /s)
* Saltar para a música # na fila (/skipto, /st)
* Mover uma música na fila (/move, /mv)
* Remover música # da fila (/remove, /rm)
* Reproduza um clipe mp3 (/clip song.mp3) (coloque o arquivo na pasta de sons)
* Listar todos os clipes (/clips)
* Mostrar ping da API (/ping)
* Mostrar tempo de atividade do bot (/uptime)
* Alterne a poda de mensagens de bot (/pruning)
* Localização em 6 idiomas
* Ajuda (/help, /h)
* Manipulador de comandos de [discordjs.guide](https://discordjs.guide/)
* Controles de mídia via reações

![reactions](https://i.imgur.com/9S7Omf9.png)



## 📝 Credits

[@eritislami](https://github.com/eritislami) Todo direito autoral a [@ieritislam/discord-music-bot](https://github.com/eritislami/evobot)
