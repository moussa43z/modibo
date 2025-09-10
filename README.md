<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio SISR - Ton Nom</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1581093588401-22d38c9d907b') center/cover;
      color: white;
      padding: 5rem 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      font-size: 1.3rem;
    }
    nav {
      background: #1a73e8;
      padding: 1rem;
      text-align: center;
      position: sticky;
      top: 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffcc00;
    }
    section {
      padding: 3rem 2rem;
      max-width: 1100px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-size: 2rem;
      color: #1a73e8;
    }
    .skills, .projects, .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
    footer {
      background: #1a73e8;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ton Nom</h1>
    <p>Étudiant BTS SIO SISR | Administration Systèmes & Réseaux</p>
  </header>

  <nav>
    <a href="#about">À propos</a>
    <a href="#skills">Compétences</a>
    <a href="#projects">Projets</a>
    <a href="#gallery">Galerie</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>À propos</h2>
    <p>Je suis étudiant en BTS SIO option SISR. Passionné par les réseaux, l'administration systèmes, la cybersécurité et le DevOps, je développe mes compétences au travers de projets scolaires, professionnels et personnels.</p>
  </section>

  <section id="skills">
    <h2>Compétences</h2>
    <div class="skills">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31" alt="Linux">
        <h3>Linux</h3>
        <p>Administration de serveurs Ubuntu, Debian, CentOS. Sécurisation et automatisation avec scripts Bash.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1612831455543-3c2161edec29" alt="Windows Server">
        <h3>Windows Server</h3>
        <p>Gestion d'Active Directory, DNS, DHCP, GPO et configuration de services réseau sécurisés.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581091012184-5c7b6a4e3b4c" alt="Virtualisation">
        <h3>Virtualisation</h3>
        <p>VMware, VirtualBox, Proxmox pour créer et administrer des environnements multi-VM.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581090700227-4c4f4e4a42db" alt="Cisco">
        <h3>Réseaux Cisco</h3>
        <p>Configuration de routeurs et switches, VLAN, routage statique et dynamique, sécurité réseau.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1603791445824-0050bd436b1d" alt="Sécurité">
        <h3>Sécurité</h3>
        <p>Mise en place de pare-feu, VPN, certificats SSL, surveillance et sauvegardes.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1591696331115-2f62d220d09f" alt="Scripts">
        <h3>Scripts</h3>
        <p>Automatisation avec Bash, PowerShell et Python pour simplifier l’administration système.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projets</h2>
    <div class="projects">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1593642634315-48f5414c3ad9" alt="AD">
        <h3>Active Directory</h3>
        <p>Installation et configuration d’un domaine Windows Server 2019 avec gestion des utilisateurs et stratégies de groupe.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581092334608-4e9a5e7f7f1f" alt="Infrastructure Réseau">
        <h3>Infrastructure Réseau</h3>
        <p>Configuration complète d’un réseau Cisco (VLAN, routage, DHCP, sécurité avec ACL).</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1518770660439-4636190af475" alt="Serveur Linux">
        <h3>Serveur Linux</h3>
        <p>Installation d’un serveur web Apache avec base MySQL, sécurisation via pare-feu UFW et certificats SSL.</p>
      </div>
    </div>
  </section>

  <section id="gallery">
    <h2>Galerie</h2>
    <div class="gallery">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c" alt="Schéma Réseau">
        <p>Schéma réseau créé pour un projet de segmentation VLAN.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c" alt="Teamwork">
        <p>Collaboration sur un projet SISR avec mise en place d’un serveur partagé.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1605902711622-cfb43c4437b5" alt="Monitoring">
        <p>Dashboard de supervision système et réseau avec Grafana.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">Email : <a href="mailto:ton.email@example.com">ton.email@example.com</a></p>
    <p style="text-align:center;">LinkedIn : <a href="#">linkedin.com/in/tonprofil</a></p>
    <p style="text-align:center;">GitHub : <a href="#">github.com/tonprofil</a></p>
    <p style="text-align:center;"><a href="CV.pdf" target="_blank">Télécharger mon CV (PDF)</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Ton Nom - Portfolio BTS SIO SISR</p>
  </footer>

</body>
</html>
