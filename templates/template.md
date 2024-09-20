---
<%*
const title = await tp.system.prompt('Enter new article title')
await tp.file.rename(title);
%>
title: "<%* tR += title  %>"
emoji: 📚
type: tech
topics: 
published: false
url: "https://zenn.dev/mutao-net/articles/<% title %>"
aliases:
---
