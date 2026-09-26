<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Formation Agents IA Terrain — Parcours interactif complet</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400;600;700&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--ink:#1C1B19;--paper:#F2EEE6;--ochre:#C97A2B;--teal:#2B6E6E;--purple:#6B4E8C;--line:#D8D1C0;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box}html,body{height:100%}
body{margin:0;background:var(--paper);color:var(--ink);font-family:'IBM Plex Sans',sans-serif;line-height:1.55}
h1,h2,h3{font-family:'Fraunces',serif;margin:0;font-weight:600}
.wrap{max-width:760px;margin:0 auto;padding:0 22px 60px}
header{padding:40px 0 20px}
h1{font-size:clamp(24px,5vw,32px)}
.tag{font-size:12px;text-transform:uppercase;letter-spacing:.05em;color:var(--ink);background:#EDEAE3;display:inline-block;padding:4px 10px;border-radius:20px;margin-bottom:12px}
.progress{height:6px;background:#EDEAE3;border-radius:3px;overflow:hidden;margin:18px 0}
.progress-bar{height:100%;background:var(--ink);width:0%;transition:width .3s}
.chapter{border:1px solid var(--line);border-radius:8px;margin-bottom:18px;overflow:hidden}
.chapter.locked{opacity:.4;pointer-events:none}
.ch-head{background:#EDEAE3;padding:14px 20px;font-size:18px;font-family:'Fraunces',serif}
.ch-body{padding:18px 20px}
.ch-body h4{font-size:13px;text-transform:uppercase;color:#8A8472;letter-spacing:.03em;margin:14px 0 5px}
.ch-body p,.ch-body li{font-size:15px}
table{width:100%;border-collapse:collapse;margin:10px 0;font-size:13.5px}
th,td{border:1px solid var(--line);padding:7px 9px;text-align:left}
th{background:var(--ink);color:#fff;font-weight:600}
.quote{background:#F8F5EE;border-left:3px solid var(--line);padding:10px 14px;font-size:14px;font-style:italic;margin:8px 0;white-space:pre-line}
.def b.term{color:var(--teal)}
.exo{background:#EAE3F0;border-radius:4px;padding:12px 16px;margin-top:10px;font-size:14px}
.warn{background:#F3E9DC;border-radius:4px;padding:12px 16px;margin-top:10px;font-size:14px}
.sol{margin-top:0}
.sol summary{cursor:pointer;font-weight:600;font-size:13.5px;color:var(--teal);padding:8px 0}
.sol[open] summary{margin-bottom:4px}
.sol-body{background:#E7EEEC;border-radius:4px;padding:10px 14px;font-size:13.5px;font-style:italic}
.howto{background:#F8F5EE;border:1px dashed var(--line);border-radius:4px;padding:12px 14px;margin:8px 0;font-size:13.5px}
.howto a{color:var(--teal)}
.quiz{background:#EFE6D8;border-radius:6px;padding:16px 18px;margin-top:16px}
.quiz p{font-weight:500;margin:0 0 10px}
.quiz label{display:block;background:#fff;border:1px solid var(--line);border-radius:4px;padding:9px 12px;margin-bottom:8px;font-size:14px;cursor:pointer}
.quiz button{background:var(--ink);color:#fff;border:none;padding:10px 18px;border-radius:4px;font-size:14px;cursor:pointer}
.fb{font-size:13px;margin-top:8px;font-weight:500}
.fb.ok{color:var(--teal)}.fb.no{color:#B0442C}
.done{display:none;color:var(--teal);font-weight:600;font-size:14px;margin-top:8px}
</style>
</head>
<body>
<div class="wrap">
<header>
  <p class="tag">Parcours interactif — 10 chapitres</p>
  <h1>Choisir, construire, prospecter, facturer, grandir</h1>
  <p style="font-size:14px;color:#4A453C;margin-top:8px">Version pratique avec quiz et corrigés : chaque chapitre se débloque une fois le précédent validé.</p>
  <div class="progress"><div class="progress-bar" id="pbar"></div></div>
</header>

<div class="chapter" id="c1">
  <div class="ch-head">1 — Le bon état d'esprit et le choix du secteur</div>
  <div class="ch-body">
    <p>Vous ne vendez pas « de l'intelligence artificielle » — vous vendez une solution à un problème précis. Gardez cette phrase : <em>« Je vends du temps gagné et de l'argent récupéré. »</em></p>
    <h4>Méthode de décision (3 critères, dans l'ordre)</h4>
    <ol><li><b>Accès relationnel</b> — ai-je un contact direct dans ce secteur ?</li><li><b>Longueur du cycle de décision</b> — court (boutique) ou long (mine) ?</li><li><b>Disponibilité à apprendre le vocabulaire</b> — suis-je prêt à maîtriser quelques termes techniques ?</li></ol>
    <div class="warn"><b>Piège fréquent —</b> choisir le secteur qui « semble » le plus rentable (souvent la mine) plutôt que celui où l'accès réel existe.</div>
    <div class="exo"><b>Exercice —</b> Listez 8 proches et notez pour chacun : boutique / mine-pétrole / aucun lien, puis identifiez votre secteur de départ.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : Awa (cousine, boutique Instagram) → accès=2, cycle court=2, vocabulaire=2 → total 6. Jean (ex-collègue, technicien sur site minier) → accès=1, cycle court=0, vocabulaire=1 → total 2. On retient le total le plus élevé : Awa → démarrage par l'Agent Boutique.</div></details>
    <div class="quiz">
      <p>Quiz — Quel est le facteur le PLUS important pour choisir son secteur de départ ?</p>
      <label><input type="radio" name="q1" value="a"> La taille du marché mondial</label>
      <label><input type="radio" name="q1" value="b"> Avoir un contact direct dans ce secteur</label>
      <label><input type="radio" name="q1" value="c"> La couleur du logo de l'entreprise</label>
      <button onclick="check('q1','b','c1','c2')">Valider</button>
      <div class="fb" id="fb-c1"></div>
    </div>
    <div class="done" id="done-c1">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c2">
  <div class="ch-head">2 — Comprendre son marché local</div>
  <div class="ch-body">
    <p>Avant de vendre, observez ce qui existe déjà : repérez 3 boutiques et 3 sociétés minières/sous-traitants près de chez vous, et notez comment elles communiquent aujourd'hui.</p>
    <h4>Ce qu'il faut observer précisément</h4>
    <ul><li>Le délai de réponse moyen aux messages clients</li><li>La présence ou non d'un catalogue clair</li><li>Les commentaires publics de clients mécontents</li></ul>
    <div class="exo"><b>Exercice —</b> Créez une liste de 6 prospects avec une note sur leur point faible observé.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : Boutique « Chic Style » — répond en moyenne 4h après le message → point faible : lenteur de réponse. « Cosméto Plus » — pas de liste de prix visible, chaque client doit demander → point faible : absence de catalogue clair. Répétez ce diagnostic pour les 6 prospects.</div></details>
    <div class="quiz">
      <p>Quiz — Quel signal indique qu'une boutique a besoin d'un Agent Boutique ?</p>
      <label><input type="radio" name="q2" value="a"> Elle répond lentement aux messages clients</label>
      <label><input type="radio" name="q2" value="b"> Elle a beaucoup d'abonnés</label>
      <button onclick="check('q2','a','c2','c3')">Valider</button>
      <div class="fb" id="fb-c2"></div>
    </div>
    <div class="done" id="done-c2">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c3">
  <div class="ch-head">3 — Construire un Agent Boutique sans code</div>
  <div class="ch-body">
    <h4>Le vocabulaire à maîtriser</h4>
    <p class="def"><b class="term">Le canal</b> — l'application par laquelle le client contacte la boutique (WhatsApp, Messenger, Instagram). <b>À quoi ça sert :</b> c'est le point d'entrée unique où l'agent reçoit et envoie ses messages. WhatsApp est souvent prioritaire car déjà utilisé spontanément par les clients.</p>
    <p class="def"><b class="term">L'intention</b> — le besoin réel caché derrière un message, quelle que soit sa formulation exacte (« C'est combien ? » et « Prix svp » = même intention). <b>À quoi ça sert :</b> regrouper des dizaines de formulations sous une seule réponse-type, au lieu d'écrire une réponse pour chaque phrase possible.</p>
    <p class="def"><b class="term">Le flow</b> — le chemin que suit la conversation, du message reçu jusqu'à la réponse. <b>À quoi ça sert :</b> plan de circulation reliant chaque intention détectée à une réponse ou action précise, construit visuellement sans coder.</p>
    <p class="def"><b class="term">La base de données</b> — l'endroit où sont stockées les infos consultées ou enregistrées par l'agent (catalogue, stock, commandes). <b>À quoi ça sert :</b> mémoire externe de l'agent, souvent un simple tableur relié à l'outil.</p>
    <h4>Outils, où les obtenir et comment démarrer</h4>
    <div class="howto"><b>WhatsApp Business</b> (gratuit) — téléchargez-le sur le Play Store/App Store en cherchant exactement « WhatsApp Business » (business.whatsapp.com). Une fois installé : Paramètres → Outils professionnels → activez « Message d'accueil » et « Message d'absence » ; créez des « Réponses rapides » (ex. /prix) pour les questions fréquentes.</div>
    <div class="howto"><b>ManyChat</b> (flow builder, gratuit pour démarrer) — créez un compte sur manychat.com via « Sign Up Free ». Puis : Automation → Flows → « + New Flow » ; ajoutez un bloc « Keyword Trigger » par intention (ex. « prix », « dispo », « commande ») relié à un bloc réponse ; cliquez « Publish » pour activer.</div>
    <div class="howto"><b>Google Sheets</b> (gratuit avec un compte Google, sheets.google.com) — créez un classeur « Catalogue », avec les colonnes : Nom produit, Prix, Variante, Stock, Mot-clé. Reliez-le ensuite à ManyChat via l'intégration « Google Sheets » du menu Apps/Integrations.</div>
    <h4>Construire l'agent en 5 étapes</h4>
    <ol>
      <li><b>Cartographier les questions réelles</b> — récupérez 30 à 50 messages déjà reçus, classez-les par thème.</li>
      <li><b>Construire le catalogue</b> — voir Google Sheets ci-dessus.</li>
      <li><b>Dessiner le flow minimum</b> — 3 branches : question produit, suivi de commande, transfert humain.</li>
      <li><b>Configurer et tester</b> — 10 messages types avant mise en production.</li>
      <li><b>Ajouter la relance de panier</b> — message automatique si pas de réponse sous 24h (bloc « Delay » puis envoi, dans ManyChat ou Make).</li>
    </ol>
    <div class="warn"><b>Vigilance —</b> un agent qui répond « je ne comprends pas » plus d'une fois sur cinq fait fuir le client.</div>
    <div class="exo"><b>Exercice —</b> À partir de 30 messages réels d'un commerçant, listez les intentions et dessinez le flow en 3 branches.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : « Disponible en quelle taille ? », « Vous livrez où ? », « Combien ça coûte ? » → intention « Question produit ». « J'ai commandé hier, c'est prêt ? » → « Suivi de commande ». « Bonjour » seul → « Aucune correspondance », transféré à un humain. Flow : mots-clés prix/taille/livraison → réponse catalogue ; mots-clés commande/suivi → statut ; reste → transfert humain.</div></details>
    <div class="quiz">
      <p>Quiz — Quelle est la première étape pour construire un Agent Boutique ?</p>
      <label><input type="radio" name="q3" value="a"> Cartographier les questions réellement posées par les clients</label>
      <label><input type="radio" name="q3" value="b"> Choisir la couleur du chatbot</label>
      <button onclick="check('q3','a','c3','c4')">Valider</button>
      <div class="fb" id="fb-c3"></div>
    </div>
    <div class="done" id="done-c3">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c4">
  <div class="ch-head">4 — Construire un Agent Mine (suivi de production)</div>
  <div class="ch-body">
    <h4>Le vocabulaire à maîtriser</h4>
    <ul><li><b>Tonnage journalier</b> — quantité extraite ou traitée sur une période</li><li><b>Taux de disponibilité machine</b> — proportion du temps où l'équipement est réellement opérationnel</li><li><b>Arrêts machine</b> — durée et cause de chaque interruption</li><li><b>Taux de récupération</b> — rapport entre quantité utile et quantité traitée</li></ul>

    <h4>Étape 1 — Digitaliser le relevé</h4>
    <p><b>Pourquoi :</b> un relevé papier se perd, n'est pas visible en temps réel, et ne peut pas être additionné automatiquement. Un formulaire numérique règle ces trois problèmes dès la saisie.</p>
    <div class="howto"><b>Comment (Google Forms, connexion correcte)</b> — forms.google.com → « Vierge » → renommez « Relevé quotidien — [site] » → ajoutez les champs Date, Tonnage du jour, Durée d'arrêt (min), Cause de l'arrêt (liste déroulante), Incident (texte), Nom de l'agent → onglet « Réponses » → cliquez l'icône verte Sheets pour créer la feuille liée automatiquement → bouton « Envoyer » pour obtenir le lien à diffuser sur WhatsApp.</div>
    <div class="howto"><b>Comment (KoBoToolbox, zones à connexion faible)</b> — kobotoolbox.org → compte gratuit → « New » → « Build from scratch » → mêmes champs → « Deploy ». Sur les téléphones des agents, installez l'app « KoboCollect » (Play Store) pour remplir hors-ligne ; la synchronisation se fait dès qu'une connexion revient.</div>

    <h4>Étape 2 — Centraliser automatiquement</h4>
    <p><b>Pourquoi :</b> recopier chaque relevé à la main prend du temps et introduit des erreurs de saisie.</p>
    <p><b>Comment :</b> déjà actif si vous avez suivi l'étape 1 avec Google Forms — chaque réponse crée automatiquement une ligne dans la feuille liée, sans action supplémentaire.</p>

    <h4>Étape 3 — Générer le rapport quotidien</h4>
    <p><b>Pourquoi :</b> un tableau de données brutes n'est pas lisible rapidement ; un rapport calcule les écarts automatiquement.</p>
    <div class="howto"><b>Comment</b> — dans Google Sheets, ajoutez un onglet « Tableau de bord ». Formule de moyenne mobile : <code>=MOYENNE(plage 7 derniers tonnages)</code>. Formule d'alerte : <code>=SI(tonnage_jour&lt;moyenne7j*0,8;"ALERTE";"OK")</code>.</div>

    <h4>Étape 4 — Ajouter l'alerte automatique</h4>
    <p><b>Pourquoi :</b> un tableau que personne ne consulte activement ne sert à rien ; l'alerte pousse l'information au bon moment.</p>
    <div class="howto"><b>Comment (Make, make.com, compte gratuit)</b> — « Create a new scenario » → module déclencheur « Google Sheets – Watch Rows » sur l'onglet Tableau de bord → filtre : continuer seulement si Statut = « ALERTE » → action « Gmail – Send an Email » (ou WhatsApp Business Cloud API si déjà connectée) vers le responsable → activez le scénario (interrupteur « ON »).</div>

    <div class="warn"><b>Vigilance —</b> ne jamais présenter cet outil comme un contrôle du personnel : il doit rester une aide à la décision pour le responsable de site.</div>
    <div class="exo"><b>Exercice —</b> Concevez un formulaire de relevé quotidien pour un site fictif, avec au moins 6 champs et un seuil d'alerte.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Champs : Date ; Tonnage du jour (t) ; Durée d'arrêt (min) ; Cause (panne / maintenance / manque d'approvisionnement / autre) ; Incident observé ; Nom de l'agent. Seuil d'alerte : tonnage du jour &lt; 80% de la moyenne des 7 derniers jours, OU durée d'arrêt cumulée &gt; 90 minutes → statut « ALERTE ».</div></details>
    <div class="quiz">
      <p>Quiz — Comment doit être présenté l'Agent Mine aux équipes terrain ?</p>
      <label><input type="radio" name="q4" value="a"> Comme un outil de surveillance individuelle des employés</label>
      <label><input type="radio" name="q4" value="b"> Comme une aide à la décision pour le responsable de site</label>
      <button onclick="check('q4','b','c4','c5')">Valider</button>
      <div class="fb" id="fb-c4"></div>
    </div>
    <div class="done" id="done-c4">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c5">
  <div class="ch-head">5 — Prospection : scripts et objections</div>
  <div class="ch-body">
    <p>Les 5 premiers clients servent avant tout à produire une <b>preuve de résultat chiffrée</b>, pas du profit immédiat.</p>
    <h4>Script boutique</h4>
    <div class="quote">"Bonjour [nom], je remarque que votre boutique répond aux clients manuellement. Je propose un service qui répond automatiquement aux questions produits et relance les paniers abandonnés. Essai gratuit d'un mois, sans engagement — intéressé(e) ?"</div>
    <p><b>Comment l'envoyer concrètement :</b> ouvrez WhatsApp, ouvrez la conversation avec le prospect, collez le texte en remplaçant [nom] par son prénom réel, envoyez en message individuel — jamais en diffusion groupée, qui obtient un taux de réponse bien plus faible.</p>
    <h4>Script mine/pétrole</h4>
    <div class="quote">"Bonjour [nom], je propose un suivi quotidien automatisé de votre production, avec alertes en cas de retard. Test gratuit d'un mois."</div>
    <h4>Objections courantes — réponse et mise en œuvre concrète</h4>
    <table>
      <tr><th>Objection</th><th>Réponse</th><th>Comment le faire</th></tr>
      <tr><td>Pas le temps</td><td>L'essai ne demande rien de vous.</td><td>Proposez une démo de 5 min en vidéo WhatsApp où vous manipulez votre propre téléphone.</td></tr>
      <tr><td>Trop technique</td><td>Rien à gérer techniquement.</td><td>Montrez en direct une conversation déjà fonctionnelle chez un autre client (ou une démo test).</td></tr>
      <tr><td>Pas d'intérêt</td><td>Calculons le temps/argent perdu.</td><td>Demandez : « Combien de messages/jour ? » puis « Combien de minutes pour y répondre ? ». Multipliez par les jours ouvrés du mois pour un chiffre concret.</td></tr>
    </table>
    <div class="exo"><b>Exercice —</b> Envoyez le script adapté à votre secteur à 3 prospects réels aujourd'hui, et notez leurs objections telles quelles.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : Prospect 1 (vêtements) → « pas le temps » → démo proposée le lendemain matin. Prospect 2 (téléphones) → aucune objection, rendez-vous pris. Prospect 3 (cosmétiques) → « pas intéressée » → calcul fait : 15 messages/jour × 10 min × 26 jours = 65h/mois passées à répondre manuellement — a suscité un nouvel intérêt.</div></details>
    <div class="quiz">
      <p>Quiz — Un prospect dit « je n'ai pas le temps ». Quelle est la meilleure réponse ?</p>
      <label><input type="radio" name="q5" value="a"> Insister sur le prix bas</label>
      <label><input type="radio" name="q5" value="b"> Rappeler que l'essai ne demande rien de son côté</label>
      <button onclick="check('q5','b','c5','c6')">Valider</button>
      <div class="fb" id="fb-c5"></div>
    </div>
    <div class="done" id="done-c5">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c6">
  <div class="ch-head">6 — Prix, contrat et négociation</div>
  <div class="ch-body">
    <p>Le prix doit refléter la valeur gagnée ou économisée par le client — pas être fixé au hasard.</p>
    <table>
      <tr><th>Secteur</th><th>Modèle</th><th>Fourchette</th></tr>
      <tr><td>Boutique</td><td>Abonnement + commission</td><td>25 000–50 000 F/mois + 5%</td></tr>
      <tr><td>Mine</td><td>Abonnement mensuel</td><td>100 000–300 000 F/mois</td></tr>
      <tr><td>Géologie</td><td>Facturation à la mission</td><td>50 000–150 000 F/rapport</td></tr>
    </table>
    <p><b>Comment rédiger le contrat concrètement :</b> ouvrez un document vierge (Google Docs ou Word), reprenez 4 titres — service précis, prix, durée/préavis, responsabilités — remplissez chacun en 1-2 phrases, faites signer par une photo de signature manuscrite envoyée sur WhatsApp si aucune signature électronique n'est disponible.</p>
    <div class="warn"><b>Vigilance —</b> face à une négociation serrée, ne baissez jamais un prix définitivement : proposez un tarif de lancement limité dans le temps.</div>
    <div class="exo"><b>Exercice —</b> Calculez la valeur apportée à votre prochain prospect et fixez un prix en conséquence.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : boutique reçoit 20 messages/jour, 8 min de réponse chacun = 2h40/jour, soit ~69h/mois. Même à 500F/heure, la valeur dépasse 34 000F/mois — un tarif de 30 000F/mois est donc justifié.</div></details>
    <div class="quiz">
      <p>Quiz — Un client négocie fort dès le départ. Que faire ?</p>
      <label><input type="radio" name="q6" value="a"> Baisser définitivement le prix</label>
      <label><input type="radio" name="q6" value="b"> Proposer un tarif de lancement limité dans le temps</label>
      <button onclick="check('q6','b','c6','c7')">Valider</button>
      <div class="fb" id="fb-c6"></div>
    </div>
    <div class="done" id="done-c6">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c7">
  <div class="ch-head">7 — Livrer un service que le client garde</div>
  <div class="ch-body">
    <p>La première livraison détermine si le client reste après l'essai gratuit. Trois règles : livrez exactement ce qui a été promis, expliquez simplement, prévoyez un suivi à 7 jours.</p>
    <div class="quote">"Voici votre agent en place : [explication en 3 phrases]. Je reviens vers vous dans une semaine pour ajuster ensemble."</div>
    <p><b>Comment organiser ce suivi :</b> notez un rappel à J+7 dans votre calendrier téléphone, préparez à l'avance 2 questions : « Avez-vous remarqué une différence dans vos ventes ou votre temps de réponse ? » et « Y a-t-il une question à laquelle l'agent n'a pas su répondre ? ».</p>
    <div class="warn"><b>Vigilance —</b> survendre une fonctionnalité qui n'existe pas encore est l'erreur la plus coûteuse.</div>
    <div class="exo"><b>Exercice —</b> Rédigez votre propre modèle de message de livraison, adapté à votre secteur.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple (boutique) : « Bonjour Awa, votre Agent Boutique est actif depuis ce matin : il répond automatiquement aux questions de prix et de disponibilité, et relance les clients qui n'ont pas terminé leur commande après 24h. Je repasse vous voir vendredi pour ajuster ensemble si besoin. »</div></details>
    <div class="quiz">
      <p>Quiz — Que ne faut-il jamais faire à la livraison ?</p>
      <label><input type="radio" name="q7" value="a"> Survendre une fonctionnalité qui n'existe pas encore</label>
      <label><input type="radio" name="q7" value="b"> Prévoir un suivi à 7 jours</label>
      <button onclick="check('q7','a','c7','c8')">Valider</button>
      <div class="fb" id="fb-c7"></div>
    </div>
    <div class="done" id="done-c7">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c8">
  <div class="ch-head">8 — Analyse de données géologiques et pétrolières</div>
  <div class="ch-body">
    <p>Ce chapitre enseigne une méthode d'organisation et de synthèse de données — pas une formation d'ingénieur géologue.</p>
    <h4>Types de données rencontrés</h4>
    <ul><li>Relevés de forage (lithologie, profondeur)</li><li>Résultats d'échantillons (teneurs, analyses)</li><li>Données de production pétrolière (débit, pression)</li><li>Rapports de terrain manuscrits</li></ul>
    <h4>La chaîne de traitement en 5 étapes</h4>
    <ol>
      <li><b>Collecte structurée</b> — date, lieu, agent, unité pour chaque donnée.</li>
      <li><b>Centralisation</b> — un tableau Google Sheets unique regroupant toutes les données dispersées.</li>
      <li><b>Nettoyage</b> — repérer doublons, valeurs manquantes, incohérences d'unité. Dans Sheets : Données → Nettoyer les données → Supprimer les doublons.</li>
      <li><b>Synthèse</b> — une page pour un décideur non technique.</li>
      <li><b>Validation humaine obligatoire</b> — un ingénieur ou géologue qualifié revoit toute conclusion.</li>
    </ol>
    <div class="quote">RAPPORT — [Site] — [Date]
1. Résumé en 3 phrases
2. Chiffres clés
3. Évolution par rapport à la période précédente
4. Anomalies observées
5. Recommandation (à valider par un responsable technique)</div>
    <div class="warn"><b>Vigilance —</b> ce module ne remplace jamais un logiciel de géologie certifié ni l'avis d'un professionnel qualifié.</div>
    <div class="exo"><b>Exercice —</b> Créez 10 données fictives et appliquez les 4 premières étapes de la chaîne de traitement.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple de synthèse : « 10 échantillons collectés entre 0 et 40m, teneur moyenne 2,3 g/t, maximale 4,1 g/t à 22m, minimale 0,8 g/t à 5m. Anomalie : un échantillon à 9,7 g/t s'écarte fortement et doit être revérifié. Recommandation : creuser davantage autour de cette zone, sous réserve de validation par un géologue. »</div></details>
    <div class="quiz">
      <p>Quiz — Quelle étape est absolument obligatoire avant toute décision basée sur ces données ?</p>
      <label><input type="radio" name="q8" value="a"> La validation par un ingénieur ou géologue qualifié</label>
      <label><input type="radio" name="q8" value="b"> L'ajout d'une couleur au tableau</label>
      <button onclick="check('q8','a','c8','c9')">Valider</button>
      <div class="fb" id="fb-c8"></div>
    </div>
    <div class="done" id="done-c8">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c9">
  <div class="ch-head">9 — Qui sont vos clients et comment les trouver</div>
  <div class="ch-body">
    <h4>Agent Boutique — profil et canaux</h4>
    <p>Vendeurs actifs sur Facebook/Instagram/WhatsApp avec catalogue visible mais réponses lentes ; secteurs à forte récurrence (mode, cosmétiques, téléphones), 5 à 50 commandes/semaine.</p>
    <ul><li>Groupes Facebook de vente locaux — rejoignez-les, repérez les vendeurs actifs quotidiens</li><li>Recherche Instagram par hashtags locaux (#boutiqueDouala...)</li><li>Visite physique des marchés avec une carte de contact</li><li>Page vitrine de votre activité avec preuve anonymisée de résultats</li><li>Partenariat avec vendeurs de forfaits internet / community managers (commission par client signé)</li></ul>
    <h4>Agent Mine — profil et canaux</h4>
    <p>Petites sociétés minières artisanales, sous-traitants de transport/engins facturés au tonnage, carrières de matériaux de construction en périphérie urbaine.</p>
    <ul><li>Chambre des Mines et syndicats professionnels — événements et réunions</li><li>Fournisseurs d'équipement/carburant — ils connaissent tous les sites actifs</li><li>Visite directe des sites, contact en personne avec le responsable</li><li>Recherche LinkedIn : « responsable de site », « chef d'exploitation »</li></ul>
    <h4>Géologie/Pétrole — profil et canaux</h4>
    <p>Bureaux d'études géotechniques indépendants, petites sociétés parapétrolières locales, jeunes ingénieurs en fin de stage.</p>
    <ul><li>Écoles et facultés de géosciences/mines — enseignants et associations d'étudiants</li><li>Groupes LinkedIn/Facebook géologie-mines Afrique centrale</li><li>Répertoires de bureaux d'études du Ministère des Mines</li><li>Rapport gratuit offert en échange d'un témoignage</li></ul>
    <div class="warn"><b>Vigilance —</b> la visibilité en ligne reste secondaire par rapport au contact direct : dans ces secteurs, la confiance se gagne majoritairement en personne.</div>
    <div class="exo"><b>Exercice —</b> Listez 10 prospects réels correspondant au profil de votre secteur, avec le canal exact utilisé pour identifier chacun.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple (Boutique) : 1) « Chic Douala » — groupe Facebook « Vends et achète Douala ». 2) « Cosméto Yaoundé » — recherche Instagram #cosmetiqueCameroun. 3) « Phone Store Akwa » — visite physique du marché central. (et ainsi de suite jusqu'à 10, chacun rattaché à un canal précis et vérifiable).</div></details>
    <div class="quiz">
      <p>Quiz — Pour trouver des clients Agent Mine, quel canal est particulièrement utile ?</p>
      <label><input type="radio" name="q9" value="a"> Les fournisseurs d'équipement et de carburant, qui connaissent les sites actifs</label>
      <label><input type="radio" name="q9" value="b"> Les publicités télévisées nationales</label>
      <button onclick="check('q9','a','c9','c10')">Valider</button>
      <div class="fb" id="fb-c9"></div>
    </div>
    <div class="done" id="done-c9">✓ Chapitre validé</div>
  </div>
</div>

<div class="chapter locked" id="c10">
  <div class="ch-head">10 — Faire grandir le portefeuille & plan 90 jours</div>
  <div class="ch-body">
    <h4>4 leviers de croissance</h4>
    <ol><li>Recommandation après chaque client satisfait</li><li>Preuve chiffrée documentée par client</li><li>Rythme mesuré : 2-3 nouveaux clients/mois</li><li>Délégation à partir de 15-20 clients</li></ol>
    <table>
      <tr><th>Période</th><th>Objectif</th></tr>
      <tr><td>Semaines 1-2</td><td>Contacter 15-20 prospects, 2-3 essais gratuits</td></tr>
      <tr><td>Semaines 3-4</td><td>Livrer, ajuster, collecter témoignages</td></tr>
      <tr><td>Mois 2</td><td>Tarifs pleins, viser 5-8 clients actifs</td></tr>
      <tr><td>Mois 3</td><td>Recommandations actives, préparer la délégation</td></tr>
    </table>
    <div class="exo"><b>Exercice final —</b> Rédigez sur une page : secteur choisi, 10 prospects nommés, prix fixé, date visée pour le 1er client payant.</div>
    <details class="sol"><summary>Voir le corrigé</summary><div class="sol-body">Exemple : Secteur — Agent Boutique. Prospects : 1. Awa Fashion — 30 000F/mois. 2. Cosméto Douala — 30 000F/mois. 3. Phone Store Yaoundé — 35 000F/mois (jusqu'à 10). Date visée pour le premier client payant : dans 21 jours, après un essai gratuit débuté cette semaine avec Awa Fashion.</div></details>
    <div class="quiz">
      <p>Quiz — Quel rythme de croissance est recommandé au départ ?</p>
      <label><input type="radio" name="q10" value="a"> 20 clients le premier mois</label>
      <label><input type="radio" name="q10" value="b"> 2 à 3 nouveaux clients par mois</label>
      <button onclick="check('q10','b','c10','')">Valider</button>
      <div class="fb" id="fb-c10"></div>
    </div>
    <div class="done" id="done-c10">✓ Parcours interactif terminé — bravo !</div>
  </div>
</div>

</div>
<script>
function check(name, correct, curId, nextId){
  var sel = document.querySelector('input[name="'+name+'"]:checked');
  var fb = document.getElementById('fb-'+curId);
  if(!sel){ fb.textContent="Choisissez une réponse."; fb.className="fb no"; return; }
  if(sel.value===correct){
    fb.textContent="Correct !"; fb.className="fb ok";
    document.getElementById('done-'+curId).style.display='block';
    try{ localStorage.setItem('formInt_'+curId,'done'); }catch(e){}
    if(nextId){ document.getElementById(nextId).classList.remove('locked'); }
    updateProgress();
  } else {
    fb.textContent="Pas tout à fait — relisez le chapitre et réessayez."; fb.className="fb no";
  }
}
function updateProgress(){
  var total=10, done=0;
  for(var i=1;i<=10;i++){ try{ if(localStorage.getItem('formInt_c'+i)==='done') done++; }catch(e){} }
  document.getElementById('pbar').style.width = (done/total*100)+'%';
}
window.onload=function(){
  for(var i=2;i<=10;i++){
    try{ if(localStorage.getItem('formInt_c'+(i-1))==='done'){ document.getElementById('c'+i).classList.remove('locked'); document.getElementById('done-c'+(i-1)).style.display='block'; } }catch(e){}
  }
  updateProgress();
};
</script>
</body>
</html>
