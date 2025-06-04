# 📗 **HueConnectRefactored** v1.0.0

<<<<<<< HEAD
> **Basé sur le plugin de** : *Zero_Hue*  
=======
> **Basé sur** : *Zerox_Hue*  
>>>>>>> 095daf68d404da6f6d44cdc3c12741a78cd29ae3
> **Refactorisé par** : *Robocnop*  
> **Objectif** : Faire fonctionner HueConnect avec les versions actuelles de NovaLife et le rendre plus léger que l'originale.

---

## 🔧 Fonctionnalités

- Envoie un message, **uniquement aux administrateurs**, lorsqu’un joueur se connecte.
- Inclut dans la notification :
  - Nom complet du joueur
  - Nom Steam
  - ID Steam
  - Indication si le joueur est admin (et son niveau d’admin)

---

## ⬇️ Installation

1. **Téléchargez** le fichier `HueConnectRefactored.dll`.
2. **Placez** `HueConnectRefactored.dll` dans le dossier `Plugins` de votre serveur NovaLife.
3. **Lancez** votre serveur, puis **éditez** le fichier `config.json` généré à côté de la DLL (dans le répertoire ayant le même nom) pour y ajouter votre webhook Discord :
   ```json
   {
     "LoginWebhookUrl": "https://discord.com/api/webhooks/…"
   }
4. Redémarrez le serveur pour appliquer la configuration.
5. Profitez : désormais, chaque connexion de joueur sera notifiée aux admins (et sur Discord, si configuré).
