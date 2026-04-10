<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Admin — Club GlobalVet</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700;800&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#f2f4f9;--w:#fff;--dk:#12103a;--pu:#4f35b3;--pu2:#6c4fd6;--pl:#ede9ff;
      --te:#0a7c6e;--gr:#1e8a50;--re:#d94040;--go:#e8a020;--mu:#6b7280;--li:#e5e7eb;
      --ff:'Space Grotesk',sans-serif;--fb:'DM Sans',sans-serif;}
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:var(--fb);background:var(--bg);color:var(--dk)}
    button,input,select,textarea{font-family:var(--fb);cursor:pointer}

    /* LOGIN */
    #L{min-height:100vh;display:flex;align-items:center;justify-content:center;
      background:radial-gradient(ellipse at 65% 0%,rgba(95,69,200,.2),transparent 52%),
      radial-gradient(ellipse at 0% 90%,rgba(59,43,134,.15),transparent 48%),
      linear-gradient(175deg,#eceeff,#f2f4f9);padding:1rem}
    .lc{background:#fff;border-radius:24px;padding:2.4rem 2.2rem;width:100%;max-width:400px;
      box-shadow:0 24px 60px rgba(18,16,58,.13)}
    .lb{display:flex;align-items:center;justify-content:center;gap:.65rem;margin-bottom:1.5rem}
    .lb-ico{width:44px;height:44px;background:linear-gradient(135deg,var(--dk),var(--pu));
      border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:1.4rem}
    .lb-nm{font-family:var(--ff);font-size:1rem;font-weight:700}
    .lt{font-family:var(--ff);font-size:1.3rem;font-weight:700;text-align:center;margin-bottom:.25rem}
    .ls{font-size:.83rem;color:var(--mu);text-align:center;margin-bottom:1.6rem}
    .le{background:#fff0f0;border:1px solid #fecaca;border-radius:10px;padding:.65rem .9rem;
      font-size:.83rem;color:var(--re);margin-bottom:.8rem;display:none}
    .le.show{display:block}
    .lf{margin-bottom:.9rem}
    .ll{font-size:.7rem;font-weight:700;letter-spacing:.07em;text-transform:uppercase;
      color:var(--mu);display:block;margin-bottom:.35rem}
    .li{width:100%;padding:.72rem .95rem;background:#f8fbff;border:1.5px solid var(--li);
      border-radius:12px;font-size:.9rem;color:var(--dk);outline:none;transition:border-color .2s}
    .li:focus{border-color:var(--pu)}
    .lbtn{width:100%;padding:.88rem;background:var(--dk);color:#fff;font-family:var(--ff);
      font-weight:700;font-size:.95rem;border:none;border-radius:14px;transition:opacity .15s}
    .lbtn:hover{opacity:.88}

    /* NAV */
    #A{display:none}
    .nav{background:var(--dk);height:54px;display:flex;align-items:center;
      justify-content:space-between;padding:0 1.5rem;position:sticky;top:0;z-index:200;
      box-shadow:0 2px 12px rgba(0,0,0,.2)}
    .nav-l{display:flex;align-items:center;gap:.75rem}
    .nav-ico{width:32px;height:32px;background:linear-gradient(135deg,var(--pu),var(--pu2));
      border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:.95rem}
    .nav-nm{font-family:var(--ff);font-size:.93rem;font-weight:700;color:#fff}
    .nav-bd{background:var(--re);color:#fff;font-size:.67rem;font-weight:700;
      padding:.18rem .6rem;border-radius:50px;letter-spacing:.04em;text-transform:uppercase}
    .nav-r{display:flex;align-items:center;gap:.8rem}
    .nav-u{font-family:var(--ff);font-size:.8rem;color:rgba(255,255,255,.5)}
    .nav-out{background:none;border:1px solid rgba(255,255,255,.15);color:rgba(255,255,255,.5);
      font-size:.8rem;font-weight:600;padding:.3rem .8rem;border-radius:50px;transition:all .15s}
    .nav-out:hover{border-color:rgba(255,100,100,.5);color:#ff8080}

    /* LAYOUT */
    .lay{display:flex;min-height:calc(100vh - 54px)}
    .sb{width:218px;flex-shrink:0;background:var(--w);border-right:1px solid var(--li);
      padding:1.1rem .75rem;position:sticky;top:54px;height:calc(100vh - 54px);overflow-y:auto}
    .sb-lbl{font-size:.64rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;
      color:#9ca3af;padding:.7rem .65rem .3rem}
    .sb-btn{display:flex;align-items:center;gap:.6rem;padding:.62rem .75rem;border-radius:10px;
      border:none;background:none;font-size:.85rem;font-weight:600;color:var(--mu);
      width:100%;text-align:left;transition:background .15s,color .15s}
    .sb-btn:hover{background:var(--bg);color:var(--dk)}
    .sb-btn.on{background:var(--pl);color:var(--pu)}
    .sb-btn svg{flex-shrink:0;opacity:.8}
    .sb-n{margin-left:auto;font-size:.65rem;font-weight:700;padding:.1rem .42rem;
      border-radius:50px;color:#fff}
    .sb-n.pu{background:var(--pu)}.sb-n.gr{background:var(--gr)}.sb-n.re{background:var(--re)}

    .mn{flex:1;padding:2rem 2.2rem;min-width:0;max-width:1080px}
    .pn{display:none}.pn.on{display:block}
    .ptit{font-family:var(--ff);font-size:1.2rem;font-weight:700;margin-bottom:1.5rem;
      display:flex;align-items:center;gap:.55rem}

    /* STATS */
    .sts{display:grid;grid-template-columns:repeat(4,1fr);gap:1rem;margin-bottom:1.8rem}
    .st{background:var(--w);border-radius:15px;padding:1.25rem 1.3rem;border:1px solid var(--li)}
    .st-n{font-family:var(--ff);font-size:1.9rem;font-weight:700;line-height:1;margin-bottom:.2rem}
    .st-l{font-size:.79rem;color:var(--mu)}
    .st.pu .st-n{color:var(--pu)}.st.gr .st-n{color:var(--gr)}
    .st.re .st-n{color:var(--re)}.st.go .st-n{color:var(--go)}

    /* CARD */
    .cd{background:var(--w);border-radius:18px;border:1px solid var(--li);overflow:hidden;margin-bottom:1.5rem}
    .cd-h{display:flex;align-items:center;justify-content:space-between;
      padding:1rem 1.4rem;border-bottom:1px solid var(--li)}
    .cd-t{font-family:var(--ff);font-size:.96rem;font-weight:700;display:flex;align-items:center;gap:.5rem}
    .cd-b{padding:1.4rem}
    .cd-b.np{padding:0}

    /* TABLE */
    .tb{width:100%;border-collapse:collapse}
    .tb th{font-size:.7rem;font-weight:700;letter-spacing:.06em;text-transform:uppercase;
      color:var(--mu);padding:.7rem 1.3rem;text-align:left;border-bottom:1px solid var(--li);background:#fafbff}
    .tb td{padding:.8rem 1.3rem;font-size:.86rem;border-bottom:1px solid var(--li)}
    .tb tr:last-child td{border-bottom:none}
    .tb tbody tr:hover td{background:#fafbff}
    .mn-n{font-weight:700}.mn-e{font-size:.77rem;color:var(--mu)}
    .sc{display:inline-flex;align-items:center;gap:.3rem;font-size:.71rem;font-weight:700;
      padding:.2rem .6rem;border-radius:50px}
    .sc-a{background:rgba(30,138,80,.1);color:var(--gr)}
    .sc-p{background:rgba(232,160,32,.12);color:#7a4800}
    .pch{font-size:.74rem;font-weight:700;padding:.18rem .5rem;border-radius:50px;
      background:var(--pl);color:var(--pu)}
    .srch{padding:.44rem .88rem;border:1.5px solid var(--li);border-radius:10px;
      font-size:.83rem;outline:none;width:230px;transition:border-color .2s}
    .srch:focus{border-color:var(--pu)}

    /* ACTIONS */
    .ab{padding:.3rem .72rem;border-radius:8px;font-size:.74rem;font-weight:700;
      border:none;transition:opacity .15s;margin-right:.3rem}
    .ab:hover{opacity:.78}
    .ab-on{background:rgba(30,138,80,.1);color:var(--gr)}
    .ab-off{background:rgba(217,64,64,.1);color:var(--re)}
    .ab-del{background:rgba(217,64,64,.08);color:var(--re)}

    /* FORM */
    .fg{display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1rem}
    .fg3{grid-template-columns:1fr 1fr 1fr}
    .fsp{grid-column:1/-1}
    .fl{font-size:.69rem;font-weight:700;letter-spacing:.07em;text-transform:uppercase;
      color:var(--mu);display:block;margin-bottom:.32rem}
    .fi{width:100%;padding:.64rem .88rem;background:#f8fbff;border:1.5px solid var(--li);
      border-radius:10px;font-size:.87rem;color:var(--dk);outline:none;transition:border-color .2s}
    .fi:focus{border-color:var(--pu);background:#fff}
    .fs{width:100%;padding:.64rem .88rem;border:1.5px solid var(--li);border-radius:10px;
      font-size:.87rem;color:var(--dk);background:#f8fbff;outline:none;
      appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='11' height='11' viewBox='0 0 24 24' fill='none' stroke='%236b7280' stroke-width='2'%3E%3Cpolyline points='6 9 12 15 18 9'/%3E%3C/svg%3E");
      background-repeat:no-repeat;background-position:right .75rem center;padding-right:2rem}
    .fs:focus{border-color:var(--pu)}

    /* BUTTONS */
    .bm{display:inline-flex;align-items:center;gap:.5rem;background:var(--pu);color:#fff;
      border:none;border-radius:12px;padding:.72rem 1.5rem;font-family:var(--ff);
      font-size:.87rem;font-weight:700;transition:opacity .15s}
    .bm:hover{opacity:.88}
    .bm.gr{background:var(--gr)}.bm.re{background:var(--re)}
    .bs{display:inline-flex;align-items:center;gap:.5rem;background:transparent;color:var(--dk);
      border:1.5px solid var(--li);border-radius:12px;padding:.7rem 1.3rem;
      font-family:var(--ff);font-size:.87rem;font-weight:700;transition:all .15s}
    .bs:hover{border-color:var(--pu);color:var(--pu)}

    /* VIDEO ROWS */
    .vr{display:flex;align-items:center;gap:1rem;padding:.88rem 1.4rem;border-bottom:1px solid var(--li)}
    .vr:last-child{border-bottom:none}
    .vt{width:54px;height:40px;border-radius:9px;overflow:hidden;flex-shrink:0}
    .vt img{width:100%;height:100%;object-fit:cover}
    .vt-d{width:54px;height:40px;border-radius:9px;background:linear-gradient(135deg,#12103a,#4f35b3);
      display:flex;align-items:center;justify-content:center;font-size:1rem;flex-shrink:0}
    .vi{flex:1;min-width:0}
    .vtit{font-size:.9rem;font-weight:700;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
    .vme{font-size:.74rem;color:var(--mu)}
    .vc{font-size:.7rem;font-weight:700;padding:.14rem .5rem;border-radius:50px;
      background:var(--pl);color:var(--pu);white-space:nowrap;flex-shrink:0}

    /* FEED ROWS */
    .fr{display:flex;align-items:center;gap:1rem;padding:.95rem 1.4rem;border-bottom:1px solid var(--li)}
    .fr:last-child{border-bottom:none}
    .fd{font-size:.71rem;font-weight:700;text-transform:uppercase;letter-spacing:.05em;
      padding:.2rem .65rem;border-radius:50px;background:var(--pl);color:var(--pu);
      white-space:nowrap;flex-shrink:0;min-width:90px;text-align:center}
    .fc{flex:1;min-width:0}
    .ft{font-size:.9rem;font-weight:700}
    .fm{font-size:.74rem;color:var(--mu)}
    .tv{background:rgba(217,64,64,.1);color:var(--re);font-size:.7rem;font-weight:700;padding:.14rem .5rem;border-radius:50px}
    .tp{background:rgba(79,53,179,.1);color:var(--pu);font-size:.7rem;font-weight:700;padding:.14rem .5rem;border-radius:50px}
    .tl{background:rgba(232,160,32,.15);color:#7a4800;font-size:.7rem;font-weight:700;padding:.14rem .5rem;border-radius:50px}
    .tn{background:var(--dk);color:#fff;font-size:.7rem;font-weight:700;padding:.14rem .5rem;border-radius:50px}

    /* LIVE CARD */
    .lvc{background:linear-gradient(135deg,#1a1060,#4f35b3);border-radius:16px;
      padding:1.5rem;color:#fff;margin-bottom:1rem}
    .lvc-t{font-family:var(--ff);font-size:1.1rem;font-weight:700;margin-bottom:.3rem}
    .lvc-m{font-size:.83rem;color:rgba(255,255,255,.6)}

    /* TOAST */
    .tst{position:fixed;bottom:1.5rem;left:50%;transform:translateX(-50%) translateY(80px);
      background:var(--dk);color:#fff;font-family:var(--ff);font-size:.87rem;font-weight:600;
      padding:.72rem 1.4rem;border-radius:50px;box-shadow:0 8px 24px rgba(0,0,0,.2);z-index:500;
      opacity:0;transition:transform .35s cubic-bezier(.34,1.56,.64,1),opacity .3s;white-space:nowrap}
    .tst.show{transform:translateX(-50%) translateY(0);opacity:1}
    .tst.gr{background:var(--te)}

    /* MODAL */
    .mo{display:none;position:fixed;inset:0;background:rgba(18,16,58,.45);
      backdrop-filter:blur(4px);z-index:300;align-items:center;justify-content:center;padding:1rem}
    .mo.show{display:flex}
    .mb{background:#fff;border-radius:22px;width:100%;max-width:500px;
      box-shadow:0 24px 60px rgba(18,16,58,.2);overflow:hidden}
    .mb-h{display:flex;align-items:center;justify-content:space-between;
      padding:1.1rem 1.4rem;border-bottom:1px solid var(--li)}
    .mb-t{font-family:var(--ff);font-size:1rem;font-weight:700}
    .mb-x{background:rgba(0,0,0,.06);border:none;width:30px;height:30px;border-radius:50%;
      font-size:1rem;display:flex;align-items:center;justify-content:center}
    .mb-b{padding:1.3rem 1.4rem}
    .mb-f{padding:.85rem 1.4rem;border-top:1px solid var(--li);display:flex;gap:.6rem;justify-content:flex-end}

    @media(max-width:900px){.sts{grid-template-columns:1fr 1fr}.sb{display:none}.mn{padding:1.2rem}}
  </style>
</head>
<body>

<!-- LOGIN -->
<div id="L">
  <div class="lc">
    <div class="lb"><div class="lb-ico">🐾</div><div class="lb-nm"><strong>GlobalVet</strong> Admin</div></div>
    <h1 class="lt">Panel Administrativo</h1>
    <p class="ls">Solo para administradores del Club</p>
    <div class="le" id="le">Correo o contraseña incorrectos.</div>
    <div class="lf"><label class="ll">Correo</label><input class="li" type="email" id="lem" placeholder="admin@globalvet.com"></div>
    <div class="lf"><label class="ll">Contraseña</label><input class="li" type="password" id="lps" placeholder="Tu contraseña"></div>
    <button class="lbtn" id="lbtn" onclick="doLogin()">Iniciar sesión</button>
  </div>
</div>

<!-- ADMIN -->
<div id="A">
  <nav class="nav">
    <div class="nav-l">
      <div class="nav-ico">🐾</div>
      <span class="nav-nm">GlobalVet Admin</span>
      <span class="nav-bd">Admin</span>
    </div>
    <div class="nav-r">
      <span class="nav-u" id="nu"></span>
      <button class="nav-out" onclick="doLogout()">Salir</button>
    </div>
  </nav>

  <div class="lay">
    <aside class="sb">
      <div class="sb-lbl">Principal</div>
      <button class="sb-btn on" onclick="sp('r',this)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/><rect x="14" y="14" width="7" height="7"/></svg>
        Resumen
      </button>
      <div class="sb-lbl">Miembros</div>
      <button class="sb-btn" onclick="sp('m',this)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg>
        Todos los miembros
        <span class="sb-n pu" id="sbt">0</span>
      </button>
      <div class="sb-lbl">Contenido Club</div>
      <button class="sb-btn" onclick="sp('v',this)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><polygon points="23 7 16 12 23 17 23 7"/><rect x="1" y="5" width="15" height="14" rx="2"/></svg>
        Videos
        <span class="sb-n gr" id="sbv">0</span>
      </button>
      <button class="sb-btn" onclick="sp('f',this)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><line x1="8" y1="6" x2="21" y2="6"/><line x1="8" y1="12" x2="21" y2="12"/><line x1="8" y1="18" x2="21" y2="18"/><line x1="3" y1="6" x2="3.01" y2="6"/><line x1="3" y1="12" x2="3.01" y2="12"/><line x1="3" y1="18" x2="3.01" y2="18"/></svg>
        Feed semanal
      </button>
      <button class="sb-btn" onclick="sp('s',this)">
        <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
        Próxima sesión
      </button>
    </aside>

    <main class="mn">

      <!-- RESUMEN -->
      <div class="pn on" id="p-r">
        <div class="ptit">📊 Resumen del Club</div>
        <div class="sts">
          <div class="st pu"><div class="st-n" id="stt">—</div><div class="st-l">Miembros totales</div></div>
          <div class="st gr"><div class="st-n" id="sta">—</div><div class="st-l">Activos</div></div>
          <div class="st re"><div class="st-n" id="stp">—</div><div class="st-l">Pendientes</div></div>
          <div class="st go"><div class="st-n" id="stv">—</div><div class="st-l">Videos en biblioteca</div></div>
        </div>
        <div class="cd">
          <div class="cd-h"><div class="cd-t">👥 Últimos registros</div></div>
          <div class="cd-b np">
            <table class="tb"><thead><tr><th>Miembro</th><th>Plan</th><th>Estado</th><th>Fecha</th></tr></thead>
            <tbody id="rtb"><tr><td colspan="4" style="text-align:center;padding:2rem;color:var(--mu)">Cargando…</td></tr></tbody></table>
          </div>
        </div>
      </div>

      <!-- MIEMBROS -->
      <div class="pn" id="p-m">
        <div class="ptit">👥 Miembros del Club</div>
        <div class="cd">
          <div class="cd-h">
            <div class="cd-t">Todos los miembros</div>
            <input class="srch" type="text" placeholder="Buscar nombre o email…" oninput="fM(this.value)">
          </div>
          <div class="cd-b np">
            <table class="tb">
              <thead><tr><th>Nombre</th><th>Email</th><th>Plan</th><th>Estado</th><th>Fecha</th><th>Acción</th></tr></thead>
              <tbody id="mtb"><tr><td colspan="6" style="text-align:center;padding:2rem;color:var(--mu)">Cargando…</td></tr></tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIDEOS -->
      <div class="pn" id="p-v">
        <div class="ptit">🎬 Videos del Club</div>
        <div class="cd">
          <div class="cd-h"><div class="cd-t">➕ Agregar nuevo video</div></div>
          <div class="cd-b">
            <div class="fg">
              <div><label class="fl">Título del video</label><input class="fi" type="text" id="vt" placeholder="Ej: Diagnóstico diferencial canino"></div>
              <div><label class="fl">Categoría</label>
                <select class="fs" id="vc">
                  <option value="endo">Endocrinología canina básica</option>
                  <option value="onco">Bases de oncología veterinaria</option>
                  <option value="hema">Hematología clínica</option>
                  <option value="otro">Otro / Nuevo curso</option>
                </select>
              </div>
              <div><label class="fl">URL de YouTube</label><input class="fi" type="url" id="vu" placeholder="https://youtu.be/XXXXXXX"></div>
              <div><label class="fl">Instructor</label><input class="fi" type="text" id="vi" placeholder="MVZ. Juan Pérez"></div>
              <div><label class="fl">Duración</label><input class="fi" type="text" id="vd" placeholder="42 min"></div>
              <div><label class="fl">Etiqueta</label>
                <select class="fs" id="vtg">
                  <option value="nuevo">🆕 Nuevo</option>
                  <option value="">Sin etiqueta</option>
                  <option value="visto">Visto</option>
                </select>
              </div>
            </div>
            <button class="bm" onclick="addV()">
              <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
              Agregar video al Club
            </button>
          </div>
        </div>
        <div class="cd">
          <div class="cd-h"><div class="cd-t">📚 Biblioteca actual</div></div>
          <div class="cd-b np" id="vlist"><div style="text-align:center;padding:2rem;color:var(--mu)">Cargando…</div></div>
        </div>
      </div>

      <!-- FEED -->
      <div class="pn" id="p-f">
        <div class="ptit">📅 Feed semanal</div>
        <div class="cd">
          <div class="cd-h"><div class="cd-t">✏️ Agregar contenido a la semana</div></div>
          <div class="cd-b">
            <div class="fg fg3">
              <div><label class="fl">Día</label>
                <select class="fs" id="fd">
                  <option>Lunes</option><option>Martes</option><option>Miércoles</option>
                  <option>Jueves</option><option>Viernes</option><option>Nuevo hoy</option>
                </select>
              </div>
              <div><label class="fl">Tipo</label>
                <select class="fs" id="ftp">
                  <option value="video">🎥 Video</option>
                  <option value="pdf">📄 PDF</option>
                  <option value="live">🔴 En vivo</option>
                  <option value="nuevo">✨ Nuevo</option>
                </select>
              </div>
              <div><label class="fl">Meta (instructor, duración…)</label><input class="fi" type="text" id="fm" placeholder="Dr. Morales · 12 min"></div>
              <div class="fsp"><label class="fl">Título del contenido</label><input class="fi" type="text" id="ftt" placeholder="Diagnóstico diferencial: vómito crónico en felinos"></div>
            </div>
            <button class="bm" onclick="addF()">
              <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
              Agregar al feed
            </button>
          </div>
        </div>
        <div class="cd">
          <div class="cd-h">
            <div class="cd-t">📋 Contenido de esta semana</div>
            <button class="bs" onclick="clrF()" style="font-size:.8rem;padding:.38rem .85rem">🗑️ Limpiar semana</button>
          </div>
          <div class="cd-b np" id="flist"><div style="text-align:center;padding:2rem;color:var(--mu)">Cargando…</div></div>
        </div>
      </div>

      <!-- SESION -->
      <div class="pn" id="p-s">
        <div class="ptit">📡 Próxima sesión en vivo</div>
        <div class="cd" style="margin-bottom:1.5rem">
          <div class="cd-h"><div class="cd-t">✏️ Configurar sesión</div></div>
          <div class="cd-b">
            <div class="fg">
              <div><label class="fl">Título</label><input class="fi" type="text" id="st" placeholder="Q&A Endocrinología"></div>
              <div><label class="fl">Instructor</label><input class="fi" type="text" id="si" placeholder="Dr. Juárez"></div>
              <div><label class="fl">Fecha (texto)</label><input class="fi" type="text" id="sf" placeholder="23 de abril"></div>
              <div><label class="fl">Hora</label><input class="fi" type="text" id="sh" placeholder="8:00 PM"></div>
              <div class="fsp"><label class="fl">Fecha/hora exacta para cronómetro</label><input class="fi" type="datetime-local" id="se"></div>
            </div>
            <button class="bm gr" onclick="saveS()">
              <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"/></svg>
              Guardar sesión — se actualiza en tiempo real
            </button>
          </div>
        </div>
        <div class="lvc">
          <div style="font-size:.7rem;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:rgba(255,255,255,.4);margin-bottom:.6rem">Vista previa en el dashboard</div>
          <div class="lvc-t" id="lpt">Q&A Endocrinología</div>
          <div class="lvc-m" id="lpm">Dr. Juárez · 23 de abril · 8:00 PM</div>
          <div style="font-size:.78rem;color:rgba(255,255,255,.4);margin-top:.5rem">El cronómetro se calcula automáticamente desde la fecha exacta.</div>
        </div>
      </div>

    </main>
  </div>
</div>

<!-- MODAL -->
<div class="mo" id="mo">
  <div class="mb">
    <div class="mb-h"><div class="mb-t">⚠️ Confirmar</div><button class="mb-x" onclick="cmo()">✕</button></div>
    <div class="mb-b"><p style="font-size:.92rem;color:var(--mu)" id="moMsg"></p></div>
    <div class="mb-f"><button class="bs" onclick="cmo()">Cancelar</button><button class="bm re" id="moBtn">Eliminar</button></div>
  </div>
</div>

<div class="tst" id="tst"></div>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.0/firebase-app.js";
import { getAuth, signInWithEmailAndPassword, onAuthStateChanged, signOut }
  from "https://www.gstatic.com/firebasejs/10.12.0/firebase-auth.js";
import { getFirestore, collection, getDocs, doc, getDoc, setDoc, updateDoc, addDoc, deleteDoc, serverTimestamp }
  from "https://www.gstatic.com/firebasejs/10.12.0/firebase-firestore.js";

const cfg={apiKey:"AIzaSyDw-1mNG-xj55Yb_TyHw6LFWwpptqJZJ3M",authDomain:"club-global-vet.firebaseapp.com",
  projectId:"club-global-vet",storageBucket:"club-global-vet.firebasestorage.app",
  messagingSenderId:"448888067634",appId:"1:448888067634:web:96adc6b03ba3248f4f0e2b"};
const app=initializeApp(cfg),auth=getAuth(app),db=getFirestore(app);
const ADMINS=['globalvetmexico1@gmail.com','teccapitalweb@gmail.com'];
let AM=[],AV=[];

// AUTH
onAuthStateChanged(auth,u=>{
  if(u&&ADMINS.includes(u.email)){
    document.getElementById('L').style.display='none';
    document.getElementById('A').style.display='block';
    document.getElementById('nu').textContent=u.email;
    loadAll();
  }else if(u){signOut(auth);err('Sin permisos de administrador.');}
  else{document.getElementById('L').style.display='flex';document.getElementById('A').style.display='none';}
});

window.doLogin=async()=>{
  const e=document.getElementById('lem').value.trim(),p=document.getElementById('lps').value;
  if(!e||!p)return;
  const b=document.getElementById('lbtn');b.textContent='Verificando…';b.disabled=true;
  try{await signInWithEmailAndPassword(auth,e,p);}
  catch{err('Correo o contraseña incorrectos.');b.textContent='Iniciar sesión';b.disabled=false;}
};
window.doLogout=async()=>{await signOut(auth);};
function err(m){const el=document.getElementById('le');el.textContent=m;el.classList.add('show');setTimeout(()=>el.classList.remove('show'),4000);}

async function loadAll(){await Promise.all([loadM(),loadV(),loadF(),loadS()]);}

// MIEMBROS
async function loadM(){
  try{
    const s=await getDocs(collection(db,'usuarios'));
    AM=s.docs.map(d=>({id:d.id,...d.data()}));
    const t=AM.length,a=AM.filter(m=>m.membresiaActiva||m.estado==='activo').length;
    document.getElementById('stt').textContent=t;
    document.getElementById('sta').textContent=a;
    document.getElementById('stp').textContent=t-a;
    document.getElementById('sbt').textContent=t;
    rM(AM);rR(AM.slice(0,6));
  }catch{toast('❌ Error cargando miembros');}
}
function rM(list){
  const tb=document.getElementById('mtb');
  if(!list.length){tb.innerHTML='<tr><td colspan="6" style="text-align:center;padding:2rem;color:var(--mu)">Sin miembros</td></tr>';return;}
  tb.innerHTML=list.map(m=>{
    const ok=m.membresiaActiva||m.estado==='activo';
    const f=m.fechaRegistro?.toDate?m.fechaRegistro.toDate().toLocaleDateString('es-MX',{day:'2-digit',month:'short',year:'numeric'}):'—';
    return`<tr>
      <td><div class="mn-n">${m.nombre||'—'}</div></td>
      <td><div class="mn-e">${m.email||'—'}</div></td>
      <td><span class="pch">${m.planLabel||'Plan Mensual'}</span></td>
      <td><span class="sc ${ok?'sc-a':'sc-p'}">${ok?'✓ Activo':'⏳ Pendiente'}</span></td>
      <td style="font-size:.79rem;color:var(--mu)">${f}</td>
      <td>${ok?`<button class="ab ab-off" onclick="tgM('${m.id}',false)">Desactivar</button>`
               :`<button class="ab ab-on"  onclick="tgM('${m.id}',true)">Activar</button>`}</td>
    </tr>`;
  }).join('');
}
function rR(list){
  const tb=document.getElementById('rtb');
  if(!list.length){tb.innerHTML='<tr><td colspan="4" style="text-align:center;padding:2rem;color:var(--mu)">Sin registros</td></tr>';return;}
  tb.innerHTML=list.map(m=>{
    const ok=m.membresiaActiva||m.estado==='activo';
    const f=m.fechaRegistro?.toDate?m.fechaRegistro.toDate().toLocaleDateString('es-MX',{day:'2-digit',month:'short',year:'numeric'}):'—';
    return`<tr>
      <td><div class="mn-n">${m.nombre||'—'}</div><div class="mn-e">${m.email||'—'}</div></td>
      <td><span class="pch">${m.planLabel||'Plan Mensual'}</span></td>
      <td><span class="sc ${ok?'sc-a':'sc-p'}">${ok?'✓ Activo':'⏳ Pendiente'}</span></td>
      <td style="font-size:.79rem;color:var(--mu)">${f}</td>
    </tr>`;
  }).join('');
}
window.fM=q=>{const f=AM.filter(m=>(m.nombre||'').toLowerCase().includes(q.toLowerCase())||(m.email||'').toLowerCase().includes(q.toLowerCase()));rM(f);};
window.tgM=async(uid,on)=>{
  try{await updateDoc(doc(db,'usuarios',uid),{membresiaActiva:on,estado:on?'activo':'inactivo'});
    toast(on?'✅ Membresía activada':'⚠️ Membresía desactivada',on);loadM();}
  catch{toast('❌ Error al actualizar');}
};

// VIDEOS
const CN={endo:'Endocrinología',onco:'Oncología',hema:'Hematología',otro:'Otro'};
const CI={endo:'https://teccapitalweb.github.io/globalvet-mexico/assets/img/cursos/endocrinologia.png',
         onco:'https://teccapitalweb.github.io/globalvet-mexico/assets/img/cursos/oncologia.png',
         hema:'https://teccapitalweb.github.io/globalvet-mexico/assets/img/cursos/hematologia.png'};
async function loadV(){
  try{const s=await getDocs(collection(db,'videos_club'));
    AV=s.docs.map(d=>({id:d.id,...d.data()}));
    document.getElementById('stv').textContent=AV.length;
    document.getElementById('sbv').textContent=AV.length;
    rV(AV);}catch{rV([]);}
}
function rV(list){
  const c=document.getElementById('vlist');
  if(!list.length){c.innerHTML='<div style="text-align:center;padding:2rem;color:var(--mu)">Sin videos. Agrega el primero arriba.</div>';return;}
  c.innerHTML=list.map(v=>{
    const img=CI[v.categoria];
    return`<div class="vr">
      ${img?`<div class="vt"><img src="${img}" alt=""></div>`:'<div class="vt-d">🎥</div>'}
      <div class="vi">
        <div class="vtit">${v.titulo||'—'}</div>
        <div class="vme">${v.instructor||''} ${v.duracion?'· '+v.duracion:''} · <a href="https://youtu.be/${v.youtubeUrl}" target="_blank" style="color:var(--pu)">Ver ↗</a></div>
      </div>
      <span class="vc">${CN[v.categoria]||v.categoria||'—'}</span>
      <button class="ab ab-del" onclick="dV('${v.id}')">🗑️ Eliminar</button>
    </div>`;
  }).join('');
}
window.addV=async()=>{
  const t=document.getElementById('vt').value.trim(),u=document.getElementById('vu').value.trim();
  if(!t||!u){toast('⚠️ Título y URL son obligatorios');return;}
  let id=u;const m=u.match(/(?:youtu\.be\/|v=|\/embed\/)([a-zA-Z0-9_-]{11})/);if(m)id=m[1];
  try{await addDoc(collection(db,'videos_club'),{
    titulo:t,categoria:document.getElementById('vc').value,youtubeUrl:id,
    instructor:document.getElementById('vi').value.trim(),
    duracion:document.getElementById('vd').value.trim(),
    etiqueta:document.getElementById('vtg').value,fechaSubida:serverTimestamp()});
    toast('✅ Video agregado — visible para clientes en tiempo real',true);
    ['vt','vu','vi','vd'].forEach(x=>document.getElementById(x).value='');
    loadV();}
  catch{toast('❌ Error al guardar');}
};
window.dV=id=>confirm2('¿Eliminar este video de la biblioteca?',async()=>{
  await deleteDoc(doc(db,'videos_club',id));toast('🗑️ Video eliminado');loadV();});

// FEED
const TM={video:'tv',pdf:'tp',live:'tl',nuevo:'tn'};
const TL={video:'● Video',pdf:'● PDF',live:'● En vivo',nuevo:'Nuevo'};
async function loadF(){
  try{const s=await getDocs(collection(db,'feed_semanal'));
    rF(s.docs.map(d=>({id:d.id,...d.data()})));}catch{rF([]);}
}
function rF(list){
  const c=document.getElementById('flist');
  if(!list.length){c.innerHTML='<div style="text-align:center;padding:2rem;color:var(--mu)">Feed vacío.</div>';return;}
  c.innerHTML=list.map(f=>`<div class="fr">
    <span class="fd">${f.dia||'—'}</span>
    <div class="fc"><div class="ft">${f.titulo||'—'}</div><div class="fm">${f.meta||''}</div></div>
    <span class="${TM[f.tipo]||'tn'}">${TL[f.tipo]||f.tipo}</span>
    <button class="ab ab-del" onclick="dF('${f.id}')">🗑️</button>
  </div>`).join('');
}
window.addF=async()=>{
  const t=document.getElementById('ftt').value.trim();
  if(!t){toast('⚠️ Escribe el título');return;}
  try{await addDoc(collection(db,'feed_semanal'),{
    dia:document.getElementById('fd').value,tipo:document.getElementById('ftp').value,
    titulo:t,meta:document.getElementById('fm').value.trim(),creado:serverTimestamp()});
    toast('✅ Agregado al feed — visible para clientes ahora',true);
    document.getElementById('ftt').value='';document.getElementById('fm').value='';
    loadF();}
  catch{toast('❌ Error');}
};
window.dF=id=>confirm2('¿Eliminar este ítem del feed?',async()=>{
  await deleteDoc(doc(db,'feed_semanal',id));toast('🗑️ Eliminado');loadF();});
window.clrF=()=>confirm2('¿Limpiar todo el feed de esta semana?',async()=>{
  const s=await getDocs(collection(db,'feed_semanal'));
  await Promise.all(s.docs.map(d=>deleteDoc(d.ref)));
  toast('✅ Feed limpiado',true);loadF();});

// SESION
async function loadS(){
  try{const s=await getDoc(doc(db,'config','proxima_sesion'));
    if(s.exists()){const d=s.data();
      document.getElementById('st').value=d.titulo||'';
      document.getElementById('si').value=d.instructor||'';
      document.getElementById('sf').value=d.fecha||'';
      document.getElementById('sh').value=d.hora||'';
      if(d.fechaExacta)document.getElementById('se').value=d.fechaExacta;
      updPrev(d.titulo,d.instructor,d.fecha,d.hora);}}catch{}
}
function updPrev(t,i,f,h){
  document.getElementById('lpt').textContent=t||'Título de la sesión';
  document.getElementById('lpm').textContent=`${i||'Instructor'} · ${f||'Fecha'} · ${h||'Hora'}`;
}
window.saveS=async()=>{
  const t=document.getElementById('st').value.trim();
  if(!t){toast('⚠️ Escribe el título');return;}
  try{await setDoc(doc(db,'config','proxima_sesion'),{
    titulo:t,instructor:document.getElementById('si').value.trim(),
    fecha:document.getElementById('sf').value.trim(),hora:document.getElementById('sh').value.trim(),
    fechaExacta:document.getElementById('se').value,actualizado:serverTimestamp()});
    toast('✅ Sesión guardada — el cronómetro se actualiza en tiempo real',true);
    updPrev(t,document.getElementById('si').value,document.getElementById('sf').value,document.getElementById('sh').value);}
  catch{toast('❌ Error al guardar');}
};
['st','si','sf','sh'].forEach(id=>document.getElementById(id)?.addEventListener('input',()=>
  updPrev(document.getElementById('st').value,document.getElementById('si').value,
          document.getElementById('sf').value,document.getElementById('sh').value)));

// CONFIRM MODAL
let PA=null;
function confirm2(msg,cb){document.getElementById('moMsg').textContent=msg;PA=cb;document.getElementById('mo').classList.add('show');}
window.cmo=()=>{document.getElementById('mo').classList.remove('show');PA=null;};
document.getElementById('moBtn').onclick=async()=>{if(PA){await PA();PA=null;}cmo();};

// TOAST
function toast(msg,gr){
  const t=document.getElementById('tst');t.textContent=msg;
  t.className='tst show'+(gr?' gr':'');setTimeout(()=>t.classList.remove('show'),3500);}
window.toast=toast;
</script>

<script>
function sp(id,btn){
  document.querySelectorAll('.pn').forEach(p=>p.classList.remove('on'));
  document.querySelectorAll('.sb-btn').forEach(b=>b.classList.remove('on'));
  document.getElementById('p-'+id).classList.add('on');
  if(btn)btn.classList.add('on');
}
window.sp=sp;
document.addEventListener('keydown',e=>{if(e.key==='Enter'){const L=document.getElementById('L');if(L&&L.style.display!=='none')window.doLogin?.();}});
</script>
</body>
</html>
