<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JLPT 考古題練習</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@300;400;500&family=Noto+Serif+TC:wght@300;400&family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300&display=swap" rel="stylesheet">
<style>
:root {
  --bg:       #f5f3ef;
  --surface:  #edeae4;
  --card:     #faf9f6;
  --border:   #dcd8d0;
  --muted:    #b8b2a7;
  --body:     #5c5650;
  --heading:  #3a3530;
  --accent:   #8c7b6b;
  --accent2:  #7a8c7b;
  --danger:   #a06060;
  --shadow:   rgba(58,53,48,0.08);
  --n3bg: rgba(196,180,154,.15);
  --n2bg: rgba(154,171,180,.15);
  --n1bg: rgba(164,154,180,.15);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  background:var(--bg);color:var(--body);
  font-family:'Noto Serif TC','Noto Serif JP',serif;
  font-weight:300;line-height:1.9;min-height:100vh;
}

/* NAV */
nav{
  position:sticky;top:0;z-index:100;
  background:rgba(245,243,239,.92);backdrop-filter:blur(8px);
  border-bottom:1px solid var(--border);
  display:flex;align-items:center;justify-content:space-between;
  padding:.9rem 2rem;
}
.nav-logo{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:1rem;color:var(--heading);letter-spacing:.1em;
}
.nav-tabs{display:flex;gap:.3rem;}
.nav-tab{
  border:none;background:transparent;
  font-family:inherit;font-size:.75rem;letter-spacing:.12em;
  color:var(--muted);cursor:pointer;
  padding:.4rem .9rem;border-radius:100px;transition:all .2s;
}
.nav-tab.active{background:var(--heading);color:var(--bg);}

/* LAYOUT */
.page{display:none;max-width:780px;margin:0 auto;padding:3rem 2rem 6rem;}
.page.active{display:block;}
.section-label{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:.72rem;letter-spacing:.3em;text-transform:uppercase;
  color:var(--muted);margin-bottom:1.8rem;
  display:flex;align-items:center;gap:1rem;
}
.section-label::after{content:'';flex:1;height:1px;background:var(--border);}

/* BUTTONS */
.btn{
  border:none;border-radius:3px;
  font-family:inherit;font-size:.78rem;letter-spacing:.1em;
  cursor:pointer;transition:all .18s;display:inline-flex;
  align-items:center;gap:.4rem;padding:.55rem 1.2rem;
}
.btn-primary{background:var(--heading);color:var(--bg);}
.btn-primary:hover{background:#2a2520;}
.btn-ghost{background:transparent;border:1px solid var(--border);color:var(--body);}
.btn-ghost:hover{border-color:var(--accent);color:var(--accent);}
.btn-danger{background:transparent;border:1px solid var(--border);color:var(--danger);}
.btn-danger:hover{background:rgba(160,96,96,.08);}
.btn-sm{padding:.3rem .75rem;font-size:.7rem;}

/* BADGES */
.badge{
  display:inline-block;font-size:.65rem;letter-spacing:.12em;
  padding:.15rem .55rem;border-radius:100px;
  font-family:'Cormorant Garamond',serif;font-style:italic;
}
.badge.n3{background:var(--n3bg);color:#7a6a50;}
.badge.n2{background:var(--n2bg);color:#4a6070;}
.badge.n1{background:var(--n1bg);color:#5a4a70;}
.type-chip{
  display:inline-block;font-size:.65rem;letter-spacing:.08em;
  padding:.12rem .5rem;border-radius:2px;
  background:var(--surface);color:var(--muted);
  font-family:'Cormorant Garamond',serif;font-style:italic;
}

/* ── QUIZ ── */
.quiz-filters{display:flex;gap:.5rem;flex-wrap:wrap;margin-bottom:2rem;align-items:center;}
.filter-pill{
  border:1px solid var(--border);background:transparent;
  border-radius:100px;padding:.3rem .8rem;
  font-size:.72rem;font-family:inherit;color:var(--muted);
  cursor:pointer;transition:all .2s;letter-spacing:.08em;
}
.filter-pill.active{background:var(--heading);border-color:var(--heading);color:var(--bg);}
.quiz-meta{
  display:flex;align-items:center;justify-content:space-between;
  margin-bottom:1.5rem;flex-wrap:wrap;gap:.5rem;
}
.quiz-counter{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:.82rem;color:var(--muted);
}
.progress-bar{width:100%;height:2px;background:var(--border);border-radius:1px;margin-bottom:2rem;overflow:hidden;}
.progress-fill{height:100%;background:var(--accent);transition:width .4s ease;border-radius:1px;}

/* Question Card */
.q-card{
  background:var(--card);border:1px solid var(--border);
  border-radius:4px;padding:2.2rem 2.5rem;
  box-shadow:0 2px 20px var(--shadow);margin-bottom:1.2rem;
  animation:fadeUp .3s ease;
}
@keyframes fadeUp{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
.q-header{display:flex;align-items:flex-start;gap:.8rem;margin-bottom:1.6rem;flex-wrap:wrap;}
.q-number{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:.8rem;color:var(--muted);white-space:nowrap;margin-top:.15rem;
}
.q-passage{
  background:var(--surface);border-left:2px solid var(--border);
  padding:1rem 1.3rem;margin-bottom:1.5rem;
  font-family:'Noto Serif JP',serif;font-size:.92rem;
  line-height:2.1;color:var(--heading);border-radius:0 3px 3px 0;
}
.q-stem{
  font-family:'Noto Serif JP',serif;font-size:1.05rem;
  line-height:1.9;color:var(--heading);margin-bottom:1.5rem;letter-spacing:.04em;
}
.q-blank{
  display:inline-block;min-width:3em;border-bottom:1.5px solid var(--heading);
  text-align:center;margin:0 .2em;vertical-align:bottom;
}
.options{display:flex;flex-direction:column;gap:.65rem;}
.option{
  border:1px solid var(--border);border-radius:3px;
  padding:.8rem 1.1rem;cursor:pointer;
  display:flex;align-items:flex-start;gap:.8rem;
  transition:all .2s;background:var(--card);
  font-family:'Noto Serif JP',serif;font-size:.9rem;
  color:var(--heading);line-height:1.7;
}
.option:hover:not(.locked){border-color:var(--accent);background:rgba(140,123,107,.04);}
.option.correct{border-color:var(--accent2)!important;background:rgba(122,140,123,.08)!important;}
.option.wrong{border-color:var(--danger)!important;background:rgba(160,96,96,.06)!important;}
.option.reveal-correct{border-color:var(--accent2)!important;background:rgba(122,140,123,.04)!important;}
.opt-label{
  min-width:1.4rem;height:1.4rem;border-radius:50%;
  background:var(--surface);display:flex;align-items:center;justify-content:center;
  font-size:.68rem;color:var(--muted);flex-shrink:0;margin-top:.1rem;
  font-family:'Cormorant Garamond',serif;font-style:italic;transition:all .2s;
}
.option.correct .opt-label{background:var(--accent2);color:#fff;}
.option.wrong   .opt-label{background:var(--danger);color:#fff;}
.explanation{
  margin-top:1.2rem;padding:1.3rem 1.5rem;
  background:var(--surface);border-radius:3px;
  font-size:.82rem;line-height:1.95;color:var(--body);
  animation:fadeUp .25s ease;
}
.exp-verdict{
  font-family:'Noto Serif JP',serif;font-size:.9rem;
  color:var(--heading);margin-bottom:.8rem;
  padding-bottom:.8rem;border-bottom:1px solid var(--border);
}
.exp-verdict .correct-mark{color:var(--accent2);}
.exp-verdict .wrong-mark{color:var(--danger);}
.exp-key{
  display:inline;background:rgba(140,123,107,.12);
  padding:.1rem .3rem;border-radius:2px;
  font-family:'Noto Serif JP',serif;color:var(--heading);font-size:.95em;
}
.explanation p+p{margin-top:.6rem;}
.q-actions{display:flex;gap:.7rem;margin-top:1.5rem;flex-wrap:wrap;}
.empty-state{
  text-align:center;padding:4rem 2rem;color:var(--muted);
  font-family:'Cormorant Garamond',serif;font-style:italic;font-size:1rem;letter-spacing:.1em;
}
.score-card{
  background:var(--card);border:1px solid var(--border);
  border-radius:4px;padding:3rem;text-align:center;
  box-shadow:0 2px 20px var(--shadow);animation:fadeUp .3s ease;
}
.score-big{font-family:'Cormorant Garamond',serif;font-size:4rem;color:var(--heading);line-height:1;margin-bottom:.5rem;}
.score-label{font-size:.78rem;color:var(--muted);letter-spacing:.15em;margin-bottom:2rem;}
.score-breakdown{display:flex;justify-content:center;gap:2rem;margin-bottom:2rem;flex-wrap:wrap;}
.score-item{text-align:center;}
.score-item-num{font-size:1.4rem;color:var(--heading);font-family:'Cormorant Garamond',serif;}
.score-item-label{font-size:.7rem;color:var(--muted);letter-spacing:.1em;}

/* ── ADMIN ── */
.admin-toolbar{display:flex;gap:.7rem;margin-bottom:2rem;flex-wrap:wrap;align-items:center;}
.admin-toolbar .spacer{flex:1;}
.q-list{display:flex;flex-direction:column;gap:.8rem;margin-bottom:2rem;}
.q-list-item{
  background:var(--card);border:1px solid var(--border);
  border-radius:3px;padding:1rem 1.3rem;
  display:flex;align-items:flex-start;gap:1rem;transition:border-color .2s;
}
.q-list-item:hover{border-color:var(--muted);}
.q-list-body{flex:1;min-width:0;}
.q-list-stem{
  font-family:'Noto Serif JP',serif;font-size:.88rem;color:var(--heading);
  line-height:1.7;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;
}
.q-list-tags{display:flex;gap:.4rem;margin-top:.4rem;flex-wrap:wrap;}
.q-list-actions{display:flex;gap:.4rem;flex-shrink:0;}

/* MODAL */
.modal-overlay{
  position:fixed;inset:0;background:rgba(58,53,48,.45);
  backdrop-filter:blur(3px);z-index:500;
  display:flex;align-items:center;justify-content:center;padding:1rem;
}
.modal-overlay.hidden{display:none;}
.modal{
  background:var(--card);border:1px solid var(--border);
  border-radius:4px;width:100%;max-width:620px;max-height:90vh;
  overflow-y:auto;box-shadow:0 8px 40px rgba(58,53,48,.18);animation:fadeUp .25s ease;
}
.modal-header{
  padding:1.3rem 1.8rem;border-bottom:1px solid var(--border);
  display:flex;align-items:center;justify-content:space-between;
}
.modal-title{font-family:'Cormorant Garamond',serif;font-size:1.05rem;color:var(--heading);letter-spacing:.08em;}
.modal-close{
  border:none;background:transparent;font-size:1.1rem;color:var(--muted);
  cursor:pointer;line-height:1;padding:.2rem .4rem;border-radius:2px;transition:color .2s;
}
.modal-close:hover{color:var(--heading);}
.modal-body{padding:1.5rem 1.8rem;}
.modal-footer{padding:1rem 1.8rem;border-top:1px solid var(--border);display:flex;justify-content:flex-end;gap:.7rem;}
.form-row{margin-bottom:1.2rem;}
.form-label{
  display:block;font-size:.72rem;letter-spacing:.12em;color:var(--muted);
  margin-bottom:.45rem;font-family:'Cormorant Garamond',serif;font-style:italic;
}
.form-input,.form-select,.form-textarea{
  width:100%;border:1px solid var(--border);border-radius:3px;
  padding:.6rem .85rem;font-family:'Noto Serif JP','Noto Serif TC',serif;
  font-size:.85rem;color:var(--heading);background:var(--bg);
  transition:border-color .2s;outline:none;
}
.form-input:focus,.form-select:focus,.form-textarea:focus{border-color:var(--accent);}
.form-textarea{resize:vertical;min-height:70px;line-height:1.8;}
.form-row-2{display:grid;grid-template-columns:1fr 1fr;gap:1rem;}
@media(max-width:480px){.form-row-2{grid-template-columns:1fr;}}
.option-inputs{display:flex;flex-direction:column;gap:.5rem;}
.option-input-row{display:flex;gap:.5rem;align-items:center;}
.opt-indicator{
  min-width:1.6rem;height:1.6rem;border-radius:50%;
  background:var(--surface);border:1px solid var(--border);
  display:flex;align-items:center;justify-content:center;
  font-size:.65rem;color:var(--muted);flex-shrink:0;
  font-family:'Cormorant Garamond',serif;font-style:italic;
  cursor:pointer;transition:all .2s;
}
.opt-indicator.correct-opt{background:var(--accent2);border-color:var(--accent2);color:#fff;}
.correct-hint{font-size:.68rem;color:var(--muted);margin-top:.4rem;font-style:italic;}
.code-area{
  width:100%;font-family:monospace;font-size:.75rem;
  border:1px solid var(--border);border-radius:3px;
  padding:.8rem;background:var(--surface);color:var(--body);
  min-height:120px;resize:vertical;outline:none;
}
.code-area:focus{border-color:var(--accent);}
</style>
</head>
<body>

<nav>
  <div class="nav-logo">JLPT 練習帳</div>
  <div class="nav-tabs">
    <button class="nav-tab active" data-page="quiz">練習</button>
    <button class="nav-tab" data-page="admin">題庫管理</button>
  </div>
</nav>

<!-- QUIZ PAGE -->
<div class="page active" id="page-quiz">
  <div class="section-label">考古題練習</div>
  <div class="quiz-filters" id="quizFilters">
    <button class="filter-pill active" data-filter="all">全部</button>
    <button class="filter-pill" data-filter="n3">N3</button>
    <button class="filter-pill" data-filter="n2">N2</button>
    <button class="filter-pill" data-filter="n1">N1</button>
    <button class="filter-pill" data-filter="文字語彙">文字・語彙</button>
    <button class="filter-pill" data-filter="文法">文法</button>
    <button class="filter-pill" data-filter="読解">読解</button>
  </div>
  <div id="quizArea"></div>
</div>

<!-- ADMIN PAGE -->
<div class="page" id="page-admin">
  <div class="section-label">題庫管理</div>
  <div class="admin-toolbar">
    <button class="btn btn-primary" id="btnAddQ">＋ 新增題目</button>
    <div class="spacer"></div>
    <button class="btn btn-ghost btn-sm" id="btnExport">匯出 JSON</button>
    <button class="btn btn-ghost btn-sm" id="btnImport">匯入 JSON</button>
  </div>
  <div class="q-list" id="qList"></div>
</div>

<!-- MODAL: Add/Edit -->
<div class="modal-overlay hidden" id="modalOverlay">
  <div class="modal">
    <div class="modal-header">
      <span class="modal-title" id="modalTitle">新增題目</span>
      <button class="modal-close" id="modalClose">✕</button>
    </div>
    <div class="modal-body">
      <div class="form-row-2">
        <div class="form-row">
          <label class="form-label">等級 Level</label>
          <select class="form-select" id="fLevel">
            <option value="n3">N3</option>
            <option value="n2" selected>N2</option>
            <option value="n1">N1</option>
          </select>
        </div>
        <div class="form-row">
          <label class="form-label">題型 Type</label>
          <select class="form-select" id="fType">
            <option value="文字語彙">文字・語彙</option>
            <option value="文法" selected>文法</option>
            <option value="読解">読解</option>
          </select>
        </div>
      </div>
      <div class="form-row" id="passageRow" style="display:none">
        <label class="form-label">文章段落（読解用）</label>
        <textarea class="form-textarea" id="fPassage" placeholder="貼入閱讀文章段落…" rows="4"></textarea>
      </div>
      <div class="form-row">
        <label class="form-label">題幹 Question Stem</label>
        <textarea class="form-textarea" id="fStem" placeholder="例：（　　）に入る最もよいものを選んでください。" rows="2"></textarea>
      </div>
      <div class="form-row">
        <label class="form-label">選項（點擊圓圈標記正解）</label>
        <div class="option-inputs" id="optionInputs"></div>
        <div class="correct-hint">↑ 點擊左側圓圈 = 設為正解</div>
      </div>
      <div class="form-row">
        <label class="form-label">解析 Explanation</label>
        <textarea class="form-textarea" id="fExplanation" placeholder="解析正確答案的文法・語感要點…" rows="3"></textarea>
      </div>
      <div class="form-row">
        <label class="form-label">來源 Source（選填）</label>
        <input class="form-input" id="fSource" type="text" placeholder="例：JLPT 2019 N2 第三回">
      </div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" id="btnCancel">取消</button>
      <button class="btn btn-primary" id="btnSave">儲存題目</button>
    </div>
  </div>
</div>

<!-- MODAL: Import -->
<div class="modal-overlay hidden" id="importOverlay">
  <div class="modal">
    <div class="modal-header">
      <span class="modal-title">匯入 JSON</span>
      <button class="modal-close" id="importClose">✕</button>
    </div>
    <div class="modal-body">
      <div class="form-row">
        <label class="form-label">貼上 JSON 資料（陣列格式）</label>
        <textarea class="code-area" id="importText" placeholder='[{"level":"n2","type":"文法","stem":"…","options":["A","B","C","D"],"answer":0,"explanation":"…"}]'></textarea>
      </div>
    </div>
    <div class="modal-footer">
      <button class="btn btn-ghost" id="importCancel">取消</button>
      <button class="btn btn-primary" id="importConfirm">匯入</button>
    </div>
  </div>
</div>

<script>
// ── Storage ──
const STORE_KEY = 'jlpt_questions';
function loadQ(){ try{ return JSON.parse(localStorage.getItem(STORE_KEY))||[]; }catch{ return []; } }
function saveQ(qs){ localStorage.setItem(STORE_KEY, JSON.stringify(qs)); }
function uid(){ return Date.now().toString(36)+Math.random().toString(36).slice(2); }

function seedIfEmpty(){
  if(loadQ().length) return;
  saveQ([
    {id:uid(),level:'n3',type:'文字語彙',stem:'彼は（　　）顔で話しかけてきた。',options:['にこにこした','ぱらぱらした','ぐるぐるした','ぼろぼろした'],answer:0,explanation:'「にこにこ」是擬態語，形容面帶笑容、表情愉快。\n「ぱらぱら」指翻書或稀疏，「ぐるぐる」指旋轉，「ぼろぼろ」指破爛，均與臉部表情無關。',source:'範例題'},
    {id:uid(),level:'n2',type:'文法',stem:'試験に合格した（　　）、すぐ友人に連絡した。',options:['とたんに','ものの','にしては','ばかりか'],answer:0,explanation:'「〜とたんに」表示「剛一做完某事，緊接著就⋯⋯」，強調兩個動作幾乎同時發生的瞬間性。\n「ものの」表示轉折，「にしては」表示評價，「ばかりか」表示遞進，均不符合語意。',source:'範例題'},
    {id:uid(),level:'n2',type:'読解',passage:'日本語には「間（ま）」という概念がある。それは単なる沈黙ではなく、言葉と言葉の間に息づく空気のようなものだ。会話においても、あえて語らないことで、相手に想像の余地を与える。この「間」を理解せずして、日本語の真髄には近づけないと言われる。',stem:'この文章で筆者が最も伝えたいことは何か。',options:['日本語には沈黙が多く、会話が難しい。','「間」は日本語理解に欠かせない文化的概念である。','言葉を多く使うほど、日本語は上手になる。','日本語の文法は他の言語より複雑だ。'],answer:1,explanation:'文章核心主張：「間」不只是沉默，而是蘊含文化意義的空間，且「不理解間就無法接近日語的真髓」。選項２最完整呈現了筆者主旨。\n選項１錯誤（作者未說日語難以對話），選項３與４均未出現在文中。',source:'範例題'},
    {id:uid(),level:'n1',type:'文法',stem:'彼の発言は事実に（　　）、多くの誤解を招いた。',options:['もとづかず','もとづくことなく','もとづきながら','もとづくにつれ'],answer:1,explanation:'「〜ことなく」是 N1 書面語文法，等同於「〜ないで」，但語氣更正式，常見於評論、報導。\n「もとづかず」雖語法正確，但在此句式中略顯口語；「ながら」表示同時進行；「につれ」表示隨著⋯⋯而⋯⋯，語意均不符。',source:'範例題'},
  ]);
}

// ── Quiz State ──
let state = { filter:'all', pool:[], index:0, answered:false, selected:null, score:{correct:0,wrong:0}, done:false };

// ── Nav ──
document.querySelectorAll('.nav-tab').forEach(tab=>{
  tab.addEventListener('click',()=>{
    document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
    document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
    tab.classList.add('active');
    document.getElementById('page-'+tab.dataset.page).classList.add('active');
    if(tab.dataset.page==='admin') renderAdminList();
  });
});

// ── Filters ──
document.getElementById('quizFilters').addEventListener('click',e=>{
  if(!e.target.matches('.filter-pill')) return;
  document.querySelectorAll('.filter-pill').forEach(p=>p.classList.remove('active'));
  e.target.classList.add('active');
  state.filter=e.target.dataset.filter;
  startQuiz();
});

function getPool(){
  const qs=loadQ(), f=state.filter;
  return shuffle(f==='all'?[...qs]:qs.filter(q=>q.level===f||q.type===f));
}
function shuffle(a){ for(let i=a.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[a[i],a[j]]=[a[j],a[i]];} return a; }

function startQuiz(){
  state={filter:state.filter,pool:getPool(),index:0,answered:false,selected:null,score:{correct:0,wrong:0},done:false};
  renderQuiz();
}

// ── Render Quiz ──
const LABELS=['ア','イ','ウ','エ'];

function renderQuiz(){
  const area=document.getElementById('quizArea');
  const {pool,index,answered,done}=state;
  if(!pool.length){ area.innerHTML=`<div class="empty-state">尚無題目。<br>請先至「題庫管理」新增題目。</div>`; return; }
  if(done){ renderScore(area); return; }

  const q=pool[index], tot=pool.length, pct=(index/tot*100).toFixed(1);

  area.innerHTML=`
    <div class="quiz-meta">
      <span class="quiz-counter">${index+1} / ${tot}</span>
      <span style="display:flex;gap:.5rem">
        <span class="badge ${q.level}">${q.level.toUpperCase()}</span>
        <span class="type-chip">${q.type}</span>
      </span>
    </div>
    <div class="progress-bar"><div class="progress-fill" style="width:${pct}%"></div></div>
    <div class="q-card">
      <div class="q-header"><span class="q-number">第 ${index+1} 題</span></div>
      ${q.passage?`<div class="q-passage">${esc(q.passage)}</div>`:''}
      <div class="q-stem">${fmtStem(q.stem)}</div>
      <div class="options">
        ${q.options.map((o,i)=>`
          <div class="option${answered?' locked':''}" data-idx="${i}" tabindex="0">
            <span class="opt-label">${LABELS[i]||i+1}</span>
            <span>${esc(o)}</span>
          </div>`).join('')}
      </div>
      ${answered?renderExplanation(q):''}
      ${answered?`<div class="q-actions">
        ${index+1<tot
          ?`<button class="btn btn-primary" id="btnNext">次の問題 →</button>`
          :`<button class="btn btn-primary" id="btnFinish">結果を見る</button>`}
      </div>`:''}
    </div>`;

  if(!answered){
    area.querySelectorAll('.option').forEach(o=>{
      o.addEventListener('click',()=>selectOpt(parseInt(o.dataset.idx)));
      o.addEventListener('keydown',e=>{if(e.key==='Enter'||e.key===' ')selectOpt(parseInt(o.dataset.idx));});
    });
  } else {
    area.querySelectorAll('.option').forEach(o=>{
      const i=parseInt(o.dataset.idx);
      if(i===q.answer) o.classList.add(state.selected===q.answer?'correct':'reveal-correct');
      if(i===state.selected&&state.selected!==q.answer) o.classList.add('wrong');
    });
    const bn=area.querySelector('#btnNext'), bf=area.querySelector('#btnFinish');
    if(bn) bn.addEventListener('click',nextQ);
    if(bf) bf.addEventListener('click',()=>{state.done=true;renderQuiz();});
  }
}

function renderExplanation(q){
  const ok=state.selected===q.answer;
  return `<div class="explanation">
    <div class="exp-verdict">
      ${ok?`<span class="correct-mark">✓ 正解</span>`
          :`<span class="wrong-mark">✗ 不正解</span>　正解：<span class="exp-key">${LABELS[q.answer]}</span>　${esc(q.options[q.answer])}`}
    </div>
    ${q.explanation?q.explanation.split('\n').map(l=>`<p>${esc(l)}</p>`).join(''):''}
    ${q.source?`<p style="margin-top:.8rem;color:var(--muted);font-size:.72rem;letter-spacing:.1em;font-style:italic">出典：${esc(q.source)}</p>`:''}
  </div>`;
}

function selectOpt(i){
  state.answered=true; state.selected=i;
  if(i===state.pool[state.index].answer) state.score.correct++;
  else state.score.wrong++;
  renderQuiz();
}
function nextQ(){ state.index++; state.answered=false; state.selected=null; renderQuiz(); }

function renderScore(area){
  const {correct,wrong}=state.score, tot=state.pool.length, pct=Math.round(correct/tot*100);
  area.innerHTML=`
    <div class="score-card">
      <div class="score-big">${pct}<span style="font-size:1.8rem">%</span></div>
      <div class="score-label">正答率 Accuracy</div>
      <div class="score-breakdown">
        <div class="score-item"><div class="score-item-num" style="color:var(--accent2)">${correct}</div><div class="score-item-label">正解</div></div>
        <div class="score-item"><div class="score-item-num" style="color:var(--danger)">${wrong}</div><div class="score-item-label">不正解</div></div>
        <div class="score-item"><div class="score-item-num">${tot}</div><div class="score-item-label">合計</div></div>
      </div>
      <button class="btn btn-primary" id="btnRestart">もう一度</button>
    </div>`;
  area.querySelector('#btnRestart').addEventListener('click',startQuiz);
}

// ── Admin ──
function renderAdminList(){
  const qs=loadQ(), el=document.getElementById('qList');
  if(!qs.length){ el.innerHTML=`<div class="empty-state" style="padding:2rem">尚無題目，點擊「新增題目」開始建立題庫。</div>`; return; }
  el.innerHTML=qs.map(q=>`
    <div class="q-list-item">
      <div class="q-list-body">
        <div class="q-list-stem">${esc(q.stem)}</div>
        <div class="q-list-tags">
          <span class="badge ${q.level}">${q.level.toUpperCase()}</span>
          <span class="type-chip">${q.type}</span>
          ${q.source?`<span class="type-chip">${esc(q.source)}</span>`:''}
        </div>
      </div>
      <div class="q-list-actions">
        <button class="btn btn-ghost btn-sm" data-edit="${q.id}">編輯</button>
        <button class="btn btn-danger btn-sm" data-del="${q.id}">刪除</button>
      </div>
    </div>`).join('');
  el.querySelectorAll('[data-edit]').forEach(b=>b.addEventListener('click',()=>openModal(b.dataset.edit)));
  el.querySelectorAll('[data-del]').forEach(b=>b.addEventListener('click',()=>delQ(b.dataset.del)));
}

function delQ(id){
  if(!confirm('確定刪除此題目？')) return;
  saveQ(loadQ().filter(q=>q.id!==id)); renderAdminList();
}

// ── Modal ──
let editingId=null;

document.getElementById('btnAddQ').addEventListener('click',()=>openModal(null));
document.getElementById('modalClose').addEventListener('click',closeModal);
document.getElementById('btnCancel').addEventListener('click',closeModal);
document.getElementById('btnSave').addEventListener('click',saveQuestion);
document.getElementById('fType').addEventListener('change',togglePassageRow);

function togglePassageRow(){
  document.getElementById('passageRow').style.display=
    document.getElementById('fType').value==='読解'?'':'none';
}

function openModal(id){
  editingId=id;
  const q=id?loadQ().find(x=>x.id===id):null;
  document.getElementById('modalTitle').textContent=id?'編輯題目':'新增題目';
  document.getElementById('fLevel').value      =q?.level      ||'n2';
  document.getElementById('fType').value       =q?.type       ||'文法';
  document.getElementById('fStem').value       =q?.stem       ||'';
  document.getElementById('fPassage').value    =q?.passage    ||'';
  document.getElementById('fExplanation').value=q?.explanation||'';
  document.getElementById('fSource').value     =q?.source     ||'';
  document.getElementById('optionInputs').innerHTML=
    [0,1,2,3].map(i=>`
      <div class="option-input-row">
        <div class="opt-indicator${i===(q?.answer??0)?' correct-opt':''}" data-optidx="${i}">${LABELS[i]}</div>
        <input class="form-input" id="fOpt${i}" value="${escAttr(q?.options?.[i]||'')}" placeholder="選項 ${LABELS[i]}">
      </div>`).join('');
  togglePassageRow();
  document.querySelectorAll('.opt-indicator').forEach(ind=>{
    ind.addEventListener('click',()=>{
      document.querySelectorAll('.opt-indicator').forEach(x=>x.classList.remove('correct-opt'));
      ind.classList.add('correct-opt');
    });
  });
  document.getElementById('modalOverlay').classList.remove('hidden');
}

function closeModal(){
  document.getElementById('modalOverlay').classList.add('hidden'); editingId=null;
}

function saveQuestion(){
  const level=document.getElementById('fLevel').value;
  const type =document.getElementById('fType').value;
  const stem =document.getElementById('fStem').value.trim();
  const passage=document.getElementById('fPassage').value.trim();
  const explanation=document.getElementById('fExplanation').value.trim();
  const source=document.getElementById('fSource').value.trim();
  const options=[0,1,2,3].map(i=>document.getElementById(`fOpt${i}`).value.trim());
  const ansEl=document.querySelector('.opt-indicator.correct-opt');
  const answer=ansEl?parseInt(ansEl.dataset.optidx):0;
  if(!stem){alert('請填入題幹。');return;}
  if(options.some(o=>!o)){alert('請填入全部四個選項。');return;}
  const qs=loadQ();
  if(editingId){
    const idx=qs.findIndex(q=>q.id===editingId);
    if(idx>=0) qs[idx]={...qs[idx],level,type,stem,passage,options,answer,explanation,source};
  } else {
    qs.push({id:uid(),level,type,stem,passage,options,answer,explanation,source});
  }
  saveQ(qs); closeModal(); renderAdminList();
}

// ── Export / Import ──
document.getElementById('btnExport').addEventListener('click',()=>{
  const blob=new Blob([JSON.stringify(loadQ(),null,2)],{type:'application/json'});
  Object.assign(document.createElement('a'),{href:URL.createObjectURL(blob),download:'jlpt_questions.json'}).click();
});
document.getElementById('btnImport').addEventListener('click',()=>{
  document.getElementById('importText').value='';
  document.getElementById('importOverlay').classList.remove('hidden');
});
document.getElementById('importClose').addEventListener('click',()=>document.getElementById('importOverlay').classList.add('hidden'));
document.getElementById('importCancel').addEventListener('click',()=>document.getElementById('importOverlay').classList.add('hidden'));
document.getElementById('importConfirm').addEventListener('click',()=>{
  try{
    const data=JSON.parse(document.getElementById('importText').value.trim());
    if(!Array.isArray(data)) throw new Error('需要陣列格式');
    const existing=loadQ(), ids=new Set(existing.map(q=>q.id));
    let added=0;
    data.forEach(q=>{ if(!q.id)q.id=uid(); if(!ids.has(q.id)){existing.push(q);added++;} });
    saveQ(existing);
    document.getElementById('importOverlay').classList.add('hidden');
    alert(`成功匯入 ${added} 道題目。`);
    renderAdminList();
  }catch(e){ alert('JSON 格式錯誤：'+e.message); }
});

// close on backdrop
[document.getElementById('modalOverlay'),document.getElementById('importOverlay')].forEach(ov=>{
  ov.addEventListener('click',e=>{ if(e.target===ov) ov.classList.add('hidden'); });
});

// ── Utils ──
function esc(s){ return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }
function escAttr(s){ return String(s||'').replace(/"/g,'&quot;'); }
function fmtStem(s){ return esc(s).replace(/（　　）/g,`<span class="q-blank">　　　</span>`); }

// ── Init ──
seedIfEmpty();
startQuiz();
</script>
</body>
</html>
