

<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Theory@XFEL — Program</title>
<style>
:root {
  --ink: #263746;
  --blue: #1e5b7a;
  --pale-blue: #eaf2f6;
  --line: #d6e0e6;
  --muted: #637582;
  --break: #f4f6f7;
}
* { box-sizing: border-box; }
body {
  margin: 0;
  color: var(--ink);
  background: #fff;
  font: 14px/1.35 system-ui, -apple-system, BlinkMacSystemFont,
        "Segoe UI", sans-serif;
}
header {
  padding: 1.5rem 1rem;
  background: var(--blue);
  color: white;
}
.page-header {
  color: white;
  text-align: center;
  background-color: white;
  background-image: url("./images/FELheader.png");
  background-repeat: no-repeat;
  background-size: cover;
  margin: 0 auto;

}
.wrap {
  width: min(1120px, calc(100% - 2rem));
  margin: 0 auto;
}
h1 {
  margin: 0 0 .35rem;
  font-size: clamp(1.5rem, 3vw, 2.2rem);
  line-height: 1.15;
}
header p { margin: 0; opacity: .92; }
main { padding: 1.25rem 0 2rem; }
h2 {
  margin: 0 0 .3rem;
  color: var(--blue);
  font-size: 1.4rem;
}
.intro {
  margin: 0 0 1rem;
  color: var(--muted);
}
.day { margin: 1.2rem 0 1.6rem; }
.day h3 {
  margin: 0;
  padding: .5rem .8rem;
  background: var(--pale-blue);
  color: var(--blue);
  border-left: 4px solid var(--blue);
  font-size: 1.05rem;
}
.table-scroll {
  overflow-x: auto;
  border: 1px solid var(--line);
  border-top: 0;
}
table {
  width: 100%;
  border-collapse: collapse;
  min-width: 650px;
}
th, td {
  padding: .42rem .6rem;
  text-align: left;
  vertical-align: top;
  border-bottom: 1px solid var(--line);
}
th {
  background: #f7f9fa;
  color: var(--muted);
  font-size: .76rem;
  text-transform: uppercase;
  letter-spacing: .035em;
}
tr:last-child td { border-bottom: 0; }
td.time {
  white-space: nowrap;
  font-variant-numeric: tabular-nums;
  width: 115px;
}
.speaker { min-width: 165px; }
.speaker strong {
  display: block;
  font-weight: 650;
}
.affiliation {
  display: block;
  margin-top: 3px;
  color: var(--muted);
  font-size: .85rem;
}
.talk { min-width: 250px; }
tr.break-row td {
  background: var(--break);
  color: #4d606c;
  font-style: italic;
}
tr.break-row td:first-child { font-style: normal; }
footer {
  border-top: 1px solid var(--line);
  padding: 1rem 0 1.5rem;
  color: var(--muted);
  font-size: .85rem;
}
@media (max-width: 600px) {
  header { padding: 1.3rem .5rem; }
  main { padding-top: 1rem; }
  .wrap { width: calc(100% - 1rem); }
}
@media print {
  header {
    background: white;
    color: var(--ink);
    padding: 1rem 0;
    border-bottom: 2px solid var(--blue);
  }
  header p { color: var(--muted); }
  .wrap { width: 100%; }
  main { padding: .5rem 0; }
  .day { break-inside: avoid; margin: 1rem 0; }
  th { background: #f2f5f7 !important; }
}
</style>
</head>
<body>

<main class="wrap">
  <h2>Scientific program</h2>
  <section class="day">
    <h3>Tuesday, 3 November 2026</h3>
    <div class="table-scroll">
    <table>
      <thead>
        <tr><th>Time</th><th>Speaker</th><th>Talk title / activity</th></tr>
      </thead>
      <tbody>
        <tr class="break-row">
          <td class="time">12:30–13:35</td>
          <td class="speaker"><strong>Welcome + Coffee</strong></td>
          <td class="talk">Welcome + Coffee</td>
        </tr>
        <tr>
          <td class="time">13:35–13:40</td>
          <td class="speaker"><strong>Andre Gomes</strong><span class="affiliation">University of Lille</span></td>
          <td class="talk">Welcome from organization</td>
        </tr>
        <tr>
          <td class="time">13:40–13:50</td>
          <td class="speaker"><strong>Miquel Huix Rotllant, Marie Labeye</strong></td>
          <td class="talk">Presentation of the GDR XFEL</td>
        </tr>
        <tr>
          <td class="time">13:50–14:20</td>
          <td class="speaker"><strong>Morgane Vacher</strong><span class="affiliation">University of Nantes</span></td>
          <td class="talk">X-ray spectroscopy to probe photo-induced processes in molecules and attochemistry</td>
        </tr>
        <tr>
          <td class="time">14:20–14:50</td>
          <td class="speaker"><strong>Yorick Lassman</strong><span class="affiliation">UCT Prague</span></td>
          <td class="talk">A Minimal Model for Simulating X-ray Induced Ultrafast Electron Dynamics in Complex Environments</td>
        </tr>
        <tr>
          <td class="time">14:50–15:20</td>
          <td class="speaker"><strong>Paul Albrecht</strong><span class="affiliation">KU Leuven</span></td>
          <td class="talk">Effects of Nuclear Motion on Molecular HHG Spectra: A Coupled Nuclear-Electron Quantum Dynamics Approach</td>
        </tr>
        <tr class="break-row">
          <td class="time">15:20–15:50</td>
          <td class="speaker"><strong>Coffee Break</strong></td>
          <td class="talk">Coffee Break</td>
        </tr>
        <tr>
          <td class="time">15:50–16:20</td>
          <td class="speaker"><strong>Petr Slavíček</strong><span class="affiliation">UCT Prague</span></td>
          <td class="talk">When Agreement Is Not Enough: Theory and Experiment in Ultrafast Molecular Dynamics</td>
        </tr>
        <tr>
          <td class="time">16:20–16:50</td>
          <td class="speaker"><strong>Woojin Park</strong><span class="affiliation">TU Dortmund</span></td>
          <td class="talk">Deciphering the internal conversion and triplet formation in thymine via time-resolved multicenter X-ray photoelectron spectroscopy</td>
        </tr>
        <tr>
          <td class="time">16:50–17:20</td>
          <td class="speaker"><strong>Francesco Segatta</strong><span class="affiliation">University of Bologna</span></td>
          <td class="talk">Time-resolved (X-ray) Spectroscopy with COBRAMM: from quantum chemistry to spectra &amp; insight</td>
        </tr>
        <tr class="break-row">
          <td class="time">17:20–17:30</td>
          <td class="speaker"><strong>Coffee Break</strong></td>
          <td class="talk">Coffee Break</td>
        </tr>
        <tr>
          <td class="time">17:30–18:00</td>
          <td class="speaker"><strong>Jakub Vokrouhlicky</strong><span class="affiliation">UCT Prague</span></td>
          <td class="talk">Investigation of Circular Dichroism in amino acids using soft X-ray absorption</td>
        </tr>
        <tr>
          <td class="time">18:00–18:30</td>
          <td class="speaker"><strong>Lukas Konecny</strong><span class="affiliation">Slovak Academy of Sciences</span></td>
          <td class="talk">Relativistic calculations of X-ray spectroscopies in ReSpect</td>
        </tr>
        <tr class="break-row">
          <td class="time">18:30</td>
          <td class="speaker"><strong>Free time</strong></td>
          <td class="talk">Free time</td>
        </tr>
      </tbody>
    </table>
    </div>
  </section>

  <section class="day">
    <h3>Wednesday, 4 November 2026</h3>
    <div class="table-scroll">
    <table>
      <thead>
        <tr><th>Time</th><th>Speaker</th><th>Talk title / activity</th></tr>
      </thead>
      <tbody>
        <tr>
          <td class="time">09:00–09:30</td>
          <td class="speaker"><strong>Arjan Berger</strong><span class="affiliation">University of Toulouse</span></td>
          <td class="talk">Photoemission spectroscopy from the multichannel Dyson equation</td>
        </tr>
        <tr>
          <td class="time">09:30–10:00</td>
          <td class="speaker"><strong>Fábris Kossoski</strong><span class="affiliation">University of Toulouse</span></td>
          <td class="talk">Bayesian optimization of non-Hermitian parameters for efficient electronic resonance calculations</td>
        </tr>
        <tr>
          <td class="time">10:00–10:30</td>
          <td class="speaker"><strong>Thomas Jagau</strong><span class="affiliation">KU Leuven</span></td>
          <td class="talk">Modeling Auger spectra with complex scaling</td>
        </tr>
        <tr class="break-row">
          <td class="time">10:30–11:15</td>
          <td class="speaker"><strong>Coffee Break</strong></td>
          <td class="talk">Coffee Break</td>
        </tr>
        <tr>
          <td class="time">11:15–11:45</td>
          <td class="speaker"><strong>Martin Procházka</strong><span class="affiliation">UCT Prague</span></td>
          <td class="talk">Coherent X-ray Scattering from Solvent-Delocalized States: A Computational Study of Aqueous Iodide</td>
        </tr>
        <tr>
          <td class="time">11:45–12:15</td>
          <td class="speaker"><strong>Michelangelo Tagliavini</strong><span class="affiliation">European XFEL</span></td>
          <td class="talk">Ultrafast transient iron Kα RXES of model spin-crossover molecule</td>
        </tr>
        <tr>
          <td class="time">12:15–12:45</td>
          <td class="speaker"><strong>Oriol Vendrell</strong><span class="affiliation">University of Heidelberg</span></td>
          <td class="talk">Decoherence and core-hole localization following x-ray excitation</td>
        </tr>
        <tr class="break-row">
          <td class="time">12:45–14:15</td>
          <td class="speaker"><strong>Lunch</strong></td>
          <td class="talk">Lunch</td>
        </tr>
        <tr>
          <td class="time">14:15–14:45</td>
          <td class="speaker"><strong>Martin Crhan</strong><span class="affiliation">Charles University, Prague</span></td>
          <td class="talk">Attosecond time-delays in molecules containing heavy atoms</td>
        </tr>
        <tr>
          <td class="time">14:45–15:15</td>
          <td class="speaker"><strong>Robert Polly</strong><span class="affiliation">KIT</span></td>
          <td class="talk">Understanding XANES spectra and RIXS maps of actinides with ab initio calculations</td>
        </tr>
        <tr>
          <td class="time">15:15–15:45</td>
          <td class="speaker"><strong>Stéphane Carniato</strong><span class="affiliation">Sorbonne University</span></td>
          <td class="talk">Electronegativity: the art of attracting electrons probed by Resonant Inelastic X-ray Scattering</td>
        </tr>
        <tr class="break-row">
          <td class="time">15:45–16:30</td>
          <td class="speaker"><strong>Coffee Break</strong></td>
          <td class="talk">Coffee Break</td>
        </tr>
        <tr>
          <td class="time">16:30–17:00</td>
          <td class="speaker"><strong>Sarai Folkestad</strong><span class="affiliation">NTNU Trondheim</span></td>
          <td class="talk">Multilevel coupled cluster theory for X-ray spectroscopy</td>
        </tr>
        <tr>
          <td class="time">17:00–17:30</td>
          <td class="speaker"><strong>Marc-Alias Rodriguez</strong><span class="affiliation">University Rovira i Virgili</span></td>
          <td class="talk">A computationally efficient method for accurate K-edge X-ray Absorption Spectroscopy. Mixed-reference Spin-Flip Time-Dependent Density Functional Theory</td>
        </tr>
        <tr>
          <td class="time">17:30–18:00</td>
          <td class="speaker"><strong>Cristina Sobrino</strong><span class="affiliation">UCT Prague</span></td>
          <td class="talk">Time-resolved X-ray photoelectron spectroscopy of cyclobutanone</td>
        </tr>
        <tr class="break-row">
          <td class="time">19:30</td>
          <td class="speaker"><strong><a href="https://www.penichearchimede.fr" target="_blank"> Peniche Archimede</a></strong></td>
          <td class="talk">Workshop dinner (Façade de l'Esplanade, 59000 Lille)</td>
        </tr>
      </tbody>
    </table>
    </div>
  </section>

  <section class="day">
    <h3>Thursday, 5 November 2026</h3>
    <div class="table-scroll">
    <table>
      <thead>
        <tr><th>Time</th><th>Speaker</th><th>Talk title / activity</th></tr>
      </thead>
      <tbody>
        <tr>
          <td class="time">09:00–09:30</td>
          <td class="speaker"><strong>Alessandro Nicolaou</strong><span class="affiliation">SOLEIL</span></td>
          <td class="talk">Excitons in hexagonal boron nitride: from equilibrium properties to ultrafast dynamics</td>
        </tr>
        <tr>
          <td class="time">09:30–10:00</td>
          <td class="speaker"><strong>Laura Urquiza</strong><span class="affiliation">University of Milan</span></td>
          <td class="talk">Excitons in photodoped hBN: first-principles calculations of pump-probe X-ray spectra</td>
        </tr>
        <tr>
          <td class="time">10:00–10:30</td>
          <td class="speaker"><strong>David Ayuso</strong><span class="affiliation">Imperial College London</span></td>
          <td class="talk">Efficient chiral discrimination with chiral and achiral light: from table-top nonlinear optics to opportunities at XFELs</td>
        </tr>
        <tr class="break-row">
          <td class="time">10:30–11:15</td>
          <td class="speaker"><strong>Coffee Break</strong></td>
          <td class="talk">Coffee Break</td>
        </tr>
        <tr>
          <td class="time">11:15–11:45</td>
          <td class="speaker"><strong>Antonio Picón</strong><span class="affiliation">CSIC</span></td>
          <td class="talk">From Chemical Shifts to Charge Dynamics: Insights from XFEL-Based Core-Level Spectroscopy</td>
        </tr>
        <tr>
          <td class="time">11:45–12:15</td>
          <td class="speaker"><strong>Iulia Emilia Brumboiu</strong><span class="affiliation">University of Torun</span></td>
          <td class="talk">Can resonant inelastic X-ray scattering help elucidate the photodegradation of organic materials used in photovoltaics?</td>
        </tr>
        <tr>
          <td class="time">12:15–12:45</td>
          <td class="speaker"><strong>Eleonora Luppi</strong><span class="affiliation">Sorbonne University</span></td>
          <td class="talk">How Electronic Structure Shapes Spectroscopic Signals</td>
        </tr>
        <tr class="break-row">
          <td class="time">12:45–12:50</td>
          <td class="speaker"><strong>Closing</strong></td>
          <td class="talk">Closing</td>
        </tr>
        <tr class="break-row">
          <td class="time">12:50–14:00</td>
          <td class="speaker"><strong>Lunch box + departure</strong></td>
          <td class="talk">Lunch box + departure</td>
        </tr>
      </tbody>
    </table>
    </div>
  </section>
</main>


</body>
</html>



