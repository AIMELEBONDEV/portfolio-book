# 

<style>
.education-experience-section {
  max-width: 900px;
  margin: 0 auto 50px auto;
  font-family: "Segoe UI", Arial, sans-serif;
}

/* Boutons d'ancrage */
.nav-buttons {
  text-align: center;
  margin-bottom: 25px;
}
.nav-buttons button {
  background-color: #004aad;
  color: #fff;
  font-weight: bold;
  padding: 10px 20px;
  margin: 0 10px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s;
}
.nav-buttons button:hover {
  background-color: #1e90ff;
}

/* Blocs distincts */
.block {
  background: #ffffff;
  padding: 25px;
  margin-bottom: 40px;
  border-radius: 12px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
}

.block h2 {
  text-align: center;
  color: #004aad;
  margin-bottom: 25px;
}

.education-item, .experience-item {
  border-left: 4px solid #004aad;
  padding-left: 15px;
  margin-bottom: 25px;
}

.education-item h3, .experience-item h3 {
  color: #1e90ff;
  margin: 0 0 5px 0;
  font-size: 1.15rem;
}

.education-item .school, .experience-item .date {
  font-weight: bold;
  color: #333;
}

.education-item .details, .experience-item .details {
  color: #444;
  line-height: 1.5;
}

ul {
  margin: 5px 0 0 20px;
}

/* Smooth scroll */
html {
  scroll-behavior: smooth;
}
</style>

<div class="education-experience-section">

<!-- Boutons pour naviguer -->
<div class="nav-buttons">
  <button onclick="document.getElementById('formation').scrollIntoView({behavior:'smooth'});">Formation</button>
  <button onclick="document.getElementById('experience').scrollIntoView({behavior:'smooth'});">Expériences</button>
</div>

<!-- Bloc Formation -->
<div class="block" id="formation">
<h2> Formation </h2>

<div class="education-item">
<h3>Master Big Data et Analyse Sociale</h3>
<p class="school">CNAM, Paris, France</p>
<p class="date">Septembre 2024 – Juin 2025</p>
<p class="details">Analyse de données, Machine Learning, Data Engineering, Power BI, Cloud (GCP), Docker</p>
</div>

<div class="education-item">
<h3>Master 1 & 2 - Chargé d'Études Économiques et Statistiques</h3>
<p class="school">Université de Caen, Normandie, France</p>
<p class="date">Septembre 2021 – Juin 2023</p>
<p class="details">Économétrie, méthodes quantitatives, statistiques appliquées, programmation (R, Python, SQL)</p>
</div>

<div class="education-item">
<h3>Licence Économie et Statistique appliquée</h3>
<p class="school">Université de Bourgogne, Dijon, France</p>
<p class="date">Septembre 2020 – Juin 2021</p>
<p class="details">Économétrie, méthodes quantitatives, statistiques appliquées, programmation (R, Python)</p>
</div>
</div>

<!-- Bloc Expériences -->
<div class="block" id="experience">
<h2> Expériences Professionnelles</h2>

<div class="experience-item">
<h3>Data Analyst - L’Oréal France</h3>
<p class="date">Septembre 2024 – Août 2025, Paris, France</p>
<p class="details">
Centralisation et fiabilisation des données de ventes dans le Data Lake (GCP) :
<ul>
<li>Automatisation des intégrations de fichiers (>100k lignes/semaine) vers BigQuery.</li>
<li>Contrôle qualité des données avec réduction de 30% des anomalies.</li>
<li>Création de dashboards Power BI pour 50+ utilisateurs métiers.</li>
<li>Définition de KPIs de fiabilité (exhaustivité de 92% à 99%).</li>
<li>Support utilisateurs et formation pour une exploitation optimale des dashboards.</li>
</ul>
</p>
</div>

<div class="experience-item">
<h3>Chargé d’étude & Data Analyst - CA du Cotentin</h3>
<p class="date">Janvier 2023 – Juin 2023, Cherbourg-en-Cotentin, France</p>
<p class="details">
Analyse de l’impact des meublés touristiques sur l’économie locale et le logement :
<ul>
<li>Intégration et fiabilisation des annonces Airbnb et Booking.</li>
<li>Conception de dashboards dynamiques (R/Python).</li>
<li>Analyse territoriale pour identifier impacts sur le marché du logement et l’économie locale.</li>
<li>Production de rapports stratégiques pour orienter les politiques locales.</li>
</ul>
</p>
</div>
</div>

</div>
