<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Тетріс: графік відключень</title>
<style>
:root{--bg:#fff;--card:#fff;--tx:#1f2a4a;--mut:#6b7280;--ln:#e3e3e6;--ye:#ffe600;--gr:#d5d5d8;--ic:#3a3a3c;color-scheme:light;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#14161b;--card:#1e222a;--tx:#eef0f5;--mut:#9aa1af;--ln:#343a46;--gr:#4b4f58;--ic:#dcdce0;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#14161b;--card:#1e222a;--tx:#eef0f5;--mut:#9aa1af;--ln:#343a46;--gr:#4b4f58;--ic:#dcdce0;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;-webkit-user-select:none;user-select:none}
.app{max-width:460px;margin:0 auto;padding:10px 8px 14px;display:flex;flex-direction:column;align-items:center;gap:8px}
.top{align-self:stretch;display:flex;align-items:center;justify-content:space-between;gap:8px}
h1{font-size:19px;margin:2px 0 0;padding-left:4px}
#th{border:1px solid var(--ln);background:var(--card);color:var(--tx);border-radius:999px;padding:6px 12px;font-size:13px;white-space:nowrap}
.tab{align-self:stretch;background:var(--ye);color:#14213d;font-weight:700;font-size:14px;padding:9px 12px;border-radius:10px}
.stats{align-self:stretch;display:flex;gap:6px;align-items:stretch}
.stats>div{flex:1;background:var(--card);border:1px solid var(--ln);border-radius:10px;padding:5px 8px;display:flex;flex-direction:column;justify-content:center}
.stats b{font-size:19px;line-height:1.1}
.stats span{font-size:11px;color:var(--mut)}
.stats .nx{flex:0 0 auto;padding:2px}
.wrap{position:relative;border:1px solid var(--ln);border-radius:12px;overflow:hidden;background:var(--card)}
canvas{display:block}
.ov{position:absolute;inset:0;display:flex;flex-direction:column;gap:14px;align-items:center;justify-content:center;background:rgba(10,12,18,.62);color:#fff;text-align:center;padding:16px}
.ov p{margin:0;font-size:18px;font-weight:700}
.ov.h{display:none}
.warn{position:absolute;left:0;right:0;top:0;display:none;background:var(--ye);color:#14213d;font-weight:700;font-size:13px;text-align:center;padding:6px 8px;pointer-events:none}
.warn.on{display:block}
button{font:inherit;cursor:pointer;touch-action:manipulation}
#go{background:var(--ye);color:#14213d;border:0;border-radius:999px;padding:11px 28px;font-weight:700;font-size:16px}
.ctl{align-self:stretch;display:grid;grid-template-columns:repeat(6,1fr);gap:6px}
.ctl button{height:52px;border-radius:12px;border:1px solid var(--ln);background:var(--card);color:var(--tx);font-size:21px}
.ctl button.y{background:var(--ye);color:#14213d;border-color:var(--ye)}
.ctl button:active{transform:scale(.95)}
.leg{align-self:stretch;display:flex;gap:18px;font-size:12px;color:var(--mut);padding-left:4px}
.leg i{width:20px;height:20px;border:1px solid var(--ln);border-radius:3px;background:var(--card);display:inline-block;margin-right:6px;vertical-align:middle}
.leg i.g{background:var(--gr)}
.hint{font-size:11px;color:var(--mut);text-align:center;margin:0}
</style>
</head>
<body>
<div class="app">
  <div class="top"><h1>Графік відключень: Тетріс</h1><button id="th" title="Тема"></button></div>
  <div class="tab">⚡ на сьогодні <span id="d"></span></div>
  <div class="stats">
    <div><b id="sc">0</b><span>Бали</span></div>
    <div><b id="ln">0</b><span>Годин зі світлом</span></div>
    <div><b id="lv">1</b><span>Рівень</span></div>
    <div class="nx"><canvas id="nx"></canvas></div>
  </div>
  <div class="wrap">
    <canvas id="c"></canvas>
    <div class="warn" id="wn"></div>
    <div class="ov" id="ov"><p id="ot">Заповни всі групи за годину — і світло повернеться</p><button id="go">Грати</button></div>
  </div>
  <div class="leg"><span><i></i>Світло є</span><span><i class="g"></i>Світла немає</span></div>
  <div class="ctl">
    <button data-a="l">◀</button><button data-a="r">▶</button><button data-a="rot" class="y">⟳</button>
    <button data-a="d">▼</button><button data-a="hd">⤓</button><button data-a="p">⏸</button>
  </div>
  <p class="hint">Клавіатура: ← → рух, ↑ поворот, ↓ вниз, пробіл — скинути, P — пауза. Раз на 1,5–2,5 хв знизу виростає аварійний рядок.</p>
</div>
<script>
const COLS=12,ROWS=24,LW=1.9;
const G=[];for(let i=1;i<=6;i++)G.push(i+'.1',i+'.2');
const SH=[[[1,1,1,1]],[[1,1],[1,1]],[[0,1,0],[1,1,1]],[[0,1,1],[1,1,0]],[[1,1,0],[0,1,1]],[[1,0,0],[1,1,1]],[[0,0,1],[1,1,1]]];
const cv=document.getElementById('c'),cx=cv.getContext('2d'),nv=document.getElementById('nx'),nc=nv.getContext('2d');
const $=id=>document.getElementById(id);
const B=new Path2D('M.56 .06L.24 .56H.45L.38 .94L.74 .4H.52Z');
let cs=22,board,cur,nextT,bag=[],score=0,lines=0,level=1,over=false,paused=false,started=false,acc=0,last=0;
$('d').textContent=new Date().toLocaleDateString('uk-UA',{day:'2-digit',month:'2-digit',year:'2-digit'});

const TH=['auto','light','dark'],TL={auto:'◐ Авто',light:'☀ Світла',dark:'☾ Темна'};
let tm='auto';try{tm=localStorage.getItem('theme')||'auto'}catch(e){}
if(!TL[tm])tm='auto';
function setTheme(){
  const r=document.documentElement;
  tm==='auto'?r.removeAttribute('data-theme'):r.setAttribute('data-theme',tm);
  $('th').textContent=TL[tm];drawNext();
}
$('th').addEventListener('click',()=>{tm=TH[(TH.indexOf(tm)+1)%3];try{localStorage.setItem('theme',tm)}catch(e){}setTheme()});
matchMedia('(prefers-color-scheme:dark)').addEventListener('change',drawNext);
setTheme();

function bolt(c,x,y,s,f,k,g){
  c.save();c.translate(x,y);c.scale(s,s);
  c.fillStyle=f;c.fill(B);c.lineCap='round';
  c.strokeStyle=g;c.lineWidth=.2;c.beginPath();c.moveTo(.18,.14);c.lineTo(.82,.88);c.stroke();
  c.strokeStyle=k;c.lineWidth=.08;c.stroke();c.restore();
}
function hit(m,x,y){
  for(let r=0;r<m.length;r++)for(let c=0;c<m[r].length;c++){
    if(!m[r][c])continue;
    const nx=x+c,ny=y+r;
    if(nx<0||nx>=COLS||ny>=ROWS)return true;
    if(ny>=0&&board[ny][nx])return true;
  }
  return false;
}
const EM_MIN=90000,EM_MAX=150000,EM_WARN=5000;
let emWait=0,emWarn=0,emFlash=0;
const emNext=()=>EM_MIN+Math.random()*(EM_MAX-EM_MIN);
function emergency(){
  const lost=board[0].some(Boolean);
  board.shift();
  const row=Array.from({length:COLS},()=>Math.random()<.8?1:0);
  if(row.every(Boolean))row[Math.random()*COLS|0]=0;
  board.push(row);
  emFlash=1500;
  if(lost){end();return}
  if(hit(cur.m,cur.x,cur.y)){cur.y--;if(hit(cur.m,cur.x,cur.y))end()}
}
function pull(){
  if(!bag.length){bag=[0,1,2,3,4,5,6];for(let i=6;i>0;i--){const j=Math.random()*(i+1)|0;[bag[i],bag[j]]=[bag[j],bag[i]]}}
  return bag.pop();
}
function spawn(){
  const m=SH[nextT].map(r=>r.slice());nextT=pull();
  cur={m,x:(COLS-m[0].length)>>1,y:0};
  drawNext();
  if(hit(cur.m,cur.x,cur.y))end();
}
function reset(){
  board=Array.from({length:ROWS},()=>Array(COLS).fill(0));
  bag=[];nextT=pull();score=0;lines=0;level=1;over=false;paused=false;started=true;acc=0;
  emWait=emNext();emWarn=0;emFlash=0;
  spawn();hud();$('ov').classList.add('h');
}
function hud(){$('sc').textContent=score;$('ln').textContent=lines;$('lv').textContent=level}
function show(t,b){$('ot').textContent=t;$('go').textContent=b;$('ov').classList.remove('h')}
function end(){over=true;emWarn=emFlash=0;show('Світла немає 😅 Бали: '+score,'Ще раз')}
const live=()=>started&&!paused&&!over;
function move(dx){if(live()&&!hit(cur.m,cur.x+dx,cur.y))cur.x+=dx}
function rot(){
  if(!live())return;
  const m=cur.m[0].map((_,i)=>cur.m.map(r=>r[i]).reverse());
  for(const k of [0,-1,1,-2,2])if(!hit(m,cur.x+k,cur.y)){cur.m=m;cur.x+=k;return}
}
function down(manual){
  if(!live())return;
  if(!hit(cur.m,cur.x,cur.y+1)){cur.y++;if(manual)score+=1;hud()}else lock();
}
function drop(){
  if(!live())return;
  while(!hit(cur.m,cur.x,cur.y+1)){cur.y++;score+=2}
  lock();
}
function lock(){
  cur.m.forEach((row,r)=>row.forEach((v,c)=>{if(v&&cur.y+r>=0)board[cur.y+r][cur.x+c]=1}));
  let n=0;
  for(let r=ROWS-1;r>=0;r--)if(board[r].every(Boolean)){board.splice(r,1);board.unshift(Array(COLS).fill(0));n++;r++}
  if(n){lines+=n;score+=[0,100,300,500,800][n]*level;level=1+(lines/10|0)}
  hud();spawn();
}
function pause(){
  if(!started||over)return;
  paused=!paused;
  paused?show('Пауза','Продовжити'):$('ov').classList.add('h');
}
const interval=()=>Math.max(90,800-(level-1)*70);

function fit(){
  const w=innerWidth-20,h=innerHeight-312;
  cs=Math.max(14,Math.min(34,Math.floor(Math.min(w/(COLS+LW),h/(ROWS+1)))));
  const d=devicePixelRatio||1,W=(COLS+LW)*cs,H=(ROWS+1)*cs;
  cv.style.width=W+'px';cv.style.height=H+'px';cv.width=W*d;cv.height=H*d;cx.setTransform(d,0,0,d,0,0);
  nv.style.width='56px';nv.style.height='56px';nv.width=56*d;nv.height=56*d;nc.setTransform(d,0,0,d,0,0);
  drawNext();
}
function colors(){const C=getComputedStyle(document.documentElement);return n=>C.getPropertyValue(n).trim()}
function drawNext(){
  if(nextT==null)return;
  const v=colors(),m=SH[nextT],s=13,ox=(56-m[0].length*s)/2,oy=(56-m.length*s)/2;
  nc.clearRect(0,0,56,56);
  m.forEach((row,r)=>row.forEach((k,c)=>{if(k){nc.fillStyle=v('--gr');nc.fillRect(ox+c*s,oy+r*s,s,s);bolt(nc,ox+c*s,oy+r*s,s,v('--ic'),v('--ic'),v('--gr'))}}));
}
function draw(){
  const v=colors(),W=(COLS+LW)*cs,H=(ROWS+1)*cs,ox=LW*cs,oy=cs;
  cx.fillStyle=v('--card');cx.fillRect(0,0,W,H);
  cx.font='600 '+(cs*.42)+'px system-ui,sans-serif';cx.textAlign='center';cx.textBaseline='middle';cx.fillStyle=v('--mut');
  G.forEach((g,i)=>cx.fillText(g,ox+(i+.5)*cs,oy/2));
  for(let r=0;r<ROWS;r++)cx.fillText(String(r).padStart(2,'0')+'-'+String(r+1).padStart(2,'0'),ox/2,oy+(r+.5)*cs);
  cx.strokeStyle=v('--ln');cx.lineWidth=1;cx.beginPath();
  for(let i=0;i<=COLS;i++){cx.moveTo(ox+i*cs+.5,oy);cx.lineTo(ox+i*cs+.5,oy+ROWS*cs)}
  for(let i=0;i<=ROWS;i++){cx.moveTo(ox,oy+i*cs+.5);cx.lineTo(ox+COLS*cs,oy+i*cs+.5)}
  cx.stroke();
  if(!board)return;
  const ic=v('--ic'),gr=v('--gr');
  for(let r=0;r<ROWS;r++)for(let c=0;c<COLS;c++)if(board[r][c]){
    cx.fillStyle=gr;cx.fillRect(ox+c*cs+1,oy+r*cs+1,cs-1,cs-1);bolt(cx,ox+c*cs,oy+r*cs,cs,ic,ic,gr);
  }
  if(emWarn>0){cx.fillStyle='rgba(255,200,0,'+(.2+.2*Math.sin(performance.now()/120))+')';cx.fillRect(ox,oy+(ROWS-1)*cs,COLS*cs,cs)}
  if(cur&&!over){
    let gy=cur.y;while(!hit(cur.m,cur.x,gy+1))gy++;
    cx.strokeStyle=v('--ye');cx.lineWidth=2;
    cur.m.forEach((row,r)=>row.forEach((k,c)=>{if(k)cx.strokeRect(ox+(cur.x+c)*cs+2,oy+(gy+r)*cs+2,cs-3,cs-3)}));
    cur.m.forEach((row,r)=>row.forEach((k,c)=>{
      if(k){const x=ox+(cur.x+c)*cs,y=oy+(cur.y+r)*cs;cx.fillStyle=gr;cx.fillRect(x+1,y+1,cs-1,cs-1);bolt(cx,x,y,cs,'#f5c400',ic,gr)}
    }));
  }
}
function tick(t){
  requestAnimationFrame(tick);
  const dt=Math.min(t-last,100);last=t;
  if(live()){acc+=dt;if(acc>=interval()){acc=0;down(false)}}
  if(live()){
    if(emFlash>0)emFlash-=dt;
    if(emWarn>0){emWarn-=dt;if(emWarn<=0){emWarn=0;emWait=emNext();emergency()}}
    else{emWait-=dt;if(emWait<=0)emWarn=EM_WARN}
  }
  const wn=$('wn');let txt='';
  if(emWarn>0)txt='⚠ Аварійне відключення через '+Math.ceil(emWarn/1000)+' с';
  else if(emFlash>0)txt='⚡ Аварійне відключення!';
  if(wn.textContent!==txt){wn.textContent=txt;wn.classList.toggle('on',!!txt)}
  draw();
}

addEventListener('keydown',e=>{
  const k=e.key;
  if(k==='ArrowLeft')move(-1);else if(k==='ArrowRight')move(1);else if(k==='ArrowUp')rot();
  else if(k==='ArrowDown')down(true);else if(k===' ')drop();else if(k==='p'||k==='P')pause();else return;
  e.preventDefault();
});
const act={l:()=>move(-1),r:()=>move(1),rot,d:()=>down(true),hd:drop,p:pause};
document.querySelectorAll('.ctl button').forEach(b=>{
  const f=act[b.dataset.a],rep='lrd'.includes(b.dataset.a);let t,iv;
  const stop=()=>{clearTimeout(t);clearInterval(iv)};
  b.addEventListener('pointerdown',e=>{e.preventDefault();f();if(rep){stop();t=setTimeout(()=>{iv=setInterval(f,80)},200)}});
  ['pointerup','pointerleave','pointercancel'].forEach(n=>b.addEventListener(n,stop));
});
$('go').addEventListener('click',()=>{(!started||over)?reset():pause()});
addEventListener('resize',fit);
fit();requestAnimationFrame(tick);
</script>
</body>
</html>
