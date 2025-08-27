# Changelog

- Affichage de la version dans l'UI : utilisation de `chrome.runtime.getManifest().version` au lieu d'une valeur codée en dur (évite les décalages).
## 3.0.0 - 2025-08-27
- Migration vers **Manifest V3** (conversion `browser_action`→`action`, déplacement des hôtes dans `host_permissions`, MAJ `web_accessible_resources`).
- Remplacement de `chrome.extension.getURL` par `chrome.runtime.getURL` (compatibilité MV3).
- Suppression de l'usage de `eval()` dans `jquery-datetimepicker_1.6.3.js` via parseur sécurisé (CSP MV3).
- Vérification : aucune requête XHR synchrone détectée.
- Modifié par **Naxedim**.
