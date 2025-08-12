# zoran-legal-iact

**AI Act Checker** pour l’écosystème Zoran / QuantaGlottal©® — cartographie des exigences légales et génération de checklists de conformité.

---

## ✨ Fonctionnalités
- **Analyse des textes légaux** (IA Act, RGPD, normes sectorielles)
- **Cartographie des exigences** par catégorie et niveau de risque
- **Génération automatique de checklist** personnalisée
- **Export** des rapports (PDF, JSON, Markdown)
- **Suivi d’évolution réglementaire** (versioning des lois)
- **Interopérabilité** avec modules Zoran (benchmarks, injecteurs)

---

## 📦 Installation (développement)
```bash
pip install -e .


---

⚡ Exemple rapide

from zoran_legal_iact import ComplianceChecker

checker = ComplianceChecker()

# Analyser un système
report = checker.analyze_system(
    system_profile="zoran-agent-core",
    jurisdiction="EU"
)

# Générer une checklist
checklist = checker.generate_checklist(report)
print(checklist)


---

🧱 Structure suggérée

src/zoran_legal_iact/
  __init__.py
  checker.py           # moteur d'analyse
  mapping.py           # cartographie exigences -> checklist
  exporters.py         # export PDF/JSON/MD
  updater.py           # mise à jour des textes légaux
tests/
  test_checker.py
pyproject.toml
.gitignore
LICENSE
README.md


---

🧪 Tests

pytest -q


---

🔐 Éthique

Le zoran-legal-iact applique :

le principe vivant > humain

une interprétation prudente des exigences légales

la traçabilité complète des décisions de conformité



---

📜 Licence

MIT — voir LICENSE.


---

Auteur : Frédéric Tabary — Institut IA
Contact : 0645605023 — Canada, Montréal, France
INSTITUT🦋 IA INC., 7100-380, rue Saint-Antoine Ouest, Montréal (Québec) H2Y 3X7.# zoran-legal-iact
AI Act Checker: mapping exigences→checklist projet.
