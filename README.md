```

# projet/
│   README.md
│   Rapport_Vote_Electronique_Bilingue.doc
│   database_image.png
│
│   RSA Voting Process Framework-2026-04-28-105132.png
│   
└───source code/
    │   README.md
    │   
    ├───data base/
    │       vote_database.py
    │       
    ├───data cryptation (RSA)/
    │       rsa_keygen.py
    │       
    ├───GUI interface/
    │   │   main_gui.py
    │   │   journal_votes.json
    │   │   registre_cles_publiques.json
    │   │   resultats_vote.json
    │   │   
    │   └───cles_electeurs/  (empty - stores client RSA keys when generated)
    │
    ├───rapport fr,en/
    │       rapport_vote_EN.pdf
    │       rapport_vote_FR.pdf
    │       
    └───vote client,serveur/
            generate_report.py
            voter_client.py
            voting_server.py
```
