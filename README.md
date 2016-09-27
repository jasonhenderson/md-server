# md-server
Lightweight markdown node.js server that uses embedded NeDB as default storage of MD documents. 

## purpose

The purpose of this server is to house and distribute knowledge, and to be used as an ongoing reference of that knowledge. Think "text book" without the book--you refert to it as your learn and practice, then have it as a place to revisit every so often when needed, even years later. 

## technology

The markdown syntax was selected as knowledge documentation format because of its simplicity, its widespread use on the web, and the availability of supporting resources. If you are new to markdown, or need a refresher on the sytax itself, checkout this over: https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. (Once the md-server project is live, it will be knowledged shared from the md-server!)

The server is written as a node.js express server and uses NeDB as the default database. It would be great to support other databases. The intention behind using NeDB was for quick install onto a server or container, to get up and running quickly. Other databases that support other goals would be welcomed.

Help on the project, in general, is welcomed.
