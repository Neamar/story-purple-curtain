---
triggers:
    hard:
        condition: storylines.scumbags.negociation == true
        weight: 3

actions:
    "Raconter": 
        operations:
            - storylines.scumbags.spiled = true
    "Quitter les lieux":
        operations:
            - storylines.sumbags.back_out = true
---

- "J'ai des informations intéressantes sur une de vos employées. Je pense qu'elles valent bien 300 nuyens."
- "OK. Voilà ce qu'on va faire: je te donne 100 nuyens, tu me déballes tes infos, et si je considère qu'elles valent ce que tu dis, je te donne le reste. Sinon, je demande à Lurch de t'expliquer que mon temps est précieux, et tu peux garder les 100 nuyens pour les bandages. Si tu trouves finalement que tu m'as peut-être dérangé pour rien, tu dégages maintenant et je veux plus jamais voir ta gueule."

Le nain ne semble pas vouloir discuter du sujet, et attend clairement une décision. Vous pouvez choisir de:
  * Prendre les 100 nuyens et espérer que l'info vaut le coup
  * Décider que finalement, tant pis: vous passez sur les 300 nuyens et vous trouverez autre chose pour payer le loyer...
