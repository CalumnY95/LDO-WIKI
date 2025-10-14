## 🗺️ Carte interactive

Clique sur une zone pour ouvrir la page correspondante.

<style>
  .map-wrap { position: relative; width: 100%; max-width: 1536px; margin: 0 auto; }
  .map-wrap img { width: 100%; height: auto; display: block; }
  .pin {
    position: absolute; width: 14px; height: 14px; border-radius: 9999px;
    background: #ffc107; border: 2px solid #111; transform: translate(-50%,-50%);
    box-shadow: 0 1px 6px rgba(0,0,0,.35); cursor: pointer;
  }
  .pin:hover { transform: translate(-50%,-50%) scale(1.15); }
</style>

<div class="map-wrap">
  <!-- Mets ici LE src qui a marché au test -->
  <img src="./full-map.png" usemap="#worldmap" alt="Carte LDO" width="1536" style="max-width:none;">

  <!-- Pins visibles -->
  <a class="pin" href="../zones/minazuri.md"        style="left:61.6%; top:72.9%;" title="Minazuri"></a>
  <a class="pin" href="../zones/champs-devastes.md" style="left:66.3%; top:74.3%;" title="Champs dévastés"></a>
  <a class="pin" href="../zones/ruines-maudites.md" style="left:65.0%; top:81.4%;" title="Ruines maudites"></a>
  <a class="pin" href="../zones/archipelle-ika.md"  style="left:55.4%; top:83.0%;" title="Archipelle Ika"></a>
</div>

<map name="worldmap">
  <area shape="rect" coords="929,1103,962,1136"  href="../zones/minazuri.md"        alt="Minazuri">
  <area shape="rect" coords="995,1118,1040,1166" href="../zones/champs-devastes.md" alt="Champs dévastés">
  <area shape="rect" coords="959,1213,1037,1286" href="../zones/ruines-maudites.md" alt="Ruines maudites">
  <area shape="rect" coords="822,1234,880,1317"  href="../zones/archipelle-ika.md"  alt="Archipelle Ika">
</map>
