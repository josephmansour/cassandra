# Cassandra
Un Didacticiel concernant Apache Cassandra 3.11.1

Le but de ce didactitiel est de 
Montrer comment sauvegarder la liste des sujets de Cycle C sur Cassandra 3.11 
Montrer comment les données sont réparties et répliquées
Faire un exemple sur "upsert"
Faire un exemple sur la consistance éventuelle.

Démarche:
Configurer une machine (i.e. "cassandra-machine") virtuelle hébergée dans Google Cloud Platform
Installer 3 Docker Container Cassandra 3.11.1 sur "cassandra-machine"
Créer un Keyspace "demo_kspc"
Créer une table "sujets_cyclec"
Insérer les données dans "sujets_cyclec"



