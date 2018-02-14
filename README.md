# Cassandra
##  Un Didacticiel concernant Apache Cassandra 3.11.1 

### Le but de ce didactitiel est de: 

- Montrer comment sauvegarder la liste des sujets de Cycle C sur Cassandra 3.11 
- Montrer comment les données sont reparties et répliquées
- Faire un exemple sur "upsert"
- Faire un exemple sur la consistance éventuelle.

### La démarche:
- Configurer une machine virtuelle ("cassandra-machine") hébergée dans Google Cloud Platform
- Installer 3 Docker Container Cassandra 3.11.1 (cassandra-node1, canndara-node2, cassandra-node3) sur "cassandra-machine"
- Créer un Keyspace "demo_kspc"
- Créer une table "sujets_valc"
- Insérer les données dans "sujets_valc"
- Montrer comment une partition quelconque est sauvegardée sur le disque dur



