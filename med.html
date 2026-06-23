<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Ліки 💊">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#0f1117">
<title>Ліки 💊</title>
<style>
* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }

:root {
  --bg: #0f1117;
  --card: #1a1d27;
  --card2: #22263a;
  --border: rgba(255,255,255,0.07);
  --text: #f0f0f5;
  --muted: #8b8fa8;
  --hint: #52566a;
  --accent: #5b7fff;
  --green: #34d399;
  --green-dim: rgba(52,211,153,0.12);
  --amber: #fbbf24;
  --amber-dim: rgba(251,191,36,0.12);
  --red: #f87171;
  --red-dim: rgba(248,113,113,0.12);
  --morning: #ff9f45;
  --afternoon: #60a5fa;
  --evening: #a78bfa;
  --r: 18px;
  --r-sm: 12px;
}

html { height: 100%; background: var(--bg); }
body {
  font-family: -apple-system, 'SF Pro Display', 'Helvetica Neue', sans-serif;
  background: var(--bg);
  color: var(--text);
  min-height: 100vh;
  max-width: 430px;
  margin: 0 auto;
  padding-bottom: calc(80px + env(safe-area-inset-bottom, 16px));
  overflow-x: hidden;
}

/* ── HEADER ── */
.header {
  padding: calc(env(safe-area-inset-top, 16px) + 16px) 20px 0;
  background: var(--bg);
  position: sticky;
  top: 0;
  z-index: 20;
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
}
.header-top {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  margin-bottom: 16px;
}
.header-left h1 {
  font-size: 26px;
  font-weight: 700;
  letter-spacing: -0.5px;
  line-height: 1;
}
.header-left .subtitle {
  font-size: 13px;
  color: var(--muted);
  margin-top: 4px;
  text-transform: capitalize;
}
.streak-badge {
  background: var(--amber-dim);
  border: 1px solid rgba(251,191,36,0.2);
  border-radius: 20px;
  padding: 6px 12px;
  font-size: 13px;
  font-weight: 600;
  color: var(--amber);
  display: flex;
  align-items: center;
  gap: 4px;
}

/* ── PROGRESS BAR ── */
.day-progress {
  background: var(--card);
  border-radius: 6px;
  height: 6px;
  margin-bottom: 12px;
  overflow: hidden;
}
.day-progress-fill {
  height: 100%;
  border-radius: 6px;
  background: linear-gradient(90deg, var(--accent), var(--green));
  transition: width 0.5s ease;
}
.progress-label {
  display: flex;
  justify-content: space-between;
  font-size: 11px;
  color: var(--hint);
  margin-bottom: 6px;
}

/* ── DATE PILLS ── */
.date-row {
  display: flex;
  gap: 6px;
  overflow-x: auto;
  scrollbar-width: none;
  padding-bottom: 12px;
  margin: 0 -20px;
  padding-left: 20px;
  padding-right: 20px;
}
.date-row::-webkit-scrollbar { display: none; }
.date-pill {
  flex-shrink: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 8px 10px;
  border-radius: var(--r-sm);
  background: var(--card);
  cursor: pointer;
  min-width: 48px;
  border: 1px solid transparent;
  transition: all 0.15s;
  user-select: none;
}
.date-pill.active {
  background: var(--accent);
  border-color: rgba(255,255,255,0.15);
}
.date-pill.today-indicator {
  border-color: var(--accent);
}
.date-pill .wd {
  font-size: 10px;
  font-weight: 600;
  color: var(--hint);
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
.date-pill .dn {
  font-size: 18px;
  font-weight: 700;
  color: var(--text);
  margin-top: 1px;
}
.date-pill.active .wd,
.date-pill.active .dn { color: white; }

/* ── CONTENT ── */
.content { padding: 8px 20px 0; }

/* ── TIME SECTION ── */
.time-section {
  margin-bottom: 20px;
  border-radius: var(--r);
  overflow: hidden;
  background: var(--card);
  border: 1px solid var(--border);
}
.time-section-header {
  padding: 14px 16px 12px;
  display: flex;
  align-items: center;
  gap: 10px;
  border-bottom: 1px solid var(--border);
}
.time-icon {
  width: 34px;
  height: 34px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 16px;
  flex-shrink: 0;
}
.time-icon.morning  { background: rgba(255,159,69,0.15); }
.time-icon.afternoon{ background: rgba(96,165,250,0.15); }
.time-icon.evening  { background: rgba(167,139,250,0.15); }

.time-title-block { flex: 1; }
.time-label-text {
  font-size: 15px;
  font-weight: 700;
  color: var(--text);
}
.time-sublabel {
  font-size: 12px;
  color: var(--muted);
  margin-top: 1px;
}
.time-count {
  font-size: 12px;
  padding: 3px 9px;
  border-radius: 20px;
  font-weight: 600;
}
.time-count.done { background: var(--green-dim); color: var(--green); }
.time-count.partial { background: var(--amber-dim); color: var(--amber); }
.time-count.none { background: var(--card2); color: var(--hint); }

/* ── MED ITEM ── */
.med-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 14px 16px;
  border-bottom: 1px solid var(--border);
  cursor: pointer;
  transition: background 0.12s;
  user-select: none;
  -webkit-user-select: none;
}
.med-item:last-child { border-bottom: none; }
.med-item:active { background: rgba(255,255,255,0.03); }

.med-color-bar {
  width: 3px;
  height: 36px;
  border-radius: 2px;
  flex-shrink: 0;
}
.med-info { flex: 1; }
.med-name {
  font-size: 15px;
  font-weight: 600;
  color: var(--text);
  transition: opacity 0.2s;
}
.med-sub {
  font-size: 12px;
  color: var(--muted);
  margin-top: 3px;
  display: flex;
  gap: 6px;
  align-items: center;
  flex-wrap: wrap;
}
.tag {
  display: inline-flex;
  align-items: center;
  gap: 3px;
  font-size: 11px;
  font-weight: 600;
  padding: 2px 7px;
  border-radius: 6px;
}
.tag.warn { background: rgba(167,139,250,0.15); color: #a78bfa; }
.tag.cold { background: rgba(96,165,250,0.15); color: #60a5fa; }
.tag.antibiotic { background: var(--red-dim); color: var(--red); }

.check-circle {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  border: 2px solid var(--hint);
  background: transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  transition: all 0.2s cubic-bezier(0.34,1.56,0.64,1);
}
.check-circle.checked {
  background: var(--green);
  border-color: var(--green);
  transform: scale(1.05);
}
.check-circle svg {
  opacity: 0;
  transform: scale(0.6);
  transition: all 0.18s ease;
}
.check-circle.checked svg {
  opacity: 1;
  transform: scale(1);
}

.med-item.taken .med-name { opacity: 0.35; }
.med-item.taken .med-sub { opacity: 0.3; }

/* ── EMPTY ── */
.empty-state {
  text-align: center;
  padding: 40px 20px;
  color: var(--hint);
}
.empty-state .big { font-size: 44px; margin-bottom: 10px; }
.empty-state p { font-size: 15px; }

/* ── BOTTOM NAV ── */
.bottom-nav {
  position: fixed;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  max-width: 430px;
  background: rgba(15,17,23,0.92);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border-top: 1px solid var(--border);
  display: flex;
  padding: 10px 20px calc(10px + env(safe-area-inset-bottom, 0px));
  gap: 4px;
  z-index: 30;
}
.nav-btn {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 3px;
  padding: 6px 0;
  border-radius: var(--r-sm);
  cursor: pointer;
  user-select: none;
  transition: all 0.15s;
  border: none;
  background: none;
  color: var(--hint);
}
.nav-btn.active { color: var(--accent); }
.nav-btn .nav-icon { font-size: 22px; line-height: 1; }
.nav-btn .nav-label { font-size: 10px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.05em; }

/* ── MEDS TAB ── */
.med-card-full {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--r);
  padding: 16px;
  margin-bottom: 10px;
}
.med-card-top {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 12px;
}
.med-dot { width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0; }
.med-card-name { font-size: 16px; font-weight: 700; flex: 1; }
.end-badge {
  font-size: 11px;
  font-weight: 600;
  padding: 3px 9px;
  border-radius: 20px;
}
.end-soon { background: var(--amber-dim); color: var(--amber); }
.end-mid { background: rgba(96,165,250,0.12); color: #60a5fa; }
.end-long { background: var(--green-dim); color: var(--green); }
.end-done { background: var(--card2); color: var(--hint); }

.med-card-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 12px; }
.mgrid-item .ml { font-size: 11px; color: var(--hint); margin-bottom: 3px; }
.mgrid-item .mv { font-size: 13px; font-weight: 500; color: var(--text); }
.med-card-note { font-size: 12px; color: var(--muted); padding: 10px 12px; background: var(--card2); border-radius: var(--r-sm); }
.prog-bar { height: 4px; background: var(--card2); border-radius: 3px; margin-top: 12px; overflow: hidden; }
.prog-fill { height: 100%; border-radius: 3px; transition: width 0.5s; }

/* ── INFO TAB ── */
.info-section { margin-bottom: 16px; }
.info-title { font-size: 12px; font-weight: 700; color: var(--hint); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 8px; }
.info-card {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--r);
  overflow: hidden;
}
.info-row {
  display: flex;
  align-items: center;
  padding: 13px 16px;
  border-bottom: 1px solid var(--border);
  gap: 12px;
  font-size: 14px;
}
.info-row:last-child { border-bottom: none; }
.info-row .il { color: var(--muted); flex: 1; }
.info-row .iv { font-weight: 600; color: var(--text); }
.warn-card {
  background: var(--red-dim);
  border: 1px solid rgba(248,113,113,0.2);
  border-radius: var(--r);
  padding: 16px;
  margin-bottom: 10px;
}
.warn-title { font-size: 13px; font-weight: 700; color: var(--red); margin-bottom: 10px; display: flex; align-items: center; gap: 6px; }
.warn-item { font-size: 13px; color: var(--text); padding: 6px 0; border-bottom: 1px solid rgba(248,113,113,0.1); line-height: 1.5; }
.warn-item:last-child { border-bottom: none; }
.tips-card {
  background: var(--green-dim);
  border: 1px solid rgba(52,211,153,0.2);
  border-radius: var(--r);
  padding: 16px;
}
.tips-title { font-size: 13px; font-weight: 700; color: var(--green); margin-bottom: 10px; display: flex; align-items: center; gap: 6px; }
.tips-item { font-size: 13px; color: var(--text); padding: 5px 0; line-height: 1.5; }

/* ── INSTALL BANNER ── */
.install-banner {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--r);
  padding: 14px 16px;
  margin-bottom: 16px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.install-icon { font-size: 28px; flex-shrink: 0; }
.install-text .it { font-size: 14px; font-weight: 600; color: var(--text); }
.install-text .is { font-size: 12px; color: var(--muted); margin-top: 3px; line-height: 1.4; }
.install-close { font-size: 18px; color: var(--hint); cursor: pointer; padding: 4px; flex-shrink: 0; }

/* ── TABS ── */
.tab-content { display: none; }
.tab-content.visible { display: block; }
</style>
</head>
<body>

<div class="header">
  <div class="header-top">
    <div class="header-left">
      <h1>💊 Ліки</h1>
      <div class="subtitle" id="headerDate"></div>
    </div>
    <div class="streak-badge" id="streakBadge">🔥 <span id="streakNum">0</span> дн.</div>
  </div>
  <div class="progress-label">
    <span id="progressText">Прийнято сьогодні</span>
    <span id="progressPct">0%</span>
  </div>
  <div class="day-progress"><div class="day-progress-fill" id="dayProgressFill" style="width:0%"></div></div>
  <div class="date-row" id="dateRow"></div>
</div>

<!-- TAB: Today -->
<div id="tab-today" class="tab-content visible">
  <div class="content" id="todayContent"></div>
</div>

<!-- TAB: Meds -->
<div id="tab-meds" class="tab-content">
  <div class="content" id="medsContent"></div>
</div>

<!-- TAB: Info -->
<div id="tab-info" class="tab-content">
  <div class="content" id="infoContent"></div>
</div>

<!-- Bottom Nav -->
<nav class="bottom-nav">
  <button class="nav-btn active" onclick="switchTab('today')" id="nav-today">
    <span class="nav-icon">📋</span>
    <span class="nav-label">Сьогодні</span>
  </button>
  <button class="nav-btn" onclick="switchTab('meds')" id="nav-meds">
    <span class="nav-icon">💊</span>
    <span class="nav-label">Курси</span>
  </button>
  <button class="nav-btn" onclick="switchTab('info')" id="nav-info">
    <span class="nav-icon">ℹ️</span>
    <span class="nav-label">Важливо</span>
  </button>
</nav>

<script>
// ── DATA ──────────────────────────────────────────────────
const START = new Date(2026, 5, 22); // 22 червня 2026

const MEDS = [
  {
    id: 'opticef', name: 'Оптицеф', color: '#e06c8a',
    days: 7, dose: '1 т. × 1 р/д',
    note: 'Антибіотик — не пропускати прийоми, довести курс до кінця',
    tags: ['antibiotic'],
    slots: [{ period: 'evening', food: 'після їжі', label: 'після вечері' }]
  },
  {
    id: 'urofuragin', name: 'Урофурагін', color: '#f0a030',
    days: 14, dose: '1 т. × 3 р/д',
    note: 'Пити з великою кількістю рідини',
    tags: [],
    slots: [
      { period: 'morning',   food: 'після їжі', label: 'після сніданку' },
      { period: 'afternoon', food: 'після їжі', label: 'після обіду' },
      { period: 'evening',   food: 'після їжі', label: 'після вечері' }
    ]
  },
  {
    id: 'arstifen', name: 'Арстифен', color: '#34d399',
    days: 91, dose: '1 т. × 3 р/д',
    note: 'Не переривати курс без консультації лікаря',
    tags: [],
    slots: [
      { period: 'morning',   food: 'після їжі', label: 'після сніданку' },
      { period: 'afternoon', food: 'після їжі', label: 'після обіду' },
      { period: 'evening',   food: 'після їжі', label: 'після вечері' }
    ]
  },
  {
    id: 'nokamen', name: 'Нокамен', color: '#a78bfa',
    days: 61, dose: '1 т. × 2 р/д',
    note: 'Приймати за 30 хвилин ДО їжі',
    tags: ['warn'],
    slots: [
      { period: 'morning', food: 'ДО їжі — за 30 хв', label: 'вранці' },
      { period: 'evening', food: 'ДО їжі — за 30 хв', label: 'ввечері' }
    ]
  },
  {
    id: 'maxibalance', name: 'Максібаланс', color: '#60a5fa',
    days: 10, dose: '1 т. × 2 р/д',
    note: 'Зберігати у холодильнику!',
    tags: ['cold'],
    slots: [
      { period: 'morning', food: 'після їжі', label: 'після сніданку' },
      { period: 'evening', food: 'після їжі', label: 'після вечері' }
    ]
  }
];

const PERIODS = [
  { id: 'morning',   icon: '☀️', label: 'Ранок',  time: '7:00',  class: 'morning' },
  { id: 'afternoon', icon: '🌤',  label: 'Обід',   time: '13:00', class: 'afternoon' },
  { id: 'evening',   icon: '🌙', label: 'Вечір',  time: '19:00', class: 'evening' }
];

// ── STATE ─────────────────────────────────────────────────
const CK = 'meds_v3';
let data = {};
try { data = JSON.parse(localStorage.getItem(CK) || '{}'); } catch(e) {}
function save() { try { localStorage.setItem(CK, JSON.stringify(data)); } catch(e) {} }

function addDays(d, n) { const r = new Date(d); r.setDate(r.getDate()+n); return r; }
function dayOff(d) {
  const a = new Date(d); a.setHours(0,0,0,0);
  const b = new Date(START); b.setHours(0,0,0,0);
  return Math.round((a-b)/86400000);
}
function endDate(m) { return addDays(START, m.days - 1); }
function fmtDate(d) { return d.toLocaleDateString('uk-UA', { day:'numeric', month:'long' }); }
function fmtShort(d) { return d.toLocaleDateString('uk-UA', { day:'numeric', month:'short' }); }

const WD = ['нд','пн','вт','ср','чт','пт','сб'];
let selectedOff = dayOff(new Date());

// ── HEADER ───────────────────────────────────────────────
function renderHeader() {
  const today = new Date();
  const todayOff = dayOff(today);
  const d = addDays(START, selectedOff);
  const weekday = d.toLocaleDateString('uk-UA', { weekday:'long' });
  const dateStr = d.toLocaleDateString('uk-UA', { day:'numeric', month:'long' });

  document.getElementById('headerDate').textContent =
    weekday.charAt(0).toUpperCase() + weekday.slice(1) + ', ' + dateStr;

  // streak
  let streak = 0;
  for (let i = todayOff; i >= 0; i--) {
    const key = `d${i}`;
    const dayMeds = MEDS.filter(m => i >= 0 && i < m.days);
    if (!dayMeds.length) break;
    const allSlots = dayMeds.flatMap(m => m.slots.map(s => `${m.id}_${s.period}`));
    const taken = allSlots.filter(k => data[key] && data[key][k]);
    if (taken.length === allSlots.length) streak++;
    else break;
  }
  document.getElementById('streakNum').textContent = streak;

  // progress today
  updateDayProgress();
}

function updateDayProgress() {
  const key = `d${selectedOff}`;
  const active = MEDS.filter(m => selectedOff >= 0 && selectedOff < m.days);
  const allSlots = active.flatMap(m => m.slots.map(s => `${m.id}_${s.period}`));
  const taken = allSlots.filter(k => data[key] && data[key][k]);
  const pct = allSlots.length ? Math.round(taken.length / allSlots.length * 100) : 100;
  document.getElementById('dayProgressFill').style.width = pct + '%';
  document.getElementById('progressPct').textContent = pct + '%';
  document.getElementById('progressText').textContent =
    taken.length + ' з ' + allSlots.length + ' прийомів';
}

// ── DATE ROW ─────────────────────────────────────────────
function renderDateRow() {
  const row = document.getElementById('dateRow');
  row.innerHTML = '';
  const todayOff = dayOff(new Date());

  for (let i = 0; i < 14; i++) {
    const off = todayOff - 1 + i;
    const d = addDays(START, off);
    const chip = document.createElement('div');
    const isActive = off === selectedOff;
    const isToday = off === todayOff;
    chip.className = 'date-pill' + (isActive ? ' active' : '') + (!isActive && isToday ? ' today-indicator' : '');
    chip.innerHTML = `<span class="wd">${WD[d.getDay()]}</span><span class="dn">${d.getDate()}</span>`;
    chip.onclick = () => { selectedOff = off; renderAll(); };
    row.appendChild(chip);
    if (isToday) setTimeout(() => chip.scrollIntoView({ inline:'center', behavior:'smooth' }), 60);
  }
}

// ── TODAY TAB ────────────────────────────────────────────
function renderToday() {
  const el = document.getElementById('todayContent');
  el.innerHTML = '';
  const key = `d${selectedOff}`;

  const active = MEDS.filter(m => selectedOff >= 0 && selectedOff < m.days);

  if (!active.length) {
    el.innerHTML = `<div class="empty-state"><div class="big">🎉</div><p>Цього дня прийомів немає</p></div>`;
    return;
  }

  PERIODS.forEach(period => {
    const periodMeds = active.filter(m => m.slots.some(s => s.period === period.id));
    if (!periodMeds.length) return;

    const total = periodMeds.length;
    const takenCount = periodMeds.filter(m => data[key] && data[key][`${m.id}_${period.id}`]).length;

    const section = document.createElement('div');
    section.className = 'time-section';

    let countClass = takenCount === 0 ? 'none' : takenCount === total ? 'done' : 'partial';
    let countText = takenCount === total ? '✓ Всі прийняті' : takenCount + '/' + total + ' прийнято';

    section.innerHTML = `
      <div class="time-section-header">
        <div class="time-icon ${period.class}">${period.icon}</div>
        <div class="time-title-block">
          <div class="time-label-text">${period.label}</div>
          <div class="time-sublabel">${period.time}</div>
        </div>
        <div class="time-count ${countClass}" id="cnt_${period.id}">${countText}</div>
      </div>
    `;

    periodMeds.forEach(med => {
      const slot = med.slots.find(s => s.period === period.id);
      const ck = `${med.id}_${period.id}`;
      const taken = !!(data[key] && data[key][ck]);

      const row = document.createElement('div');
      row.className = 'med-item' + (taken ? ' taken' : '');
      row.dataset.ck = ck;

      let tagsHTML = slot.food.includes('ДО') ? '<span class="tag warn">⚠ До їжі</span>' : `<span>${slot.food}</span>`;
      if (med.tags.includes('cold')) tagsHTML += ' <span class="tag cold">❄ Холодильник</span>';
      if (med.tags.includes('antibiotic')) tagsHTML += ' <span class="tag antibiotic">Антибіотик</span>';

      row.innerHTML = `
        <div class="med-color-bar" style="background:${med.color}"></div>
        <div class="med-info">
          <div class="med-name">${med.name}</div>
          <div class="med-sub">${tagsHTML}</div>
        </div>
        <div class="check-circle${taken ? ' checked' : ''}">
          <svg width="13" height="13" viewBox="0 0 13 13" fill="none">
            <path d="M2 6.5l3 3 6-6" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </div>
      `;

      row.onclick = () => {
        if (!data[key]) data[key] = {};
        data[key][ck] = !data[key][ck];
        save();
        if (navigator.vibrate) navigator.vibrate(data[key][ck] ? [20] : [10,10,10]);
        row.classList.toggle('taken', data[key][ck]);
        const circle = row.querySelector('.check-circle');
        circle.classList.toggle('checked', data[key][ck]);
        // update count
        const allMeds = active.filter(m => m.slots.some(s => s.period === period.id));
        const t = allMeds.filter(m => data[key] && data[key][`${m.id}_${period.id}`]).length;
        const c = document.getElementById('cnt_' + period.id);
        c.className = 'time-count ' + (t === 0 ? 'none' : t === allMeds.length ? 'done' : 'partial');
        c.textContent = t === allMeds.length ? '✓ Всі прийняті' : t + '/' + allMeds.length + ' прийнято';
        updateDayProgress();
        renderHeader();
      };

      section.appendChild(row);
    });

    el.appendChild(section);
  });
}

// ── MEDS TAB ─────────────────────────────────────────────
function renderMeds() {
  const el = document.getElementById('medsContent');
  el.innerHTML = '';
  const todayOff = dayOff(new Date());

  MEDS.forEach(med => {
    const end = endDate(med);
    const rem = med.days - todayOff;
    const pct = Math.min(100, Math.max(0, Math.round(todayOff / med.days * 100)));
    let badgeClass, badgeText;
    if (rem <= 0) { badgeClass='end-done'; badgeText='Завершено'; }
    else if (rem <= 5) { badgeClass='end-soon'; badgeText=rem+' дн.'; }
    else if (rem <= 20) { badgeClass='end-mid'; badgeText=rem+' дн.'; }
    else { badgeClass='end-long'; badgeText=rem+' дн.'; }

    const timesText = [...new Set(med.slots.map(s => {
      const p = PERIODS.find(p => p.id === s.period);
      return p.time;
    }))].join(', ');

    const card = document.createElement('div');
    card.className = 'med-card-full';
    card.innerHTML = `
      <div class="med-card-top">
        <div class="med-dot" style="background:${med.color}"></div>
        <div class="med-card-name">${med.name}</div>
        <span class="end-badge ${badgeClass}">${badgeText}</span>
      </div>
      <div class="med-card-grid">
        <div class="mgrid-item"><div class="ml">Дозування</div><div class="mv">${med.dose}</div></div>
        <div class="mgrid-item"><div class="ml">Кінець курсу</div><div class="mv">${fmtShort(end)}</div></div>
        <div class="mgrid-item"><div class="ml">Час прийому</div><div class="mv">${timesText}</div></div>
        <div class="mgrid-item"><div class="ml">Прийом з їжею</div><div class="mv">${med.slots[0].food}</div></div>
      </div>
      <div class="med-card-note">💬 ${med.note}</div>
      <div class="prog-bar"><div class="prog-fill" style="width:${pct}%;background:${med.color}"></div></div>
    `;
    el.appendChild(card);
  });
}

// ── INFO TAB ─────────────────────────────────────────────
function renderInfo() {
  document.getElementById('infoContent').innerHTML = `
    <div class="install-banner" id="installBanner">
      <div class="install-icon">📲</div>
      <div class="install-text">
        <div class="it">Додати на головний екран</div>
        <div class="is">iOS: кнопка «Поділитись» → «На екран "Додому"»<br>Android: меню ⋮ → «Додати на головний екран»</div>
      </div>
      <div class="install-close" onclick="document.getElementById('installBanner').remove()">✕</div>
    </div>

    <div class="info-section">
      <div class="info-title">⚠️ Критично важливо</div>
      <div class="warn-card">
        <div class="warn-title">⚠ Увага</div>
        <div class="warn-item">🟣 <b>Нокамен</b> — єдиний, що треба пити <b>за 30 хв ДО їжі</b>. Решта — після!</div>
        <div class="warn-item">❄️ <b>Максібаланс</b> — зберігати у <b>холодильнику</b></div>
        <div class="warn-item">💊 <b>Оптицеф</b> — антибіотик, курс пройти повністю, не переривати</div>
        <div class="warn-item">💧 Пити <b>1.5–2 л рідини</b> на день</div>
      </div>
    </div>

    <div class="info-section">
      <div class="info-title">📅 Дати закінчення</div>
      <div class="info-card">
        <div class="info-row"><span class="il">Оптицеф</span><span class="iv">28 червня 2026</span></div>
        <div class="info-row"><span class="il">Максібаланс</span><span class="iv">1 липня 2026</span></div>
        <div class="info-row"><span class="il">Урофурагін</span><span class="iv">5 липня 2026</span></div>
        <div class="info-row"><span class="il">Нокамен</span><span class="iv">21 серпня 2026</span></div>
        <div class="info-row"><span class="il">Арстифен</span><span class="iv">20 вересня 2026</span></div>
      </div>
    </div>

    <div class="info-section">
      <div class="info-title">💡 Після стентування</div>
      <div class="tips-card">
        <div class="tips-title">✅ Рекомендації</div>
        <div class="tips-item">— Не піднімати важке понад 5 кг до видалення стента</div>
        <div class="tips-item">— Обмежити фізичні навантаження</div>
        <div class="tips-item">— При появі крові в сечі, болю або температури — одразу до лікаря</div>
        <div class="tips-item">— Стент зазвичай видаляють через 2–4 тижні після операції</div>
      </div>
    </div>
  `;
}

// ── TABS ─────────────────────────────────────────────────
function switchTab(name) {
  ['today','meds','info'].forEach(t => {
    document.getElementById('tab-'+t).classList.toggle('visible', t === name);
    document.getElementById('nav-'+t).classList.toggle('active', t === name);
  });
  window.scrollTo({ top: 0, behavior: 'smooth' });
}

// ── INIT ─────────────────────────────────────────────────
function renderAll() {
  renderHeader();
  renderDateRow();
  renderToday();
}

renderAll();
renderMeds();
renderInfo();
</script>
</body>
</html>
