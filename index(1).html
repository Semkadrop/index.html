<!doctype html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1">
<title>SEMKA DROP</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#07070b;color:#fff;font-family:Arial,sans-serif;min-height:100vh;display:flex;justify-content:center}
.app{width:100%;max-width:520px;padding:18px 12px 30px}
.login{position:fixed;inset:0;background:#07070b;display:flex;align-items:center;justify-content:center;padding:20px;z-index:20}
.login-box{width:100%;max-width:390px;background:#121018;border:1px solid #30283a;border-radius:20px;padding:24px;box-shadow:0 20px 60px #000}
.login-title{text-align:center;font-size:28px;font-weight:900;margin-bottom:8px}.login-title span{color:#a855f7}
.login-sub{text-align:center;color:#9993a2;font-size:13px;margin-bottom:20px}
input{width:100%;padding:15px;border-radius:13px;border:1px solid #38313f;background:#09090d;color:#fff;font-size:16px;outline:none}
input:focus{border-color:#a855f7}
.login button{margin-top:12px}
.error{display:none;color:#f87171;text-align:center;font-size:12px;margin-top:9px}
.top{display:flex;justify-content:space-between;align-items:center;margin-bottom:20px}
.logo{font-weight:900;font-size:28px;letter-spacing:1px}.logo span{color:#a855f7}
.player{background:#15131d;border:1px solid #30253e;border-radius:14px;padding:8px 10px;font-size:12px;font-weight:800}
.balance{margin-top:4px;color:#d8b4fe;font-size:13px}
.case{background:linear-gradient(180deg,#15121d,#0d0c12);border:1px solid #29212f;border-radius:20px;padding:16px;box-shadow:0 15px 50px #000}
.title{text-align:center;font-size:20px;font-weight:900;margin:2px 0 14px}
.roller-wrap{position:relative;overflow:hidden;border-radius:15px;background:#08080c;border:1px solid #27232d;height:150px}
.roller-wrap:before,.roller-wrap:after{content:"";position:absolute;z-index:3;top:0;height:100%;width:70px;pointer-events:none}
.roller-wrap:before{left:0;background:linear-gradient(90deg,#08080c,transparent)}
.roller-wrap:after{right:0;background:linear-gradient(-90deg,#08080c,transparent)}
.marker{position:absolute;z-index:5;left:50%;top:0;transform:translateX(-50%);height:100%;width:3px;background:#fff;box-shadow:0 0 15px #fff}
.marker:before{content:"";position:absolute;top:0;left:50%;transform:translateX(-50%);border-left:9px solid transparent;border-right:9px solid transparent;border-top:12px solid #fff}
.track{height:100%;display:flex;align-items:center;gap:10px;padding-left:calc(50% - 58px);will-change:transform}
.item{flex:0 0 116px;height:116px;border-radius:14px;border:2px solid #333;background:#15151b;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:7px}
.seed-img{width:64px;height:64px;object-fit:cover;border-radius:10px}
.name{font-size:12px;font-weight:900;text-align:center}.rarity{font-size:10px;font-weight:900;text-transform:uppercase}
.common{border-color:#777}.common .rarity{color:#aaa}
.uncommon{border-color:#22c55e}.uncommon .rarity{color:#4ade80}
.rare{border-color:#3b82f6}.rare .rarity{color:#60a5fa}
.epic{border-color:#a855f7;box-shadow:0 0 12px #7e22ce55}.epic .rarity{color:#c084fc}
.legendary{border-color:#f59e0b;box-shadow:0 0 16px #f59e0b55}.legendary .rarity{color:#fbbf24}
button{width:100%;margin-top:18px;padding:15px;border:0;border-radius:14px;background:linear-gradient(90deg,#7e22ce,#a855f7);color:white;font-size:17px;font-weight:900;cursor:pointer;box-shadow:0 8px 25px #7e22ce44}
button:disabled{opacity:.5}.cost{text-align:center;margin-top:9px;color:#9ca3af;font-size:13px}
.chances{margin-top:14px;padding:12px;border-radius:14px;background:#0d0c12;border:1px solid #28222f}
.chances-title{font-size:13px;font-weight:900;margin-bottom:8px}.chance-row{display:flex;justify-content:space-between;font-size:12px;margin:5px 0}
.result{display:none;text-align:center;margin-top:18px;padding:16px;border-radius:16px;background:#121018;border:1px solid #2e2638}
.result.show{display:block;animation:pop .35s ease}.result-img{width:100px;height:100px;object-fit:cover;border-radius:14px}.result h2{margin:5px 0}
.price{font-size:20px;font-weight:900;color:#fbbf24}.hint{color:#8d8796;font-size:12px;margin-top:10px}
.logout{background:#211b28;margin-top:12px;font-size:13px;padding:10px}
@keyframes pop{from{transform:scale(.9);opacity:0}to{transform:scale(1);opacity:1}}

.market{margin-top:14px;padding:14px;border:1px solid #30283a;border-radius:16px;background:#0d0c12}
.market-title{font-size:18px;font-weight:900;margin-bottom:10px}
.market-row{display:flex;gap:8px;margin-top:8px}
.market input,.market select{width:100%;padding:11px;border-radius:10px;border:1px solid #38313f;background:#09090d;color:#fff}
.market button{margin-top:8px;padding:11px;font-size:13px}
.market-list{margin-top:10px;display:grid;gap:8px}
.listing{display:flex;align-items:center;justify-content:space-between;gap:8px;padding:9px;border:1px solid #28222f;border-radius:11px;background:#121018}
.listing img{width:45px;height:45px;object-fit:cover;border-radius:8px}.listing-info{flex:1;font-size:11px}.listing-price{font-weight:900;color:#fbbf24}
.commission{font-size:11px;color:#8d8796;margin-top:6px}

.verified{display:inline-flex;align-items:center;justify-content:center;width:16px;height:16px;margin-left:4px;border-radius:50%;background:#3b82f6;color:#fff;font-size:11px;font-weight:900;vertical-align:middle}
</style>
</head>
<body>


<div class="login" id="login">
  <div class="login-box">
    <div class="login-title">SEMKA <span>DROP</span></div>
    <div class="login-sub" id="authTitle">Вход в аккаунт</div>
    <input id="nickname" maxlength="20" placeholder="Никнейм" autocomplete="username">
    <input id="password" type="password" maxlength="64" placeholder="Пароль" autocomplete="current-password" style="margin-top:10px">
    <button id="loginBtn">ВОЙТИ</button>
    <button id="registerBtn" style="background:#211b28;margin-top:10px">СОЗДАТЬ АККАУНТ</button>
    <div class="error" id="loginError"></div>
    <div class="commission" style="text-align:center;margin-top:12px">Новый аккаунт получает 500 GOLD</div>
  </div>
</div>

</div>

<div class="app">
<div class="top">
  <div class="logo">SEMKA <span>DROP</span></div>
  <div class="player">👤 <span id="playerName">Player</span><span id="verifiedBadge"></span><div class="balance">🪙 <span id="balance">500</span> GOLD</div></div>
</div>

<div class="case">
<div class="title">ОТКРЫТИЕ КЕЙСА</div>
<div class="roller-wrap"><div class="marker"></div><div class="track" id="track"></div></div>
<button id="spin">КРУТИТЬ — 500 GOLD</button>
<div class="cost">Лента → замедление → приз в центре</div>

<div class="chances">
<div class="chances-title">ШАНСЫ ВЫПАДЕНИЯ</div>
<div class="chance-row"><span>⚪ Обычная</span><b>64%</b></div>
<div class="chance-row"><span>🟢 Необычная</span><b>25%</b></div>
<div class="chance-row"><span>🔵 Редкая</span><b>7%</b></div>
<div class="chance-row"><span>🟣 Эпическая</span><b>3%</b></div>
<div class="chance-row"><span>🟡 Легендарная</span><b>1%</b></div>
</div>

<div class="result" id="result">
<div id="resultVisual"></div>
<h2 id="resultName">Семка</h2>
<div id="resultRarity">ОБЫЧНАЯ</div>
<div class="price">🪙 <span id="resultPrice">0</span> GOLD</div>
<div class="hint">Приз выпал из SEMKA DROP</div>
</div>


<div class="market">
  <div class="market-title">🛒 РЫНОК СЕМЕЧЕК</div>
  <div class="market-row">
    <select id="marketSeed"></select>
    <input id="marketPrice" type="number" min="1" placeholder="Цена GOLD">
  </div>
  <button id="sellSeed">ВЫСТАВИТЬ НА ПРОДАЖУ</button>
  <div class="commission">Комиссия рынка: <b>5%</b>. Комиссия поступает владельцу Semkadrop.</div>
  <div class="market-list" id="marketList"></div>
</div>

<div class="market" id="adminPanel" style="display:none">
  <div class="market-title">👑 АДМИН-КОНСОЛЬ</div>
  <input id="adminCommand" placeholder="/help">
  <button id="adminRun">ВЫПОЛНИТЬ</button>
  <div id="adminOutput" class="commission" style="white-space:pre-wrap;margin-top:10px"></div>
  <div class="market-title" style="margin-top:15px">🚨 ПОДОЗРИТЕЛЬНАЯ АКТИВНОСТЬ</div>
  <div id="alerts" class="market-list"></div>
</div>
<button class="logout" id="logout">СМЕНИТЬ НИКНЕЙМ</button>
</div>
</div>

<script>
const prizes=[
{name:"Обычная семка",rarity:"Обычная",cls:"common",price:100,image:"semki_2(1).png"},
{name:"Белая семка",rarity:"Необычная",cls:"uncommon",price:350,image:"semki_5(2).png"},
{name:"Золотистая семка",rarity:"Редкая",cls:"rare",price:750,image:"semki_1(3).png"},
{name:"Тёмная семка",rarity:"Эпическая",cls:"epic",price:2500,image:"semki_4.png"},
{name:"Полосатая семка",rarity:"Эпическая",cls:"epic",price:4200,image:"semki_3(1).png"},
{name:"Золотая семка",rarity:"Легендарная",cls:"legendary",price:10000,image:"semki_1(3).png"},
{name:"Неоновая семка",rarity:"Легендарная",cls:"legendary",price:25000,image:"semki_3(1).png"}
];

const OWNER="Semkadrop";
let playerName=localStorage.getItem("semka_drop_player");
let balance=500,busy=false;

const login=document.getElementById("login");
const nickname=document.getElementById("nickname");

const loginBtn=document.getElementById("loginBtn");
const registerBtn=document.getElementById("registerBtn");
const authTitle=document.getElementById("authTitle");
const loginError=document.getElementById("loginError");
const nickname=document.getElementById("nickname");
const password=document.getElementById("password");
const playerNameEl=document.getElementById("playerName");
const verifiedBadge=document.getElementById("verifiedBadge");
const balanceEl=document.getElementById("balance");
const login=document.getElementById("login");

const ACCOUNTS_KEY="semka_accounts_v2";
const CURRENT_KEY="semka_current_user_v2";
const OWNER_NAME="Semkadrop";

function accounts(){
 try{return JSON.parse(localStorage.getItem(ACCOUNTS_KEY)||"{}");}
 catch(e){return {};}
}
function saveAccounts(a){localStorage.setItem(ACCOUNTS_KEY,JSON.stringify(a));}
async function hashPassword(p){
 const data=new TextEncoder().encode(p);
 const hash=await crypto.subtle.digest("SHA-256",data);
 return Array.from(new Uint8Array(hash)).map(b=>b.toString(16).padStart(2,"0")).join("");
}
function normalize(n){return n.trim().toLowerCase();}
function updateVerified(){
 verifiedBadge.innerHTML=(playerName && normalize(playerName)===normalize(OWNER_NAME))
 ? '<span class="verified" title="Проверенный владелец">✓</span>' : '';
}

async function enterAccount(name,pass){
 name=name.trim();
 if(name.length<2||name.length>20||pass.length<4){
   loginError.textContent="Ник: 2–20 символов, пароль: минимум 4 символа.";
   loginError.style.display="block"; return;
 }
 const a=accounts(), key=normalize(name), h=await hashPassword(pass);
 if(!a[key]){
   loginError.textContent="Такого аккаунта нет. Нажми «Создать аккаунт».";
   loginError.style.display="block"; return;
 }
 if(a[key].passwordHash!==h){
   loginError.textContent="Неверный никнейм или пароль.";
   loginError.style.display="block"; return;
 }
 playerName=a[key].name;
 balance=Number(a[key].balance ?? 500);
 localStorage.setItem(CURRENT_KEY,key);
 playerNameEl.textContent=playerName;
 updateVerified();
 balanceEl.textContent=balance.toLocaleString("ru-RU");
 login.style.display="none";
 initAdmin();
 checkBanned();
}

async function registerAccount(name,pass){
 name=name.trim();
 if(name.length<2||name.length>20||pass.length<4){
   loginError.textContent="Ник: 2–20 символов, пароль: минимум 4 символа.";
   loginError.style.display="block"; return;
 }
 const a=accounts(), key=normalize(name);
 if(a[key]){
   loginError.textContent="Этот ник уже занят.";
   loginError.style.display="block"; return;
 }
 const h=await hashPassword(pass);
 a[key]={name, passwordHash:h, balance:500, createdAt:Date.now()};
 saveAccounts(a);
 localStorage.setItem(CURRENT_KEY,key);
 playerName=name;
 balance=500;
 playerNameEl.textContent=playerName;
 updateVerified();
 balanceEl.textContent=balance.toLocaleString("ru-RU");
 login.style.display="none";
 initAdmin();
 checkBanned();
}

loginBtn.onclick=()=>enterAccount(nickname.value,password.value);
registerBtn.onclick=()=>registerAccount(nickname.value,password.value);
nickname.addEventListener("keydown",e=>{if(e.key==="Enter")password.focus();});
password.addEventListener("keydown",e=>{if(e.key==="Enter")loginBtn.click();});

function save(){
 const a=accounts(), key=normalize(playerName);
 if(a[key]){
   a[key].balance=balance;
   saveAccounts(a);
 }
}

function logoutAccount(){
 localStorage.removeItem(CURRENT_KEY);
 location.reload();
}

document.getElementById("logout").onclick=logoutAccount;

async function restoreAccount(){
 const key=localStorage.getItem(CURRENT_KEY);
 if(!key)return;
 const a=accounts();
 if(!a[key]){localStorage.removeItem(CURRENT_KEY);return;}
 playerName=a[key].name;
 balance=Number(a[key].balance ?? 500);
 playerNameEl.textContent=playerName;
 updateVerified();
 balanceEl.textContent=balance.toLocaleString("ru-RU");
 login.style.display="none";
}

// ===== ADMIN CONSOLE =====
const ADMIN_NAME="Semkadrop";
const ADMIN_KEY="semka_admin_state_v1";
const ALERT_LIMIT=500000;
const adminPanel=document.getElementById("adminPanel");
const adminCommand=document.getElementById("adminCommand");
const adminRun=document.getElementById("adminRun");
const adminOutput=document.getElementById("adminOutput");
const alertsEl=document.getElementById("alerts");

function adminState(){
 try{return JSON.parse(localStorage.getItem(ADMIN_KEY)||'{"bans":[],"mutes":[],"alerts":[]}');}
 catch(e){return {bans:[],mutes:[],alerts:[]};}
}
function saveAdmin(s){localStorage.setItem(ADMIN_KEY,JSON.stringify(s));}
function isAdmin(){return playerName && playerName.toLowerCase()===ADMIN_NAME.toLowerCase();}

function addAlert(nick, amount, reason){
 const s=adminState();
 s.alerts.unshift({nick,amount,reason,time:new Date().toLocaleString("ru-RU")});
 s.alerts=s.alerts.slice(0,30);
 saveAdmin(s);
 renderAlerts();
}
function renderAlerts(){
 if(!isAdmin()) return;
 const s=adminState();
 alertsEl.innerHTML=s.alerts.length?s.alerts.map((a,i)=>
 `<div class="listing"><div class="listing-info"><b>🚨 ${a.nick}</b><br>+${Number(a.amount).toLocaleString("ru-RU")} GOLD<br>${a.reason}<br><span style="color:#666">${a.time}</span></div><button data-alertban="${i}" style="margin:0;padding:7px;font-size:11px">БАН</button></div>`
 ).join(""):'<div class="commission">Подозрительной активности пока нет.</div>';
}
function targetBalance(nick){
 const a=accounts(), k=normalize(nick);
 return a[k] ? Number(a[k].balance||0) : 0;
}
function setTargetBalance(nick,val){
 const a=accounts(), k=normalize(nick);
 if(a[k]){a[k].balance=Math.max(0,Math.floor(val));saveAccounts(a);}
}
function parseCmd(c){
 const parts=c.trim().split(/\s+/);
 const cmd=(parts[0]||"").toLowerCase();
 if(cmd==="/help") return `Команды:
/give Ник сумма
/take Ник сумма
/set Ник сумма
/balance Ник
/ban Ник
/unban Ник
/bans
/kick Ник
/mute Ник
/unmute Ник
/alerts
/clearalerts`;
 if(cmd==="/give"){
   const nick=parts[1], amount=Number(parts[2]);
   if(!nick||!Number.isFinite(amount)||amount<=0)return "Использование: /give Ник сумма";
   const old=targetBalance(nick), next=old+Math.floor(amount);
   setTargetBalance(nick,next);
   if(amount>=ALERT_LIMIT)addAlert(nick,amount,"крупное начисление");
   return `✅ ${nick}: +${Math.floor(amount).toLocaleString("ru-RU")} GOLD`;
 }
 if(cmd==="/take"){
   const nick=parts[1], amount=Number(parts[2]);
   if(!nick||!Number.isFinite(amount)||amount<=0)return "Использование: /take Ник сумма";
   const old=targetBalance(nick), next=Math.max(0,old-Math.floor(amount));
   setTargetBalance(nick,next);
   return `✅ ${nick}: снято ${Math.floor(amount).toLocaleString("ru-RU")} GOLD`;
 }
 if(cmd==="/set"){
   const nick=parts[1], amount=Number(parts[2]);
   if(!nick||!Number.isFinite(amount)||amount<0)return "Использование: /set Ник сумма";
   setTargetBalance(nick,amount);
   if(amount>=ALERT_LIMIT)addAlert(nick,amount,"установлен необычно большой баланс");
   return `✅ ${nick}: баланс установлен на ${Math.floor(amount).toLocaleString("ru-RU")} GOLD`;
 }
 if(cmd==="/balance"){
   const nick=parts[1];
   if(!nick)return "Использование: /balance Ник";
   return `💰 ${nick}: ${targetBalance(nick).toLocaleString("ru-RU")} GOLD`;
 }
 if(cmd==="/ban"){
   const nick=parts[1];
   if(!nick)return "Использование: /ban Ник";
   const s=adminState(); if(!s.bans.some(x=>x.toLowerCase()===nick.toLowerCase()))s.bans.push(nick);
   saveAdmin(s); return `🚫 ${nick} заблокирован.`;
 }
 if(cmd==="/unban"){
   const nick=parts[1]; if(!nick)return "Использование: /unban Ник";
   const s=adminState(); s.bans=s.bans.filter(x=>x.toLowerCase()!==nick.toLowerCase()); saveAdmin(s);
   return `✅ Бан с ${nick} снят.`;
 }
 if(cmd==="/bans"){
   const s=adminState(); return s.bans.length?`🚫 Баны:\n${s.bans.join("\n")}`:"Банов нет.";
 }
 if(cmd==="/mute"){
   const nick=parts[1]; if(!nick)return "Использование: /mute Ник";
   const s=adminState(); if(!s.mutes.includes(nick))s.mutes.push(nick); saveAdmin(s); return `🔇 ${nick} заглушён.`;
 }
 if(cmd==="/unmute"){
   const nick=parts[1]; if(!nick)return "Использование: /unmute Ник";
   const s=adminState(); s.mutes=s.mutes.filter(x=>x.toLowerCase()!==nick.toLowerCase()); saveAdmin(s); return `🔊 ${nick} снова может писать.`;
 }
 if(cmd==="/kick"){
   const nick=parts[1]; if(!nick)return "Использование: /kick Ник";
   return `👢 ${nick} отмечен для отключения. На GitHub Pages это локальная команда.`;
 }
 if(cmd==="/alerts"){
   const s=adminState(); return s.alerts.length?s.alerts.map(a=>`🚨 ${a.nick}: +${Number(a.amount).toLocaleString("ru-RU")} — ${a.reason}`).join("\n"):"Подозрительных операций нет.";
 }
 if(cmd==="/clearalerts"){
   const s=adminState(); s.alerts=[]; saveAdmin(s); renderAlerts(); return "✅ Журнал предупреждений очищен.";
 }
 return "❓ Неизвестная команда. Введи /help";
}

function initAdmin(){
 if(isAdmin()){
   adminPanel.style.display="block";
   renderAlerts();
 }
}
adminRun.onclick=()=>{
 if(!isAdmin())return;
 adminOutput.textContent=parseCmd(adminCommand.value);
 adminCommand.value="";
 renderAlerts();
};
adminCommand.addEventListener("keydown",e=>{if(e.key==="Enter")adminRun.click();});
alertsEl.onclick=e=>{
 const b=e.target.closest("[data-alertban]");
 if(!b)return;
 const s=adminState(), a=s.alerts[Number(b.dataset.alertban)];
 if(a){parseCmd("/ban "+a.nick);adminOutput.textContent=`🚫 ${a.nick} заблокирован.`;renderAlerts();}
};
initAdmin();

// Проверка бана при входе/обновлении.
function checkBanned(){
 if(!playerName)return;
 const s=adminState();
 if(s.bans.some(x=>x.toLowerCase()===playerName.toLowerCase())){
   document.body.innerHTML=`<div style="min-height:100vh;background:#07070b;color:white;display:flex;align-items:center;justify-content:center;text-align:center;font-family:Arial;padding:25px"><div><div style="font-size:55px">🚫</div><h1>Вы заблокированы</h1><p style="color:#aaa">Доступ к SEMKA DROP для ника <b>${playerName}</b> закрыт.</p></div></div>`;
 }
}
checkBanned();
</script>
</body>
</html>
<script>
restoreAccount();
</script>
