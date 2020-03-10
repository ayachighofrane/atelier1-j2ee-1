# atelier1-j2ee: Créer et déployer une Servlet

1.	Modifier le code de la Servlet "BonjourServlet" qui permet de compter et d'afficher le nombre de fois qu'elle a été appelée (Afficher par exemple un message <<Cette Servlet a été accédée " + compteur + " fois.>>) 
2.	Créer une nouvelle classe Servlet "BonsoirServlet" et configurer cette Servlet via les annotations pour qu’il soit accessible en GET via le fragment /bonsoir.
3.	Créer une nouvelle classe Servlet "RediregeServlet" qui redirige l’utilisateur vers le site Internet externe http://www.isetjb.rnu.tn/ en implémentant la méthode doGet(). Configurer cette Servlet soit par annotations, soit dans le descripteur de déploiement pour être accessible via /redirect.
4.	Créer une nouvelle classe Servlet "ParamServlet" qui permet de lire et d’afficher les paramètres de requête de l'URL http://localhost:8080/atelier1-j2ee/param?prenom=maysem&age=9. Vérifier l’affichage des résultats avec les URL suivantes :
- http://localhost:8080/atelier1-j2ee/param?age=9&prenom=maysem
- http://localhost:8080/atelier1-j2ee/param?age=9
- http://localhost:8080/atelier1-j2ee/param?prenom=maysem 
- http://localhost:8080/atelier1-j2ee/param
5. Créer deux Servlets, InitialServlet et ForwardServlet et configurer les pour être respectivement accessibles via /initial et /forward. Dans le premier Servlet, implémenter le forward vers le second. Dans le second Servlet, afficher un message <<Bienvenu dans Forward!>>.
