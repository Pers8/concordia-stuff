```html
<!-- Paste this directly into an Obsidian note (Source mode). Do NOT include the backticks. -->
<style>
  :root{
    --bg:#0b0b0f; --panel:#111218; --muted:#a9b0c6; --text:#e9ecf8; --line:#1e2230;
    --brand:#6ea8ff; --accent:#ffd089; --green:#9be7c4;
  }
  .skin-wrap{max-width:1100px; padding:28px; margin:0 auto; background:linear-gradient(180deg,#0a0b12, #0b0b0f 30% 70%, #090a0e); color:var(--text); border-radius:16px}
  .skin-title{font-size: clamp(1.4rem, 1.1rem + 1.2vw, 2.1rem); font-weight:650; letter-spacing:.2px; margin:6px 0 2px}
  .skin-sub{color:var(--muted); font-size:.98rem; margin-bottom:18px}
  .skin-card{background:radial-gradient(80% 120% at 10% -20%, rgba(110,168,255,.08), transparent 40%), radial-gradient(70% 120% at 100% 0%, rgba(255,208,137,.06), transparent 46%), var(--panel); border:1px solid var(--line); border-radius:16px; overflow:hidden; box-shadow:0 12px 30px rgba(0,0,0,.35)}
  .skin-table{width:100%; border-collapse:separate; border-spacing:0}
  .skin-thead th{background: linear-gradient(180deg, #141726, #10131d); color:#c9d2ee; text-align:left; font-weight:600; padding:14px 16px; border-bottom:1px solid var(--line)}
  .skin-td{padding:14px 16px; border-bottom:1px solid var(--line); vertical-align:top}
  .skin-row:hover{background:rgba(255,255,255,.02)}
  .time{color:var(--brand); font-weight:600; white-space:nowrap}
  .step{font-weight:600; color:#f5f7ff}
  .prod{color:#dfe4ff}
  .tag{display:inline-flex; align-items:center; padding:.18rem .5rem; border-radius:999px; font-size:.72rem; font-weight:600; letter-spacing:.2px; border:1px solid #22283a; color:#c9d2ee; background:#111523; margin-left:.5rem}
  .freq{color:#93b0ff}
  [data-tip]{position:relative; cursor:help}
  [data-tip]::after{content:attr(data-tip); position:absolute; left:0; top:calc(100% + 8px); width:min(420px, 92%); background:#0e111b; color:#e9ecf8; border:1px solid #20263a; padding:12px 14px; border-radius:12px; font-size:.9rem; line-height:1.35; box-shadow:0 10px 24px rgba(0,0,0,.35); opacity:0; transform:translateY(-4px); pointer-events:none; transition:opacity .16s ease, transform .16s ease; z-index:20}
  [data-tip]:hover::after{opacity:1; transform:translateY(0)}
  .notes{color:var(--muted); font-size:.92rem; padding:14px 16px}
  @media (max-width:720px){
    .skin-thead{display:none}
    .skin-table, .skin-tbody, .skin-row, .skin-td{display:block; width:100%}
    .skin-row{border-top:1px solid var(--line)}
    .skin-td{border-bottom:none; padding:12px 16px}
  }
</style>

<div class="skin-wrap">
  <div class="skin-title">Full-Body Skincare Routine (Dry skin + Hyperpigmentation)</div>
  <div class="skin-sub">Daily schedule with hover instructions. Focus: hydration, tone evening, and barrier repair for medium-to-deep skin. Use consistently for 6–12 months.</div>

  <div class="skin-card">
    <table class="skin-table" aria-label="Full body skincare routine">
      <thead class="skin-thead">
        <tr>
          <th style="width:18%">Time</th>
          <th style="width:35%">Step</th>
          <th>Product Examples</th>
        </tr>
      </thead>
      <tbody class="skin-tbody">
        <tr class="skin-row">
          <td class="skin-td time">Morning (7–9)</td>
          <td class="skin-td step" data-tip="Shower warm (not hot). Use hands or soft cloth. Pat dry, leave skin slightly damp to trap water.">Cleanse – Face & Body <span class="tag">daily</span></td>
          <td class="skin-td prod">Face: CeraVe Hydrating / La Roche-Posay Toleriane; Body: Dove Sensitive / CeraVe Hydrating Body Wash</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Morning</td>
          <td class="skin-td step" data-tip="2–3 drops on face/neck, avoid eyelids. Start every other morning if sensitive.">Vitamin C (Face) <span class="tag">daily</span></td>
          <td class="skin-td prod">The Ordinary AA 8% + Alpha-Arbutin 2% • LRP Pure Vitamin C10</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Morning</td>
          <td class="skin-td step" data-tip="Apply while skin is slightly damp. Niacinamide 5% to even tone; then moisturizer to seal.">Niacinamide / Moisturizer (Face) <span class="tag">daily</span></td>
          <td class="skin-td prod">Niacinamide 5% (TO/Paula’s Choice) • CeraVe Moisturizing Cream</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Morning</td>
          <td class="skin-td step" data-tip="Use 2 fingers’ length for face/neck; reapply q2h outdoors. Don’t forget ears & top of feet.">Sunscreen SPF 30–50 (Face/Exposed) <span class="tag">daily</span></td>
          <td class="skin-td prod">La Roche-Posay Anthelios • Black Girl Sunscreen • Supergoop Unseen</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Anytime</td>
          <td class="skin-td step" data-tip="2–3 L water/day. Re-moisturize hands after washing. Winter: bedroom humidifier for TEWL.">Hydration & Environment <span class="tag">habits</span></td>
          <td class="skin-td prod">Water bottle • Hand cream (CeraVe) • Bedroom humidifier</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Evening (8–10)</td>
          <td class="skin-td step" data-tip="Cleanse off SPF and sweat. If heavy SPF/makeup, double cleanse (oil balm → gentle cleanser).">Cleanse – Face & Body <span class="tag">daily</span></td>
          <td class="skin-td prod">Same as morning cleansers</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Evening</td>
          <td class="skin-td step" data-tip="For dark patches (upper lip, knees, ankles, neck). Start 3–4 nights/week, increase to nightly if tolerated. Thin layer.">Azelaic Acid / Alpha-Arbutin (Targets) <span class="tag">3–7×/wk</span></td>
          <td class="skin-td prod">Azelaic Acid 10–15% (TO/Paula’s Choice) • Alpha-Arbutin 2%</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Evening</td>
          <td class="skin-td step" data-tip="Seal moisture head-to-toe. Mix body oil into cream if very dry. Occlude heels with petrolatum + cotton socks.">Deep Moisturize – Face & Body <span class="tag">daily</span></td>
          <td class="skin-td prod">Face: CeraVe Cream • Body: NIVEA Rich Nourishing / Vaseline Cocoa Radiant • Petrolatum for feet</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">2–3×/week</td>
          <td class="skin-td step" data-tip="Prefer chemical exfoliation over scrubs. Face: lactic 5–10% or glycolic 5–8%. Body: AmLactin 12% on rough areas.">Chemical Exfoliation – Face & Body <span class="tag">evening</span></td>
          <td class="skin-td prod">The Ordinary Lactic 5–10% • Paula’s Choice AHA • AmLactin/Glytone body lotions</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">2–4×/week</td>
          <td class="skin-td step" data-tip="Optional. Pea-size for whole face after moisturizer (sandwich). Skip on AHA nights.">Retinoid (Face) <span class="tag">night</span> <span class="freq">optional</span></td>
          <td class="skin-td prod">Adapalene 0.1% (Differin) • Granactive Retinoid 2%</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Weekly</td>
          <td class="skin-td step" data-tip="Soak feet 10–15 min, apply urea 20–40% nightly for a week, then 2–3×/wk maintenance. Avoid blades.">Feet Focus: Exfoliate + Urea <span class="tag">1–3×/wk</span></td>
          <td class="skin-td prod">Urea 20–40% (Ureacin/Flexitol) • Soft pumice (gentle)</td>
        </tr>
        <tr class="skin-row">
          <td class="skin-td time">Weekly</td>
          <td class="skin-td step" data-tip="Gentle sugar scrub, SPF lip balm daytime, occlusive at night. Upper lip: tiny dab azelaic nightly until even.">Lips & Upper-Lip Care <span class="tag">1–2×/wk</span></td>
          <td class="skin-td prod">SPF lip balm • Petrolatum • Azelaic 10%</td>
        </tr>
      </tbody>
    </table>
    <div class="notes">
      • Patch test new actives. If irritation occurs, reduce frequency. • Expect visible improvements in 6–12 weeks; fuller tone evening in 6–12 months.
    </div>
  </div>
</div>

```

