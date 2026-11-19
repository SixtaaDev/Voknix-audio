# Installer Voknix Audio v1.1

## 1. Extraire le pack

Extrais tous les fichiers reçus dans un même dossier. Si le RAR est protégé, utilise le mot de passe communiqué séparément.

Le pack contient **Voknix Audio.exe**, **VBCABLE_Driver_Pack46.zip** et **LISEZ-MOI.txt**.

## 2. Installer VB-CABLE pour Discord

Si **CABLE Input** et **CABLE Output** sont déjà disponibles dans Windows, passe à l’étape suivante. Tu peux aussi utiliser le retour local **Echo** sans installer le pilote.

1. Fais un clic droit sur **VBCABLE_Driver_Pack46.zip**, puis **Extraire tout**.
2. Dans le dossier extrait, fais un clic droit sur **VBCABLE_Setup_x64.exe**, puis **Exécuter en tant qu’administrateur**.
3. Dans l’installateur de VB-Audio, clique sur **Install Driver** et attends la confirmation.
4. **Redémarre Windows**.
5. Si l’installation a sélectionné **CABLE Input** comme sortie Windows par défaut, remets ton casque ou tes haut-parleurs.

VB-CABLE est développé par **VB-Audio Software**. Son paquet officiel est fourni intact. C’est un **donationware** que tu peux soutenir par un don ou une licence auprès de l’éditeur. [Site officiel de VB-CABLE](https://www.vb-cable.com/) · [Guide du pilote](https://vb-audio.com/Cable/VBCABLE_ReferenceManual.pdf)

## 3. Régler Voknix Audio et Discord

1. Ouvre **Voknix Audio.exe** et sélectionne ton **micro physique** dans le panneau **Microphone**.
2. Choisis ton **casque** dans **Sortie Windows**. Ouvre **Toutes les sorties** si ton appareil ne figure pas encore dans les raccourcis.
3. Choisis un effet voix. **Voix grave** à une intensité modérée permet d’entendre facilement la différence en parlant.
4. Coche **Envoyer à Discord**. Laisse **Echo** décoché pour écouter uniquement le retour de Discord pendant le test.
5. Dans **Discord → Paramètres utilisateur → Voix et vidéo**, sélectionne **CABLE Output (VB-Audio Virtual Cable)** dans **Micro**, et ton casque dans **Haut-parleur**.
6. Lance **Test du micro**, parle, puis arrête le test. Pendant l’appel, laisse Voknix Audio ouvert et **Envoyer à Discord** coché. [Aide Discord](https://support.discord.com/hc/en-us/articles/360020641332-Mic-Testing)

## Dépannage

| Symptôme | À vérifier |
| --- | --- |
| La jauge du micro Discord reste vide | Vérifie que **Envoyer à Discord** reste coché, que ton micro est actif et que Discord écoute **CABLE Output**. |
| La jauge bouge mais tu n’entends pas le retour | Vérifie le périphérique **Haut-parleur** dans Discord et le volume de cette sortie dans Windows. |
| Un autre participant entend sa propre voix | Vérifie que Discord joue sur ton casque et utilise uniquement **CABLE Output** en entrée. Évite de diffuser l’appel sur des haut-parleurs proches du micro. |
| Tu veux revenir au micro habituel | Décoche **Envoyer à Discord** et sélectionne ton micro physique dans Discord. |
| Tu veux une voix sans effet tout en gardant le câble | Clique sur **Neutre** dans Voknix Audio. |

**Besoin d’aide ?** Contacte **Sixtaa sur Discord** en indiquant ta version de Voknix Audio et ce que tu vois dans **Voix et vidéo**.
