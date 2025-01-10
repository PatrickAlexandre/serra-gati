# Interface Visuelle pour la serre de Sartrouville ☔️

Ce projet est une interface dynamique qui récupère et affiche les prévisions météorologiques pour Sartrouville à l'aide de l'API Open-Meteo. Il intègre diverses bibliothèques et frameworks modernes pour créer une interface engageante et attrayante.

## Fonctionnalités 
- **Prévisions météo** ☀️⛈️: Récupère les données météo pour Sartrouville grâce à l'API Open-Meteo v1.
- **Graphiques interactifs** 📊: Affiche les tendances météorologiques à l'aide de {Charts.js et ApexCharts.js}.
- **Interface moderne** 🏢: Stylisée avec {Bootstrap, Tailwind CSS et UIkit} pour une interface réactive et élégante.
- **Typographie et icônes améliorées** 🎨: Inclut {Google Fonts et les icônes Google Material} pour un rendu professionnel.
- **Google Earth 3D**

# Technologies utilisées

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.tailwindcss.com"></script>

<script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
```

# Comparatif des technologies CSS et JavaScript

| **Technologie**         | **<script> ou <style>** | **Téléchargements par mois** | **Utilisateurs total mondial** |
|--------------------------|-------------------------|------------------------------|---------------------------------|
| **Tailwind CSS**         | `<style>`              | ~12 millions                 | ~1.5 million                   |
| **Bootstrap 5**          | `<style>`              | ~15 millions                 | ~3 millions                    |
| **ApexCharts**           | `<script>`             | ~500 000                     | ~100 000                       |
| **Chart.js**             | `<script>`             | ~1.5 million                 | ~500 000                       |
| **Material Design Lite** | `<style>`              | ~100 000                     | ~50 000                        |


### APIs
- **Open-Meteo API**
  - Endpoint: `https://api.open-meteo.com/v1/forecast`
  - Coordonnées : Latitude `48.950363`, Longitude `2.174544` (Ces coordonnées correspondent à l'emplacement du Centre Technique Municipal **CTM** de Sartrouville, situé à cette adresse.)

## Utilisation 🎢

1. Ouvrez `index.html` dans votre navigateur ou utilisez un serveur de développement local.
2. Le tableau de bord récupérera automatiquement les données météorologiques pour Sartrouville à l'aide des coordonnées prédéfinies.
3. Consultez les tendances météorologiques via des graphiques interactifs et une interface moderne et réactive.

## Aperçu du code 🔬

### Script principal
```html
<script>
    const apiUrl = "https://api.open-meteo.com/v1/forecast";
    const latitude = 48.9438; // Latitude pour Sartrouville
    const longitude = 2.1641; // Longitude pour Sartrouville
</script>
```

### Structure des fichiers
- `index.html` : Fichier HTML principal contenant la structure et la mise en page.
- `styles/` : Répertoire contenant les fichiers CSS (Bootstrap, Tailwind, UIkit).
- `scripts/` : Répertoire contenant les fichiers JavaScript pour les intégrations Charts.js et ApexCharts.js.

## Contribution 📚

Les contributions sont les bienvenues ! Veuillez créer un Google Forms et l'imprimer sous la forme d'un QR Code.

## Licence 🔒

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

---
---

## Bibliothèques HTML :

## Graphiques
- [D3.js](https://d3js.org) - Bibliothèque puissante pour des visualisations dynamiques basées sur des données.

- [Chart.js](https://www.chartjs.org) - Bibliothèque simple pour créer des graphiques interactifs.
- [ApexCharts](https://apexcharts.com) - Bibliothèque moderne pour des graphiques réactifs et interactifs.

## CSS
- [Material Design Lite](https://getmdl.io) - Framework CSS léger pour intégrer les principes du Material Design dans les sites Web.

- [Bootstrap](https://getbootstrap.com) - Framework CSS pour créer des interfaces utilisateur réactives.
- [Tailwind CSS](https://tailwindcss.com) - Bibliothèque utilitaire pour styliser rapidement des éléments.

## JavaScript
- [jQuery](https://jquery.com) - Simplifie la manipulation du DOM et des animations.

- [React](https://reactjs.org) - Bibliothèque pour construire des interfaces utilisateur interactives.
- [Vue.js](https://vuejs.org) - Framework progressif pour les interfaces utilisateur.

---

## Notes
- Combinez **Bootstrap** avec **Chart.js** pour des projets réactifs et interactifs.
- Utilisez **Tailwind CSS** et **Vue.js** pour des projets modernes et légers.

---

### Graphiques
- **Charts.js**
- **ApexCharts.js**

### Frameworks CSS
- **Bootstrap**
- **Tailwind CSS**
- **UIkit**

### Outils supplémentaires
- **Google Materials** (icônes et outils de design)
- **Google Fonts** (typographie)

---