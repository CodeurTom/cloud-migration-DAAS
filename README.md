# 🌐 Projet de Migration Cloud pour le Service des Inscriptions (DAAS) de l'Université de Lomé

## 📋 Introduction : Contexte actuel et Problématique
Le **DAAS** est le Service des inscriptions en ligne de l'Université de Lomé. Il gère les inscriptions des étudiants et stocke leurs dossiers académiques depuis leur inscription jusqu’à l’obtention de leur dernier diplôme. Ces sauvegardes sont cruciales pour la continuité des services administratifs à long terme.

### ⚙️ Infrastructure actuelle
Actuellement, le système est hébergé sur un serveur local situé au **CIC**.

### ❗ Problèmes identifiés
- **Scalabilité** limitée, rendant difficile la gestion des pics de charge lors des inscriptions.
- **Risques de panne** et de **perte de données**.
- **Coûts élevés** pour la maintenance de l'infrastructure locale.
- Difficulté à gérer les **pics de trafic** lors des périodes d’inscription.

---

## 🌥️ Pourquoi migrer vers le Cloud ?
### ✅ Avantages de la Migration
1. **Réduction des coûts** :
   - Élimine la maintenance des serveurs physiques.
   - Modèle de facturation **pay-as-you-go**, facturation basée sur l’utilisation réelle.

2. **Scalabilité** :
   - Capacité à augmenter rapidement les ressources pour gérer les pics d’inscription.
   - Flexibilité pour étendre le stockage sans infrastructure physique supplémentaire.

3. **Disponibilité** :
   - Amélioration de la disponibilité avec un **hébergement distribué**, réduisant les temps d’arrêt.

4. **Sécurité** :
   - Solutions robustes de **chiffrement**, **sauvegarde** et **protection contre les cyberattaques**.

5. **Flexibilité & Accessibilité** :
   - Accès aux systèmes depuis n’importe où, facilitant le **travail à distance**.
   - Centralisation des données pour améliorer la collaboration interne.

---

## 📊 Comparaison des Fournisseurs de Services Cloud

| Critère                  | DigitalOcean                     | AWS                            | Google Cloud Platform (GCP)   | Microsoft Azure              |
|--------------------------|----------------------------------|--------------------------------|-------------------------------|------------------------------|
| **Facilité d'utilisation** | Interface simple, documentation riche | Interface complexe mais riche  | Interface simplifiée          | Intégration Windows aisée   |
| **Coût**                 | Tarification claire, abordable  | Coûts variables, souvent élevés| Coût compétitif               | Tarification variable       |
| **Options de déploiement** | Droplets, Kubernetes            | VMs, Containers, Lambda        | GKE, App Engine               | App Services, Kubernetes    |
| **Scalabilité**          | Bonne pour PME                  | Très scalable, mais complexe   | Scalabilité avancée           | Scalabilité avec AKS        |
| **Sécurité**             | Chiffrement, Firewalls          | IAM, VPC, multi-layered        | IAM, VPC, Security Scanner    | Active Directory            |
| **Support & SLA**        | Support de base, SLA 99.99%     | Support payant, SLA 99.99%     | Support payant, SLA 99.99%    | Support payant, SLA 99.99%  |

### 🏆 **Choix final : DigitalOcean**
- **Pourquoi ?** :
  - Tarification **prévisible et compétitive**.
  - Facilité d'utilisation idéale pour une première **migration** vers le cloud.
  - Bon support pour les **PME** et les applications éducatives.

---

## 🚀 Feuille de Route pour la Migration

### **Phase 1 : Préparation**
- Analyse des besoins et évaluation des systèmes existants.
- Choix du fournisseur de service cloud.
- Formation des équipes techniques.

### **Phase 2 : Migration des Données**
- Sauvegarde des bases de données actuelles.
- Transfert sécurisé des données vers le cloud.

### **Phase 3 : Migration des Applications**
- Adaptation des applications en ligne à l’environnement cloud.
- Tests de performance et ajustements.

### **Phase 4 : Tests et Validation**
- Tests de charge pour vérifier la capacité à gérer les inscriptions massives.
- Vérification de la sécurité et de la conformité.

### **Phase 5 : Optimisation et Maintenance Continue**
- Suivi des performances et optimisation des coûts.
- Surveillance continue pour garantir la disponibilité des services.

---

## 📝 Conclusion
La migration vers le cloud permettra au **DAAS** d'améliorer la disponibilité, la sécurité et l'efficacité de ses services tout en réduisant les coûts à long terme. Cela facilitera également la gestion des inscriptions lors des périodes de forte demande.

---

## 📚 Ressources et Références
- [Documentation DigitalOcean](https://www.digitalocean.com/docs/)
- [Comparaison des fournisseurs Cloud](https://aws.amazon.com/compare/)
- [Guide de migration vers le Cloud](https://cloud.google.com/learn/)

---

## ✍️ Auteurs
- **Étudiant en Master Sécurité Informatique**
- **Université de Lomé**
