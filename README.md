<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <title>RFLS Hub — Prototipo Seguro</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <style>
    :root { --bg:#0f1720; --panel:#111827; --accent:#ef4444; --muted:#9ca3af; --card:#0b1220; color-scheme: dark; }
    body{margin:0;font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;background:linear-gradient(180deg,#071021 0%, #081827 100%);color:#e6eef8}
    header{padding:16px 20px;display:flex;align-items:center;gap:12px;border-bottom:1px solid rgba(255,255,255,0.03)}
    .logo{width:40px;height:40px;border-radius:8px;background:linear-gradient(135deg,#ef4444,#f97316);display:flex;align-items:center;justify-content:center;font-weight:700}
    .container{display:flex;gap:16px;padding:18px}
    .sidebar{width:320px;background:var(--panel);border-radius:10px;padding:14px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    .main{flex:1;background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border-radius:10px;padding:14px;min-height:60vh}
    h2{margin:6px 0 12px 0;font-size:16px}
    .section{background:var(--card);padding:12px;border-radius:8px;margin-bottom:10px;border:1px solid rgba(255,255,255,0.03)}
    label{display:block;font-size:13px;margin-bottom:6px;color:var(--muted)}
    button, select{padding:8px 10px;border-radius:6px;border:1px solid rgba(255,255,255,0.04);background:rgba(255,255,255,0.02);color:inherit}
    .row{display:flex;gap:8px;flex-wrap:wrap}
    .log{height:240px;overflow:auto;background:#03111b;border-radius:6px;padding:10px;font-family:monospace;font-size:13px;border:1px solid rgba(255,255,255,0.02)}
    .toggle{
    
