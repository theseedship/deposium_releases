<div align="center">
  <img src="assets/deposium.svg" width="112" alt="DEPOSIUM®" />
  <h1>DEPOSIUM® Desktop</h1>
  <p>Vos documents, votre recherche, vos modèles.<br />Your documents, your search, your models.</p>
</div>

**FR** — L’application DEPOSIUM® connectée au SaaS, avec TurboV3 et inference embarqués. Modèles ONNX inclus ; LLM locaux facultatifs, téléchargés depuis l’application.

**EN** — The DEPOSIUM® desktop app, connected to the SaaS with bundled TurboV3 and inference engines. ONNX models included; optional local LLMs downloadable in the app.

Fermer la fenêtre conserve l’application dans la barre de menus / zone de notification si disponible ; **Quitter** arrête le runtime. · Closing the window keeps the app in the tray when available; **Quit** stops the runtime.

0.2.42 — Les modèles natifs inactifs sont déchargés puis rechargés à la demande. · Idle native models unload and reload on demand.

### Télécharger · Download

| Plateforme · Platform | Version | Téléchargement · Download | Détails · Details |
| --- | --- | --- | --- |
| **macOS — Apple Silicon** | 0.2.42 | [**DMG**](https://github.com/theseedship/deposium_releases/releases/download/v0.2.42-installed-solid.42-memory/DEPOSIUM-0.2.42.dmg) | [Notes](https://github.com/theseedship/deposium_releases/releases/tag/v0.2.42-installed-solid.42-memory) |
| **Windows — x64** | 0.2.42 | [**EXE**](https://github.com/theseedship/deposium_releases/releases/download/v0.2.42-portable.41719225846.1.win32/DEPOSIUM-0.2.42.exe) | [Notes](https://github.com/theseedship/deposium_releases/releases/tag/v0.2.42-portable.41719225846.1.win32) |
| **Linux — x64** | 0.2.42 | [**Installateur · Installer**](https://github.com/theseedship/deposium_releases/releases/download/v0.2.42-portable.41719225846.1.linux/DEPOSIUM-0.2.42.tar.gz) | [Notes](https://github.com/theseedship/deposium_releases/releases/tag/v0.2.42-portable.41719225846.1.linux) |

**FR** — Préversions : runtime Mac vérifié (BGE seul, déchargement et reprise) ; installation sur Windows/Linux encore à qualifier. L’embedding des requêtes SaaS et TGS restent serveur ; le rerank BGE peut tourner sur le poste. Mac non notarié : [procédure d’ouverture Apple](https://support.apple.com/fr-fr/guide/mac-help/-mh40616/mac).

**EN** — Preview builds: Mac runtime verified (BGE-only loading, unloading and reloading); Windows/Linux installation validation pending. SaaS query embedding and TGS remain server-side; BGE reranking can run locally. Mac is not notarized: [Apple’s opening instructions](https://support.apple.com/guide/mac-help/mh40616/mac).

Votre bibliothèque et les modèles téléchargés restent hors de l’application. Aucun secret fournisseur embarqué. · Your library and downloaded models stay outside the app. No bundled provider credentials.

[Signature et validation éditeur · Publisher signing](https://github.com/theseedship/deposium_desktop/blob/main/docs/AUTOMATIC_RELEASE_SIGNING.md) — Mac : signature ad hoc, sans notarisation ; Windows/Linux : non signés. La signature éditeur et la qualification antivirus restent à finaliser. · Mac: ad-hoc signing, no notarization; Windows/Linux: unsigned. Publisher signing and antivirus validation remain pending.
