<div align="center">

# `CD-S3E-2026`
### Ingénieur Systèmes Embarqués — Grade Apprenti

![Disponibilité](https://img.shields.io/badge/disponibilit%C3%A9-imm%C3%A9diate-2b8a3e?style=for-the-badge)
![Contrat](https://img.shields.io/badge/contrat-36%20mois-d9480f?style=for-the-badge)
![Mobilité](https://img.shields.io/badge/mobilit%C3%A9-france%20enti%C3%A8re-1B2A4A?style=for-the-badge)
![Statut](https://img.shields.io/badge/statut-en%20recherche%20active-blue?style=for-the-badge)

</div>

---

## Description générale

Composant polyvalent conçu pour opérer indifféremment sur les **couches basses** (VHDL, FPGA, RISC-V) et sur le **firmware temps réel** (C, STM32). Fabriqué avec un DUT Informatique, trempé via une Licence en Systèmes Embarqués, et actuellement recompilé en version Ingénieur (S3E, CESI, 2026–2029).

```text
Référence      : CD-S3E-2026
Conditionnement: Alternance / Apprentissage — 36 mois
Fabricant      : CESI Nanterre
Statut         : Disponible immédiatement
```

## Caractéristiques principales

- ⚡ Double culture matériel/logiciel native — sans couche d'abstraction
- 🔍 Diagnostic bas niveau : séquence de boot, développement de drivers, débogage de protocoles (UART / I2C / SPI)
- 📝 Documentation intégrée par défaut, pas une option
- 🔄 Faible latence de montée en compétence sur un nouvel outil ou langage
- 🛠️ Compatible STM32CubeIDE, ModelSim, QEMU, Proteus, Git

## Configuration des broches (Pinout)

```
                     ┌─────────────────┐
       RIGUEUR ──────┤                 ├────── UART / I2C / SPI
     C / PYTHON ──────┤     CD-S3E      ├────── STM32 / ARM Cortex-M
    VHDL / FPGA ──────┤      2026       ├────── DOCUMENTATION
     RÉSILIENCE ──────┤                 ├────── ESPRIT D'ÉQUIPE
                     └─────────────────┘
```

## Valeurs maximales absolues

| Paramètre | Symbole | Valeur | Unité |
|---|---|---|---|
| Session de debug continu | `T_DEBUG` | 12 | h avant café obligatoire |
| Pression deadline | `P_DDL` | 72 | h en fonctionnement stable |
| Tolérance à l'échec avant nouvelle tentative | `N_RETRY` | ∞ | cycles |
| Délai de réponse à une offre sérieuse | `T_RESP` | < 24 | h |

## Caractéristiques électriques / fonctionnelles

| Paramètre | Min | Typ | Max |
|---|---|---|---|
| Autonomie sur un projet embarqué | Encadré | Semi-autonome | Autonome |
| Compréhension matériel ↔ logiciel | Driver | Système | Architecture |
| Curiosité technique | — | Élevée | Ne s'arrête jamais |

## Applications

- Systèmes de contrôle-commande et automatismes critiques
- Firmware temps réel sur microcontrôleurs (STM32 / ARM Cortex-M)
- Conception et validation numérique (FPGA / VHDL)
- Test, validation et diagnostic d'interfaces embarquées

## Dernières compilations (projets)

- 🚗 **Rover autonome — STM32F411RE** : pilotes en C, capteurs ultrasoniques/infrarouges, pilotage moteurs PWM en temps réel
- 🔧 **Conception numérique FPGA / VHDL** : modules logiques, simulation ModelSim, étude timing/architecture RISC-V
- 🖥️ **Noyau xv6** : implémentation d'appels système, pagination mémoire, analyse de l'ordonnanceur (QEMU)
- 🖼️ **Éditeur Mini-PNG (C)** : manipulation de fichiers binaires, format structuré en blocs

## Informations de commande

```text
$ contact --email cheikhdiagne5222@gmail.com --tel "+33 7 80 53 61 79"
$ connect --linkedin linkedin.com/in/diagne-cheikh
$ voir --portfolio portfolio-iota-weld-52.vercel.app
```

<div align="center">

*Datasheet Rev 1.0 — Août 2026 — CESI Nanterre, S3E*

</div>
