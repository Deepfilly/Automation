const Discord = require('discord.js');
const bot = new Discord.Client();
const weather = require('weather-js');
const fs = require('fs');
const db = require('quick.db');

bot.on('ready', () => {

    console.log('Bot started.');

});

bot.login(process.env.BOT_TOKEN');
