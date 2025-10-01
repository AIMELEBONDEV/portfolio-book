<!-- COMPÉTENCES TECHNIQUES -->
# 

<div class="skills-section">
  <h2>Compétences Techniques</h2>

  <div class="skill">
    <span>Analyse & Visualisation (Power BI, Tableau, Seaborn, Matplotlib)</span>
    <div class="progress-bar">
      <div class="progress" data-width="90%"><span>90%</span></div>
    </div>
  </div>

  <div class="skill">
    <span>Bases de données (SQL, PostgreSQL, MySQL, BigQuery)</span>
    <div class="progress-bar">
      <div class="progress" data-width="85%"><span>85%</span></div>
    </div>
  </div>

  <div class="skill">
    <span>Python (Data Analysis, Machine Learning, NLP)</span>
    <div class="progress-bar">
      <div class="progress" data-width="80%"><span>80%</span></div>
    </div>
  </div>

  <div class="skill">
    <span>Cloud & Data Engineering (GCP, Dataflow, BigQuery, Docker)</span>
    <div class="progress-bar">
      <div class="progress" data-width="75%"><span>75%</span></div>
    </div>
  </div>

  <div class="skill">
    <span>Microsoft Fabric & DBT</span>
    <div class="progress-bar">
      <div class="progress" data-width="60%"><span>60%</span></div>
    </div>
  </div>
</div>

<!-- AUTRES OUTILS -->
<div class="other-tools-section">
  <h2>Autres Connaissances</h2>
  <p>Expériences ponctuelles ou bases solides sur :</p>
  <ul>
    <li>Langages : R, Java</li>
    <li>Big Data : Spark, Hadoop, Kafka</li>
    <li>Machine Learning : Random Forest, XGBoost, Deep Learning</li>
    <li>NoSQL : MongoDB</li>
    <li>Automatisation : Power Automate, Power Apps</li>
    <li>Visualisation complémentaire : Looker Studio & LookML</li>
  </ul>
</div>

<!-- COMPÉTENCES MÉTIER / SOFT SKILLS -->
<div class="soft-skills-section">
  <h2>Soft Skills & Langues</h2>
  <ul>
    <li>Analyse & Synthèse : transformer des données complexes en insights clairs.</li>
    <li>Communication : à l’aise avec les équipes métiers et les managers.</li>
    <li>Autonomie & Proactivité : capable de mener des projets de bout en bout.</li>
    <li>Résolution de problèmes : réduction des anomalies grâce à l’automatisation.</li>
    <li>Langues : Français (natif), Anglais (B2), Ewe, Yoruba, Haoussa.</li>
  </ul>
</div>

<style>
  .skills-section, .soft-skills-section, .other-tools-section {
    max-width: 800px;
    margin: 30px auto;
    padding: 20px;
    font-family: "Segoe UI", Arial, sans-serif;
    background: #fdfdfd;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }

  .skills-section h2, 
  .soft-skills-section h2, 
  .other-tools-section h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #004aad;
  }

  .skill {
    margin-bottom: 18px;
  }

  .skill span {
    display: block;
    margin-bottom: 6px;
    font-weight: bold;
    color: #333;
  }

  .progress-bar {
    background: #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    height: 26px;
  }

  .progress {
    height: 100%;
    background: linear-gradient(90deg, #004aad, #1e90ff);
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff; /* Pourcentage en blanc */
    font-size: 0.9rem;
    font-weight: bold;
    border-radius: 8px 0 0 8px;
    width: 0; /* Départ à 0 */
    transition: width 1.8s ease-in-out;
  }

  .progress span {
    position: relative;
    z-index: 2;
  }

  .soft-skills-section ul, 
  .other-tools-section ul {
    list-style: none;
    padding: 0;
  }

  .soft-skills-section li, 
  .other-tools-section li {
    margin: 8px 0;
    padding-left: 8px;
    font-size: 1rem;
    color: #444;
    line-height: 1.4;
  }

  .soft-skills-section li::before, 
  .other-tools-section li::before {
    content: "✔ ";
    color: #004aad;
    font-weight: bold;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", () => {
    const bars = document.querySelectorAll(".progress");

    const observer = new IntersectionObserver((entries, obs) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          const bar = entry.target;
          const finalWidth = bar.getAttribute("data-width");
          bar.style.width = finalWidth;
          obs.unobserve(bar); // ne rejoue pas l’animation après
        }
      });
    }, { threshold: 0.5 }); // déclenche à 50% visible

    bars.forEach(bar => {
      observer.observe(bar);
    });
  });
</script>



