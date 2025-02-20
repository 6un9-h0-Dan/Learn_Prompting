---
sidebar_position: 0
---

# 🟢 Aperçu

Prévenir l'injection de prompt (prompt injection) peut être extrêmement difficile, et il existe peu de défenses robustes contre cela(@crothers2022machine)(@goodside2021gpt). Cependant, certaines solutions de bon sens existent. Par exemple, si votre application n'a pas besoin de produire du texte libre, ne permettez pas de tels résultats. Il existe de nombreuses manières différentes de défendre un prompt. Nous discuterons ici de certaines des plus courantes.

Ce chapitre couvre des stratégies supplémentaires de bon sens comme filtrer les mots. Il traite également des stratégies d'amélioration de prompt (défense par instruction, post-prompting, différentes façons d'encadrer les entrées utilisateur, et le balisage XML). Enfin, nous discutons de l'utilisation d'un LLM pour évaluer la sortie et de quelques approches plus spécifiques au modèle.
