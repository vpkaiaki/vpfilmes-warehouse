# vpfilmes-warehouse<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mapa de Corredores - VP Filmes</title>
<style>
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #f5f5f5; padding: 20px; }
.container { max-width: 1400px; margin: 0 auto; background: white; border-radius: 8px; padding: 25px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
h1 { color: #0B2027; margin-bottom: 10px; font-size: 24px; }
.subtitle { color: #666; font-size: 12px; margin-bottom: 25px; }
.summary { background: #f0f8fb; border-left: 4px solid #4FB8C0; padding: 15px; border-radius: 4px; margin-bottom: 25px; }
.summary-row { display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-bottom: 10px; }
.summary-item { font-size: 12px; }
.summary-label { color: #666; font-weight: 500; }
.summary-value { color: #0B2027; font-weight: bold; font-size: 16px; }
.warehouse { display: grid; grid-template-columns: 1fr 120px 1fr; gap: 40px; }
.side { border: 2px solid #0B2027; border-radius: 6px; padding: 15px; background: #f9f9f9; }
.side-title { font-weight: bold; color: #0B2027; font-size: 14px; margin-bottom: 15px; text-align: center; }
.corridor-group { margin-bottom: 20px; }
.corridor-label { font-size: 11px; color: #666; font-weight: 500; margin-bottom: 5px; display: flex; justify-content: space-between; }
.corridor { display: flex; gap: 8px; }
.corridor-single { flex: 1; height: 40px; background: linear-gradient(to right, #e8f7f9, #f0f0f0); border: 1px solid #4FB8C0; border-radius: 3px; display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 500; color: #0B2027; cursor: pointer; transition: all 0.2s; }
.corridor-single:hover { background: #d0f0f5; box-shadow: 0 2px 4px rgba(79, 184, 192, 0.3); }
.corridor-double { display: grid; grid-template-columns: 1fr 1fr; gap: 4px; flex: 1; }
.corridor-double-item { height: 40px; background: linear-gradient(to right, #e8f7f9, #f0f0f0); border: 1px solid #4FB8C0; border-radius: 3px; display: flex; align-items: center; justify-content: center; font-size: 10px; font-weight: 500; color: #0B2027; cursor: pointer; transition: all 0.2s; }
.corridor-double-item:hover { background: #d0f0f5; box-shadow: 0 2px 4px rgba(79, 184, 192, 0.3); }
.center-info { display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
.center-info p { color: #666; font-size: 12px; margin-bottom: 8px; }
.center-info strong { color: #0B2027; font-size: 14px; }
.specs { background: #f0f8fb; padding: 10px; border-radius: 4px; border-left: 3px solid #4FB8C0; margin-top: 10px; font-size: 11px; color: #666; line-height: 1.6; }
.specs strong { color: #0B2027; }
</style>
</head>
<body>
<div class="container">
  <h1>Mapa de Corredores - VP Filmes Galp 09</h1>
  <div class="subtitle">Layout linear dos corredores (80cm largura, espacamento 30cm)</div>

  <div class="summary">
    <div class="summary-row">
      <div class="summary-item">
        <div class="summary-label">Total de Corredores</div>
        <div class="summary-value">27</div>
      </div>
      <div class="summary-item">
        <div class="summary-label">Comprimento Total</div>
        <div class="summary-value">215,90m</div>
      </div>
    </div>
    <div class="summary-row">
      <div class="summary-item">
        <div class="summary-label">Esquerda: 10 corredores</div>
        <div class="summary-value">76,10m</div>
      </div>
      <div class="summary-item">
        <div class="summary-label">Direita: 17 corredores</div>
        <div class="summary-value">139,80m</div>
      </div>
    </div>
  </div>

  <div class="warehouse">
    <div class="side">
      <div class="side-title">ESQUERDA (10 CORREDORES)</div>
      
      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 1</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">E1</div><div class="corridor-double-item">E2</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 2</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">E3</div><div class="corridor-double-item">E4</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 3</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">E5</div><div class="corridor-double-item">E6</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 4</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">E7</div><div class="corridor-double-item">E8</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 5</span><span>6,10m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">E9</div><div class="corridor-double-item">E10</div></div></div>
      </div>
    </div>

    <div class="center-info">
      <strong>VP FILMES</strong>
      <p>Galp 09</p>
      <p>Blumenau, SC</p>
      <div class="specs">
        <strong>Dimensoes:</strong><br>
        Corredor: 80cm<br>
        Espaco: 30cm<br><br>
        <strong>Comprimentos:</strong><br>
        6,10m ou 7,50m
      </div>
    </div>

    <div class="side">
      <div class="side-title">DIREITA (17 CORREDORES)</div>
      
      <div class="corridor-group">
        <div class="corridor-label"><span>Solo</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-single">D1</div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 1</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D2</div><div class="corridor-double-item">D3</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 2</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D4</div><div class="corridor-double-item">D5</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 3</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D6</div><div class="corridor-double-item">D7</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 4</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D8</div><div class="corridor-double-item">D9</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 5</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D10</div><div class="corridor-double-item">D11</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 6</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D12</div><div class="corridor-double-item">D13</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 7</span><span>7,50m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D14</div><div class="corridor-double-item">D15</div></div></div>
      </div>

      <div class="corridor-group">
        <div class="corridor-label"><span>Duplo 8</span><span>6,10m</span></div>
        <div class="corridor"><div class="corridor-double"><div class="corridor-double-item">D16</div><div class="corridor-double-item">D17</div></div></div>
      </div>
    </div>
  </div>
</div>
</body>
</html>
