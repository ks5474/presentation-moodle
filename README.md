<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moodiy - Plateforme de Formation en Ligne</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
        }
        
        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.3em;
            opacity: 0.9;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        section {
            margin-bottom: 50px;
            padding: 30px;
            background: #f9f9f9;
            border-left: 5px solid #667eea;
            border-radius: 5px;
        }
        
        section h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 2px solid #667eea;
            padding-bottom: 10px;
        }
        
        section h3 {
            color: #764ba2;
            font-size: 1.3em;
            margin-top: 20px;
            margin-bottom: 10px;
        }
        
        .feature-list {
            list-style: none;
            margin: 15px 0;
        }
        
        .feature-list li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
        }
        
        .feature-list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
            font-size: 1.2em;
        }
        
        .highlight-box {
            background: #e8eaf6;
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
            border-left: 4px solid #764ba2;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .stat-box {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .stat-box h4 {
            color: #667eea;
            font-size: 1.8em;
            margin-bottom: 10px;
        }
        
        .stat-box p {
            color: #666;
        }
        
        .comparison {
            background: white;
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
        }
        
        .comparison-item {
            display: flex;
            align-items: center;
            margin: 15px 0;
            padding: 15px;
            background: #f0f0f0;
            border-radius: 5px;
        }
        
        .comparison-item .icon {
            font-size: 2em;
            margin-right: 20px;
            min-width: 50px;
        }
        
        .comparison-item .text h4 {
            color: #667eea;
            margin-bottom: 5px;
        }
        
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .service-card {
            background: white;
            padding: 25px;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            border-top: 4px solid #667eea;
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
        }
        
        .service-card h3 {
            color: #667eea;
            margin-bottom: 15px;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin-top: 50px;
        }
        
        .footer-contact {
            margin-top: 15px;
            font-size: 1.05em;
            border-top: 2px solid #667eea;
            padding-top: 15px;
        }
        
        .footer-contact p {
            margin: 8px 0;
        }
        
        .cta-button {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
            transition: background 0.3s;
        }
        
        .cta-button:hover {
            background: #764ba2;
        }
    </style>
</head>
<body>
    <header>
        <h1>🎓 MOODIY</h1>
        <p>Votre Plateforme de Formation en Ligne Professionnelle</p>
    </header>
    
    <div class="container">
        <!-- Section 1: Présentation de Moodle -->
        <section>
            <h2>📱 À Propos de Moodle</h2>
            
            <p>Moodle est une plateforme de mise en ligne de formations mondialement reconnue et utilisée par les plus grandes institutions éducatives du monde.</p>
            
            <div class="highlight-box">
                <strong>Une plateforme mondiale :</strong> Utilisée par Harvard, Stanford, Oxford et des milliers d'autres institutions pédagogiques et entreprises à travers le monde.
            </div>
            
            <h3>Avantages Clés de Moodle :</h3>
            <ul class="feature-list">
                <li>Interface intuitive et accessible</li>
                <li>Utilisée internationalement par les plus grandes institutions</li>
                <li>Flexibilité et personnalisation complètes</li>
                <li>Support multilingue</li>
                <li>Sécurité robuste des données</li>
                <li>Capacité à gérer des milliers d'utilisateurs simultanément</li>
                <li>Outils collaboratifs avancés (forums, chat, vidéoconférence)</li>
                <li>Suivi détaillé de la progression des apprenants</li>
            </ul>
            
            <div class="stats">
                <div class="stat-box">
                    <h4>190+</h4>
                    <p>Pays utilisant Moodle</p>
                </div>
                <div class="stat-box">
                    <h4>300M+</h4>
                    <p>Utilisateurs enregistrés</p>
                </div>
                <div class="stat-box">
                    <h4>19+</h4>
                    <p>Années d'expérience</p>
                </div>
            </div>
        </section>
        
        <!-- Section 2: Aspects Techniques -->
        <section>
            <h2>⚙️ Aspects Techniques de Moodle</h2>
            
            <h3>Comment Fonctionne la Création d'un Compte Moodle :</h3>
            
            <div class="comparison">
                <div class="comparison-item">
                    <div class="icon">1️⃣</div>
                    <div class="text">
                        <h4>Installation de la Plateforme</h4>
                        <p>Déploiement de Moodle sur vos serveurs ou utilisation d'un hébergement cloud sécurisé</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">2️⃣</div>
                    <div class="text">
                        <h4>Configuration de Base</h4>
                        <p>Personnalisation de l'interface, logo, couleurs et paramètres généraux</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">3️⃣</div>
                    <div class="text">
                        <h4>Création des Comptes Utilisateurs</h4>
                        <p>Ajout manuel ou import en masse des étudiants et enseignants (CSV, LDAP, SSO)</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">4️⃣</div>
                    <div class="text">
                        <h4>Attribution des Rôles</h4>
                        <p>Définition des permissions : administrateur, enseignant, étudiant, gestionnaire</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">5️⃣</div>
                    <div class="text">
                        <h4>Création des Cours</h4>
                        <p>Mise en place des espaces de cours avec contenus, évaluations et activités</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">6️⃣</div>
                    <div class="text">
                        <h4>Lancement et Suivi</h4>
                        <p>Gestion des inscriptions et suivi de la progression des apprenants en temps réel</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Section 3: Comparaison avec Excel -->
        <section>
            <h2>📊 Moodle : La Complexité d'une Interface Professionnelle</h2>
            
            <p><strong>Moodle fonctionne comme Excel :</strong> Tout comme Excel, Moodle est un outil puissant mais qui nécessite une véritable maîtrise et une connaissance approfondie pour être utilisé efficacement.</p>
            
            <div class="highlight-box">
                <strong>Pourquoi cette comparaison ?</strong>
                <ul class="feature-list" style="margin-top: 10px;">
                    <li>Nombreuses options et fonctionnalités disponibles</li>
                    <li>Requiert une formation pour maximiser le potentiel</li>
                    <li>Les erreurs de configuration peuvent avoir des impacts importants</li>
                    <li>Une utilisation optimale demande de l'expérience</li>
                    <li>Les gains de productivité sont proportionnels à la maîtrise de l'outil</li>
                </ul>
            </div>
        </section>
        
        <!-- Section 4: Mes Services et Compétences -->
        <section>
            <h2>💼 Mes Services et Compétences</h2>
            
            <p>Je suis expert en gestion et configuration d'interfaces Moodle. Je mets à votre disposition une expertise complète pour transformer Moodle en une plateforme de formation performante et adaptée à vos besoins.</p>
            
            <h3>Domaines d'Expertise :</h3>
            
            <div class="services">
                <div class="service-card">
                    <h3>🔧 Configuration Moodle</h3>
                    <p>Installation, paramétrage, et personnalisation complète de votre plateforme Moodle selon vos besoins spécifiques.</p>
                </div>
                
                <div class="service-card">
                    <h3>📚 Création d'Espaces de Cours</h3>
                    <p>Conception et mise en place d'espaces de cours en ligne professionnels pour entreprises et institutions pédagogiques.</p>
                </div>
                
                <div class="service-card">
                    <h3>👥 Gestion de l'Interface</h3>
                    <p>Administration complète de Moodle : gestion des utilisateurs, des rôles, des permissions et de la structure organisationnelle.</p>
                </div>
                
                <div class="service-card">
                    <h3>🎓 Formation & Accompagnement</h3>
                    <p>Formation complète de vos équipes pour maîtriser Moodle et gérer de manière autonome votre plateforme et vos cours.</p>
                </div>
                
                <div class="service-card">
                    <h3>🚀 Optimisation de Plateforme</h3>
                    <p>Amélioration des performances, sécurité, et utilisation avancée des fonctionnalités Moodle.</p>
                </div>
                
                <div class="service-card">
                    <h3>📊 Support Continu</h3>
                    <p>Support technique et assistance continue après la mise en ligne pour garantir le bon fonctionnement.</p>
                </div>
            </div>
        </section>
        
        <!-- Section 5: Proposition de Valeur -->
        <section>
            <h2>✨ Mon Approche Différenciante</h2>
            
            <h3>Installation + Formation = Succès</h3>
            
            <div class="highlight-box">
                <p><strong>Après l'installation de votre plateforme Moodle, je propose une formation complète permettant à votre équipe de :</strong></p>
                <ul class="feature-list">
                    <li>Maîtriser l'interface Moodle de manière complète</li>
                    <li>Créer et gérer vos propres cours en ligne</li>
                    <li>Administrer autonomement votre plateforme</li>
                    <li>Optimiser l'expérience de vos apprenants</li>
                    <li>Réduire votre dépendance à un support externe</li>
                    <li>Évolutionner rapidement face aux changements</li>
                </ul>
            </div>
            
            <h3>Avantages pour Votre Organisation :</h3>
            
            <div class="comparison">
                <div class="comparison-item">
                    <div class="icon">✅</div>
                    <div class="text">
                        <h4>Autonomie</h4>
                        <p>Votre équipe gère la plateforme sans dépendre d'un tiers</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">✅</div>
                    <div class="text">
                        <h4>Réduction des Coûts</h4>
                        <p>Moins de frais de support et maintenance externes</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">✅</div>
                    <div class="text">
                        <h4>Flexibilité</h4>
                        <p>Adaptez rapidement votre plateforme à vos besoins</p>
                    </div>
                </div>
                
                <div class="comparison-item">
                    <div class="icon">✅</div>
                    <div class="text">
                        <h4>Qualité</h4>
                        <p>Plateforme optimisée et plateforme professionnelle dès le départ</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Section 6: Appel à l'Action -->
        <section style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; border-left: none;">
            <h2 style="color: white; border-bottom-color: white;">🎯 Prêt à Transformer Votre Formation en Ligne ?</h2>
            
            <p style="font-size: 1.1em; margin: 20px 0;">
                Découvrez comment Moodle, couplée à mon expertise, peut révolutionner votre offre de formation.
            </p>
            
            <p><strong>Contactez-moi pour :</strong></p>
            <ul class="feature-list" style="color: white;">
                <li>Une démonstration personnalisée</li>
                <li>Un audit de vos besoins en formation en ligne</li>
                <li>Une proposition sur mesure adaptée à votre contexte</li>
            </ul>
            
            <a href="mailto:kisikitenge@gmail.com" class="cta-button" style="background: white; color: #667eea;">📧 Nous Contacter</a>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2026 MOODIY - Plateforme de Formation en Ligne. Tous droits réservés.</p>
        <p>Expert en Configuration et Gestion d'Interfaces Moodle</p>
        <div class="footer-contact">
            <p><strong>Kisi Kitenge</strong></p>
            <p>Téléphone : +243 976 118 711 | Contact : kisikitenge@gmail.com</p>
        </div>
    </footer>
</body>
</html>
