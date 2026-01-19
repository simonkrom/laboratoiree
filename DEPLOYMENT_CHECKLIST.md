# ✅ Checklist de Déploiement - Render

Suivez cette checklist avant de déployer :

## 1️⃣ **Préparation Git**
- [ ] Repository GitHub créé et connecté
- [ ] Fichier `.env` est dans `.gitignore` ✅
- [ ] `git push` effectué vers `main`

## 2️⃣ **Sécurité**
- [ ] JWT_SECRET généré et configuré ✅ (369cbb481259f6d9aa2029463e4b390572477ac823430abb8908f6268c2705ab)
- [ ] Clés Supabase sécurisées ✅
- [ ] CORS configuré pour production ✅

## 3️⃣ **Backend (Node.js + Socket.IO)**
- [ ] Créer service Web sur Render
- [ ] Ajouter variables d'environnement
- [ ] Vérifier build command: `cd server && npm install`
- [ ] Vérifier start command: `cd server && npm start`
- [ ] URL backend générée: `https://laboratoire-backend.onrender.com`

## 4️⃣ **Frontend (HTML/CSS/JS Statique)**
- [ ] Créer service Static Site sur Render
- [ ] Publish Directory: `./` (racine)
- [ ] URL frontend générée: `https://laboratoire-frontend.onrender.com`

## 5️⃣ **Post-Déploiement**
- [ ] Tester l'API: https://laboratoire-backend.onrender.com/api/health
- [ ] Tester Socket.IO de la page coursier
- [ ] Vérifier connexions utilisateurs
- [ ] Tester temps réel (commandes, localisation)

---

## 📋 Variables d'environnement à ajouter sur Render

```
JWT_SECRET=369cbb481259f6d9aa2029463e4b390572477ac823430abb8908f6268c2705ab
SUPABASE_URL=https://buahbmjfzsrowshpsjdr.supabase.co
SUPABASE_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
SUPABASE_SECRET_KEY=sb_secret_18jNCgBm0ufh-E5PgIzgiA_JkyviqSV
```

---

## 🚀 URLs Finales

```
Frontend:   https://laboratoire-frontend.onrender.com
Backend:    https://laboratoire-backend.onrender.com
API:        https://laboratoire-backend.onrender.com/api
```

---

Consultez [DEPLOYMENT_RENDER.md](./DEPLOYMENT_RENDER.md) pour le guide complet.
