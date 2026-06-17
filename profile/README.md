<p align="center">
  <img src="https://raw.githubusercontent.com/wayremote/.github/main/assets/branding/logo/wayremote-logo-v1.svg" width="520">
</p>

<p align="center">

![MapLibre](https://img.shields.io/badge/MapLibre-Open%20Maps-00B86B?style=for-the-badge)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-Geospatial-7EBC6F?style=for-the-badge)
![Planetiler](https://img.shields.io/badge/Planetiler-Vector%20Tiles-00B86B?style=for-the-badge)
![Valhalla](https://img.shields.io/badge/Valhalla-Routing-00B86B?style=for-the-badge)

</p>

<p align="center">

![React](https://img.shields.io/badge/React-19.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React%20Native-Mobile-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Infrastructure-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</p>

<p align="center">

![Cloudflare](https://img.shields.io/badge/Cloudflare-CDN-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![PMTiles](https://img.shields.io/badge/PMTiles-Offline%20Maps-00B86B?style=for-the-badge)
![OSM](https://img.shields.io/badge/OpenStreetMap-Data-7EBC6F?style=for-the-badge)

</p>

<h1 align="center">Way Remote</h1>

<p align="center">
<b>Ocupe seu espaço no mundo.</b>
</p>

<p align="center">
Mobilidade • Rastreamento • Navegação Inteligente • Gestão Remota
</p>

---

## 🚀 Produtos

### 🧭 Way Remote Navigation

Aplicativo de navegação inteligente para mobilidade, logística e operações regionais.

### ⚙️ Way Remote Navigation SDK & API

Infraestrutura para desenvolvedores integrarem mapas, rotas, navegação e rastreamento.

### 📱 App Way Remote

Aplicativo Android e iOS para gestão remota de equipes, membros, dispositivos e pontos de interesse.

### 🖥️ Navigation Studio

Plataforma corporativa para administração de mapas, monitoramento operacional e relatórios.

---

## 🌐 Arquitetura

```text
OpenStreetMap
      │
      ▼
  Planetiler
      │
      ▼
   PMTiles
      │
      ▼
Cloudflare CDN
      │
      ▼
Way Remote Maps
      │
 ┌────┼────┐
 ▼    ▼    ▼

Studio SDK Mobile
