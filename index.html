<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Smart Water Purification System — Presentation</title>
<style>
:root{
  --bg:#050b16; --bg2:#08132a; --grid:rgba(90,160,255,0.06);
  --edge:#1f3a63; --cyan:#33d6ff; --blue:#4a90ff; --green:#33e29a;
  --amber:#ffb84d; --red:#ff5f6d; --purple:#c07bff; --white:#eaf3ff; --gray:#7f93b3;
}
*{box-sizing:border-box;}
html,body{height:100%;}
body{
  margin:0; background:
    radial-gradient(ellipse at 15% -10%, rgba(51,214,255,0.08), transparent 55%),
    radial-gradient(ellipse at 85% 100%, rgba(74,144,255,0.08), transparent 55%),
    linear-gradient(180deg,var(--bg2),var(--bg));
  color:var(--white); font-family:'Segoe UI',system-ui,-apple-system,sans-serif;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
  display:flex; flex-direction:column; min-height:100%;
}
body::before{content:""; position:fixed; inset:0; z-index:0; pointer-events:none;
  background-image:linear-gradient(var(--grid) 1px,transparent 1px),linear-gradient(90deg,var(--grid) 1px,transparent 1px);
  background-size:38px 38px;}
.wrap{position:relative; z-index:1; max-width:960px; margin:0 auto; width:100%; padding:14px 14px 90px; flex:1;}

header{display:flex; flex-wrap:wrap; justify-content:space-between; gap:10px; margin-bottom:12px;}
h1{margin:0; font-size:1.15rem; letter-spacing:0.4px;}
h1 span{color:var(--cyan);}
.sub{margin:2px 0 0; color:var(--gray); font-size:0.78rem;}

.progress{display:flex; align-items:center; gap:3px; margin-bottom:14px; overflow-x:auto; padding-bottom:4px;}
.pstep{flex:none; width:26px; height:26px; border-radius:50%; border:2px solid var(--edge); display:flex; align-items:center;
  justify-content:center; font-size:0.68rem; font-weight:700; color:var(--gray); cursor:pointer; transition:.25s;}
.pstep.done{border-color:var(--green); color:var(--green); background:rgba(51,226,154,0.08);}
.pstep.active{border-color:var(--cyan); color:var(--cyan); background:rgba(51,214,255,0.12); box-shadow:0 0 12px rgba(51,214,255,0.4);}
.pline{flex:1; height:2px; background:var(--edge); min-width:8px;}
.pline.done{background:var(--green);}

.flow{border:1px solid var(--edge); border-radius:12px; padding:16px 12px;
  background:linear-gradient(180deg,rgba(22,41,77,0.35),rgba(9,17,36,0.5)); margin-bottom:14px;}
.rawline{text-align:center; color:var(--red); font-size:0.72rem; font-weight:600; letter-spacing:0.5px; margin-bottom:8px;}
.snake{display:flex; flex-direction:column;}
.srow{display:flex; align-items:center; justify-content:space-between;}
.srow.rev{flex-direction:row-reverse;}
.turn{width:100%; display:flex; padding:2px 0;}
.turn.right{justify-content:flex-end;}
.turn.left{justify-content:flex-start;}
.turn-pipe{width:20px; height:24px; position:relative;}
.turn-pipe .barrel{position:absolute; left:5px; top:0; width:10px; height:24px; border-radius:3px;
  background:rgba(31,58,99,0.5); border:1px solid var(--edge); overflow:hidden;}
.turn-pipe .fill{position:absolute; left:0; bottom:0; width:100%; height:0%; background:linear-gradient(180deg,var(--cyan),var(--blue)); transition:height .3s;}
.turn-pipe.on .barrel{border-color:var(--cyan); box-shadow:0 0 10px rgba(51,214,255,0.25);}
.turn-pipe.on .fill{height:100%;}

.hpipe{flex:none; width:22px; height:10px; position:relative; margin:0 4px;}
.hpipe .barrel{position:absolute; top:1px; left:0; width:100%; height:8px; border-radius:3px;
  background:rgba(31,58,99,0.5); border:1px solid var(--edge); overflow:hidden;}
.hpipe .fill{position:absolute; top:0; left:0; height:100%; width:0%; background:linear-gradient(90deg,var(--cyan),var(--blue)); transition:width .3s;}
.hpipe.on .barrel{border-color:var(--cyan); box-shadow:0 0 10px rgba(51,214,255,0.25);}
.hpipe.on .fill{width:100%;}
.srow.rev .hpipe .fill{background:linear-gradient(270deg,var(--cyan),var(--blue));}

.tank{flex:1; min-width:0; position:relative; text-align:center; padding-top:14px;}
.tank-badge{position:absolute; top:-6px; left:8px; width:26px; height:26px; border-radius:50%; background:var(--bg2);
  border:2px solid var(--edge); display:flex; align-items:center; justify-content:center; font-size:0.75rem; font-weight:700;
  color:var(--gray); z-index:2;}
.tank-badge.done{border-color:var(--green); color:var(--green); background:rgba(51,226,154,0.12);}
.tank-badge.active{border-color:var(--cyan); color:var(--cyan); background:rgba(51,214,255,0.15); box-shadow:0 0 10px rgba(51,214,255,0.5);}
.vessel{border:1px solid var(--edge); border-radius:8px; background:rgba(0,0,0,0.2); padding:8px 6px 10px; opacity:0.55; transition:.25s; cursor:pointer;}
.tank.done .vessel{opacity:1; border-color:var(--green);}
.tank.active .vessel{opacity:1; border-color:var(--cyan); box-shadow:0 0 18px rgba(51,214,255,0.18); background:rgba(51,214,255,0.06);}
.liquid{height:26px; border-radius:5px; background:#5a3a1e; margin:0 auto 6px; position:relative; overflow:hidden; border:1px solid rgba(0,0,0,0.3); transition:background .4s;}
.liquid::after{content:""; position:absolute; inset:0; background:linear-gradient(180deg,rgba(255,255,255,0.12),transparent 40%);}
.tname{font-size:0.86rem; font-weight:700; line-height:1.25;}
.tstatus{font-size:0.68rem; color:var(--gray); margin-top:3px;}
.tank.active .tstatus{color:var(--cyan);} .tank.done .tstatus{color:var(--green);}

.outrow{display:flex; justify-content:center; margin-top:2px;}
.outline{text-align:center; color:var(--green); font-size:0.8rem; font-weight:700; letter-spacing:0.5px; margin-top:6px; opacity:0.4;}
.outline.on{opacity:1; text-shadow:0 0 10px rgba(51,226,154,0.5);}

.panel{border:1px solid var(--edge); border-radius:10px; padding:16px 18px;
  background:linear-gradient(180deg,rgba(22,41,77,0.5),rgba(9,17,36,0.6));}
.panel-top{display:flex; align-items:flex-start; gap:14px;}
.panel .num{font-size:1.8rem; font-weight:800; color:var(--cyan); line-height:1;}
.panel h2{margin:0; font-size:1.05rem;}
.panel .tagline{margin:2px 0 0; color:var(--gray); font-size:0.8rem;}
.sec{margin-top:12px;}
.sec .lbl{color:var(--cyan); font-size:0.72rem; font-weight:700; letter-spacing:0.3px; margin-bottom:3px;}
.sec p{margin:0; color:var(--white); font-size:0.85rem; line-height:1.5;}
.afterrow{display:flex; align-items:center; gap:10px;}
.swatch{width:26px; height:26px; border-radius:50%; flex:none; border:2px solid rgba(255,255,255,0.15);}
.params{display:grid; grid-template-columns:repeat(auto-fit,minmax(100px,1fr)); gap:6px; margin-top:12px;}
.param{background:rgba(0,0,0,0.2); border:1px solid var(--edge); border-radius:6px; padding:5px 8px;}
.param .l{font-size:0.58rem; color:var(--gray);}
.param .v{font-size:0.78rem; font-weight:600; margin-top:1px;}
.v.red{color:var(--red);} .v.amber{color:var(--amber);} .v.green{color:var(--green);} .v.cyan{color:var(--cyan);} .v.purple{color:var(--purple);}

.controls{position:sticky; bottom:0; left:0; right:0; margin-top:14px;
  padding:10px 0 calc(10px + env(safe-area-inset-bottom,0px));
  background:linear-gradient(180deg,transparent,rgba(5,11,22,0.92) 25%);}
.crow{display:flex; gap:8px; justify-content:center; flex-wrap:wrap;}
button{font-family:inherit; cursor:pointer; border-radius:9px; font-size:0.82rem; padding:10px 16px; border:1px solid var(--edge); background:transparent; color:var(--gray);}
button.act{background:linear-gradient(180deg,var(--cyan),var(--blue)); border:none; color:#03121f; font-weight:700;}
button.act:disabled{opacity:0.35; cursor:default;}
button:hover:not(:disabled){color:var(--cyan); border-color:var(--cyan);}
.stageline{text-align:center; font-size:0.75rem; color:var(--gray); margin-top:8px;}
.barwrap{height:4px; background:var(--edge); border-radius:2px; margin-top:6px; overflow:hidden;}
.bar{height:100%; background:var(--cyan); width:0%; transition:width .3s;}
.note{text-align:center; font-size:0.65rem; color:var(--gray); margin-top:10px;}
</style>
</head>
<body>
<div class="wrap">
  <header>
    <div>
      <h1>SMART <span>WATER</span> PURIFICATION SYSTEM</h1>
      <p class="sub">Rural &amp; Mining-Affected Water Treatment — Presentation Mode</p>
    </div>
  </header>

  <div class="progress" id="progress"></div>

  <div class="flow">
    <div class="rawline">RAW CONTAMINATED WATER — TURBIDITY 480 NTU · pH 5.8 · TDS 1850 ppm</div>
    <div class="turn" style="justify-content:center;">
      <div class="turn-pipe" id="pipe0"><div class="barrel"><div class="fill"></div></div></div>
    </div>
    <div class="snake" id="snake"></div>
    <div class="outrow">
      <div class="turn-pipe" id="pipeOut"><div class="barrel"><div class="fill"></div></div></div>
    </div>
    <div class="outline" id="outline">PURIFIED WATER OUTPUT</div>
  </div>

  <div class="panel" id="panel">
    <div class="panel-top">
      <div class="num" id="pNum">—</div>
      <div>
        <h2 id="pName">Ready to begin</h2>
        <p class="tagline" id="pTag">Press "Next Stage" to walk the judges through Stage 1.</p>
      </div>
    </div>
    <div id="pBody"></div>
  </div>

  <div class="controls">
    <div class="crow">
      <button id="prevBtn">◀ Prev</button>
      <button id="resetBtn">⟲ Restart</button>
      <button class="act" id="nextBtn">Next ▶</button>
    </div>
    <p class="stageline" id="stageline">Stage 0 of 9</p>
    <div class="barwrap"><div class="bar" id="bar"></div></div>
  </div>
  <p class="note">Illustrative simulation for Smart India Hackathon presentation. Parameter values are indicative process indices, not certified lab measurements.</p>
</div>

<script>
const stages = [
  {name:"EQUALIZATION TANK", tag:"Steadies incoming flow", water:"#6b4423",
   happens:"Water arriving from the village or mine site doesn't come in at a steady rate, and its dirt level keeps changing too. This tank holds and gently mixes it so the flow and contamination level are steady by the time treatment begins.",
   removed:"Nothing yet — this stage doesn't remove contaminants, it just makes the water consistent for every stage that follows.",
   after:"Still muddy and cloudy, but now flowing at a steady, predictable rate.",
   params:[["FLOW RATE","1200 L/hr","cyan"],["TURBIDITY","480 NTU","red"],["pH","5.8","amber"],["CONTAMINATION","HIGH","red"]]},
  {name:"SCREENING", tag:"Removes large debris", water:"#6b4423",
   happens:"The water passes through a metal screen or grate. Anything large — leaves, plastic bits, stones — gets physically blocked, like a kitchen sieve catching the big pieces first.",
   removed:"Large floating and suspended debris that could clog or damage equipment further down the line.",
   after:"Still cloudy, but free of visible large debris.",
   params:[["LARGE DEBRIS","REMOVED","green"],["TURBIDITY","REDUCING","amber"],["FLOW","STABLE","cyan"]]},
  {name:"MULTI-MEDIA/S AND FILTER", tag:"Filters fine particles", water:"#7a5a35",
   happens:"Water travels down through a tall column packed with layers of filter media — coarse on top, fine below. Tiny suspended particles get trapped one size at a time as the water works its way down.",
   removed:"Fine suspended solids that make the water look cloudy.",
   after:"Noticeably clearer, though still tinted and not yet chemically treated.",
   params:[["SUSPENDED SOLIDS","HIGH → LOW","amber"],["TURBIDITY","420 → 95 NTU","cyan"],["FILTER STATUS","NORMAL","green"]]},
  {name:"COAGULATION", tag:"Prepares particles to clump", water:"#8a6a45",
   happens:"A chemical called a coagulant is mixed in quickly. It neutralizes the charge that keeps tiny particles pushing each other apart, so they're free to start sticking together instead.",
   removed:"Nothing is removed here — this step sets up the next stage to work.",
   after:"Looks the same for now, but particles inside are no longer repelling each other.",
   params:[["COAGULANT DOSE","32 mg/L","amber"],["MIXING","RAPID","cyan"],["PARTICLE CHARGE","NEUTRALIZING","purple"]]},
  {name:"FLOCCULATION", tag:"Grows particle clumps", water:"#8a6a45",
   happens:"The water is stirred slowly and gently, encouraging the freed particles to bump into each other and build up into bigger, heavier clumps called flocs. Fast mixing here would break the clumps apart, so the motion stays slow.",
   removed:"Nothing yet — it's turning invisible particles into visible clumps ready for the next stage.",
   after:"Visible small clumps are now forming and beginning to sink.",
   params:[["FLOC SIZE","GROWING","purple"],["MIXING","SLOW","cyan"],["TURBIDITY","95 → 40 NTU","green"]]},
  {name:"CHEMICAL PRECIPITATION", tag:"Targets dissolved heavy metals", water:"#5c6270",
   happens:"Chemicals are added that react with heavy metals dissolved invisibly in the water — the kind no filter can catch. The reaction converts them into solid particles, which sink to the bottom as sludge.",
   removed:"Dissolved heavy metals, now converted to solid sludge and separated out.",
   after:"Free of dissolved heavy metals; sludge has settled to the bottom.",
   params:[["HEAVY METALS","PRECIPITATING","amber"],["SLUDGE","SETTLING","amber"],["TDS","1850 → 1120 ppm","cyan"]]},
  {name:"ACTIVATED CARBON", tag:"Adsorbs organics and odour", water:"#4a5a68",
   happens:"Water flows through a bed of activated carbon — a material full of microscopic pores that acts like a sponge, trapping dissolved organic matter and smells as the water passes through.",
   removed:"Dissolved organic matter, odours and trace leftover chemicals.",
   after:"Fresher, clearer, and free of any unpleasant smell.",
   params:[["ORGANICS","ADSORBING","green"],["ODOUR","REDUCING","green"],["FILTER STATUS","NORMAL","green"]]},
  {name:"REVERSE OSMOSIS", tag:"Deep-cleans at membrane level", water:"#2e6070",
   happens:"Water is pushed under high pressure through a membrane with pores so fine that even dissolved salts and trace metals can't pass through — only water molecules make it to the other side.",
   removed:"Remaining dissolved salts, minerals and trace metals, diverted away as a separate reject stream.",
   after:"The biggest jump in clarity and purity of any stage — close to the final result.",
   params:[["MEMBRANE PRESSURE","HIGH","amber"],["TDS","1120 → 180 ppm","green"],["REJECT STREAM","DIVERTED","red"]]},
  {name:"pH SENSING", tag:"Final quality checkpoint", water:"#2f8fb0",
   happens:"A digital sensor chamber checks the water's pH, total dissolved solids and other key readings in real time before release.",
   removed:"Nothing — this step checks quality, it doesn't treat the water further.",
   after:"Confirmed clear, balanced, and within safe limits — ready for release.",
   params:[["pH","5.8 → 7.1","green"],["TDS","180 ppm","green"],["MONITORING","LIVE","purple"]]},
];
const N = stages.length;
let current = -1, maxReached = -1;

const progressEl = document.getElementById('progress');
stages.forEach((s,i)=>{
  const d = document.createElement('div'); d.className='pstep'; d.id='pstep'+i; d.textContent=i+1; d.title=s.name;
  d.addEventListener('click', ()=>{ if(i<=maxReached+1) goTo(i); });
  progressEl.appendChild(d);
  if(i<N-1){ const l=document.createElement('div'); l.className='pline'; l.id='pline'+i; progressEl.appendChild(l); }
});

const snakeEl = document.getElementById('snake');
const perRow = 3;
for(let r=0; r*perRow < N; r++){
  const rowIdx = [];
  for(let c=0;c<perRow;c++){ const idx=r*perRow+c; if(idx<N) rowIdx.push(idx); }
  const row = document.createElement('div');
  row.className = 'srow' + (r%2===1 ? ' rev' : '');
  rowIdx.forEach((idx,ci)=>{
    const tank = document.createElement('div');
    tank.className='tank'; tank.id='tank'+idx;
    tank.innerHTML = '<div class="tank-badge" id="badge'+idx+'">'+(idx+1)+'</div>'+
      '<div class="vessel"><div class="liquid" id="liquid'+idx+'" style="background:#3a3a3a"></div>'+
      '<div class="tname">'+stages[idx].name+'</div><div class="tstatus" id="tst'+idx+'">PENDING</div></div>';
    tank.addEventListener('click', ()=>{ if(idx<=maxReached+1) goTo(idx); });
    row.appendChild(tank);
    if(ci < rowIdx.length-1){
      const hp = document.createElement('div'); hp.className='hpipe'; hp.id='hpipe'+idx;
      hp.innerHTML='<div class="barrel"><div class="fill"></div></div>';
      row.appendChild(hp);
    }
  });
  snakeEl.appendChild(row);
  if((r+1)*perRow < N){
    const goingRightSide = (r%2===0);
    const turn = document.createElement('div');
    turn.className = 'turn ' + (goingRightSide ? 'right' : 'left');
    turn.id = 'turnrow'+r;
    turn.innerHTML = '<div class="turn-pipe" id="turnpipe'+r+'"><div class="barrel"><div class="fill"></div></div></div>';
    snakeEl.appendChild(turn);
  }
}

const pNum=document.getElementById('pNum'), pName=document.getElementById('pName'), pTag=document.getElementById('pTag'), pBody=document.getElementById('pBody');
const prevBtn=document.getElementById('prevBtn'), nextBtn=document.getElementById('nextBtn'), resetBtn=document.getElementById('resetBtn');
const pipe0=document.getElementById('pipe0'), pipeOut=document.getElementById('pipeOut'), outline=document.getElementById('outline');
const stageline=document.getElementById('stageline'), bar=document.getElementById('bar');

function render(){
  for(let i=0;i<N;i++){
    const tank=document.getElementById('tank'+i), badge=document.getElementById('badge'+i), tst=document.getElementById('tst'+i);
    const liquid=document.getElementById('liquid'+i), pstep=document.getElementById('pstep'+i);
    tank.classList.remove('active','done'); badge.classList.remove('active','done'); pstep.classList.remove('active','done');
    if(i < current){ tank.classList.add('done'); badge.classList.add('done'); tst.textContent='✓ DONE'; liquid.style.background=stages[i].water; pstep.classList.add('done'); pstep.textContent='✓'; }
    else if(i === current){ tank.classList.add('active'); badge.classList.add('active'); tst.textContent='ACTIVE'; liquid.style.background=stages[i].water; pstep.classList.add('active'); pstep.textContent=i+1; }
    else { tst.textContent='PENDING'; liquid.style.background='#3a3a3a'; pstep.textContent=i+1; }
    const hp=document.getElementById('hpipe'+i); if(hp) hp.classList.toggle('on', i<current);
    if(i<N-1) document.getElementById('pline'+i).classList.toggle('done', i<current);
  }
  for(let r=0; r*perRow < N; r++){
    const tp = document.getElementById('turnpipe'+r);
    if(tp){ const lastIdxOfRow = Math.min((r+1)*perRow, N)-1; tp.classList.toggle('on', current > lastIdxOfRow); }
  }
  pipe0.classList.toggle('on', current>=0);
  pipeOut.classList.toggle('on', current>=N);
  outline.classList.toggle('on', current>=N);

  if(current===-1){
    pNum.textContent='—'; pName.textContent='Ready to begin'; pTag.textContent='Press "Next" to walk through Stage 1.'; pBody.innerHTML='';
  } else if(current<N){
    const s=stages[current];
    pNum.textContent=String(current+1).padStart(2,'0');
    pName.textContent=s.name; pTag.textContent=s.tag;
    pBody.innerHTML =
      '<div class="sec"><div class="lbl">WHAT HAPPENS</div><p>'+s.happens+'</p></div>'+
      '<div class="sec"><div class="lbl">WHAT IS REMOVED</div><p>'+s.removed+'</p></div>'+
      '<div class="sec"><div class="lbl">WATER AFTERWARD</div><div class="afterrow"><div class="swatch" style="background:'+s.water+'"></div><p>'+s.after+'</p></div></div>'+
      '<div class="params">'+s.params.map(function(p){return '<div class="param"><div class="l">'+p[0]+'</div><div class="v '+p[2]+'">'+p[1]+'</div></div>';}).join('')+'</div>';
  } else {
    pNum.textContent='✓'; pName.textContent='PURIFIED WATER OUTPUT'; pTag.textContent='All nine stages complete';
    pBody.innerHTML = '<div class="sec"><p>Treated water meets the indicative quality targets for this demonstration.</p></div>'+
      '<div class="params">'+
        '<div class="param"><div class="l">TURBIDITY</div><div class="v green">&lt; 1 NTU</div></div>'+
        '<div class="param"><div class="l">pH</div><div class="v green">7.1</div></div>'+
        '<div class="param"><div class="l">TDS</div><div class="v green">180 ppm</div></div>'+
      '</div>';
  }
  prevBtn.disabled = current<=-1;
  nextBtn.disabled = current>=N;
  nextBtn.textContent = current>=N ? 'Complete' : (current===N-1 ? 'Show Output ▶' : 'Next ▶');
  const shown = Math.max(current+1,0);
  stageline.textContent = 'Stage '+shown+' of '+N;
  bar.style.width = (Math.min(shown,N)/N*100)+'%';
}
function goTo(i){ current=i; if(current>maxReached) maxReached=current; render(); }
nextBtn.addEventListener('click', function(){ if(current<N) goTo(current+1); });
prevBtn.addEventListener('click', function(){ if(current>-1) goTo(current-1); });
resetBtn.addEventListener('click', function(){ current=-1; maxReached=-1; render(); });
render();
</script>
</body>
</html>
