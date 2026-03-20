# DEVbot

Discord bot for Roblox Lua scripting with AI.
// index.js
console.log("Bot legal iniciado!");

const respostas = ["Oi!", "Tudo bem?", "Como vai?", "Que legal!", "Interessante!"];
let i = 0;

setInterval(() => {
  console.log(`Bot diz: ${respostas[i % respostas.length]}`);
  i++;
}, 3000); // envia uma resposta a cada 3 segundos
