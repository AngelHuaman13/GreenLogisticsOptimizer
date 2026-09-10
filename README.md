# Green Logistics Optimizer 🌱

Aplicación web para optimizar rutas de entrega y reducir emisiones de carbono en la industria logística.

## 📋 Características

- ✅ Optimización de rutas (algoritmo TSP)
- ✅ Cálculo de emisiones de CO2
- ✅ Visualización en Google Maps
- ✅ Dashboard con reportes
- ✅ Autenticación de usuarios
- ✅ Histórico de rutas

## 🛠️ Tecnologías

| Componente | Tecnología |
|-----------|-----------|
| **Frontend** | Angular 17+ |
| **Backend** | Spring Boot 3+ |
| **Base de Datos** | MySQL 8+ |
| **Mapas** | Google Maps API |

## 🚀 Inicio Rápido

### Requisitos Previos
- Node.js 18+
- Java 17+
- MySQL 8+
- Git

### Instalación

#### 1. Clonar Repositorio
```bash
git clone https://github.com/AngelHuaman13/GreenLogisticsOptimizer.git
cd GreenLogisticsOptimizer
```

#### 2. Base de Datos
```bash
mysql -u root -p
source database/schema.sql
```

#### 3. Backend
```bash
cd backend
mvn clean install
mvn spring-boot:run
```
Backend correrá en: `http://localhost:8080`

#### 4. Frontend
```bash
cd frontend
npm install
ng serve
```
Frontend correrá en: `http://localhost:4200`

## 📖 Documentación

- [API REST](./docs/API.md)
- [Diagrama ER](./docs/ER.md)
- [Manual de Usuario](./docs/MANUAL.md)

## 👨‍💻 Autor

**Ángel Oscar Moscoso Huamán**
- GitHub: [@AngelHuaman13](https://github.com/AngelHuaman13)
- Email: angel@example.com

## 📜 Licencia

MIT License - Ver LICENSE.md

## 🌍 Impacto Ambiental

Este proyecto busca reducir emisiones de carbono en logística. Mediante optimización de rutas, se estima:
- 🚗 20-30% menos km recorridos
- ⛽ 20-30% menos combustible
- 🌍 2-3 toneladas CO2 ahorradas por cada 1000 entregas

---

**Última actualización:** Septiembre 2024
