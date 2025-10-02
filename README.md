<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amina Immobilier International - Services Immobiliers en Guinée</title>
    
    <!-- SEO Meta Tags -->
    <meta name="description" content="Amina Immobilier International - Services immobiliers professionnels, construction et aménagement urbain en Guinée et à l'international. Découvrez nos projets et services.">
    <meta name="keywords" content="immobilier Guinée, construction, aménagement urbain, services immobiliers, Amina Immobilier">
    <meta name="author" content="Amina Immobilier International">
    
    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="Amina Immobilier International - Services Immobiliers">
    <meta property="og:description" content="Services immobiliers professionnels, construction et aménagement urbain en Guinée et à l'international.">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://images.unsplash.com/photo-1560518883-ce09059eeffa?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&h=630">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Custom Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        secondary: '#2D3748',
                        accent: '#F7FAFC'
                    }
                }
            }
        }
    </script>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* Dark mode support */
        .dark {
            color-scheme: dark;
        }
        
        /* Smooth animations */
        .fade-in {
            animation: fadeIn 0.8s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .hover-scale {
            transition: transform 0.3s ease;
        }
        
        .hover-scale:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-900 dark:text-white">
    <!-- Navigation -->
    <nav class="bg-white dark:bg-gray-800 shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <h1 class="text-xl font-bold text-primary">Amina Immobilier</h1>
                        <p class="text-xs text-gray-600 dark:text-gray-400">International</p>
                    </div>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#accueil" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">Accueil</a>
                        <a href="#apropos" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">À propos</a>
                        <a href="#services" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">Services</a>
                        <a href="#activites" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">Activités</a>
                        <a href="#faq" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">FAQ</a>
                        <a href="#blog" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">Blog</a>
                        <a href="#contact" class="hover:text-primary px-3 py-2 text-sm font-medium transition-colors">Contact</a>
                    </div>
                </div>
                
                <!-- Mobile menu button -->
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-gray-600 dark:text-gray-300 hover:text-primary">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white dark:bg-gray-800 shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#accueil" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">Accueil</a>
                <a href="#apropos" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">À propos</a>
                <a href="#services" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">Services</a>
                <a href="#activites" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">Activités</a>
                <a href="#faq" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">FAQ</a>
                <a href="#blog" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">Blog</a>
                <a href="#contact" class="block px-3 py-2 text-base font-medium hover:text-primary transition-colors">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="accueil" class="pt-16 bg-gradient-to-br from-primary/10 to-blue-50 dark:from-primary/20 dark:to-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
            <div class="text-center fade-in">
                <h1 class="text-4xl md:text-6xl font-bold text-gray-900 dark:text-white mb-6">
                    Amina Immobilier
                    <span class="text-primary block">International</span>
                </h1>
                <p class="text-xl md:text-2xl text-gray-600 dark:text-gray-300 mb-8 max-w-3xl mx-auto">
                    Votre partenaire de confiance pour tous vos projets immobiliers en Guinée et à l'international
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#services" class="bg-primary text-white px-8 py-3 rounded-lg font-semibold hover:bg-primary/90 transition-colors">
                        Découvrir nos services
                    </a>
                    <a href="#contact" class="border-2 border-primary text-primary px-8 py-3 rounded-lg font-semibold hover:bg-primary hover:text-white transition-colors">
                        Nous contacter
                    </a>
                </div>
            </div>
            
            <!-- Hero Image -->
            <div class="mt-16 rounded-xl overflow-hidden shadow-2xl hover-scale">
                <img src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?ixlib=rb-4.0.3&auto=format&fit=crop&w=1400&h=700" 
                     alt="Immeubles modernes - Amina Immobilier International" 
                     class="w-full h-96 object-cover">
            </div>
        </div>
    </section>

    <!-- À propos Section -->
    <section id="apropos" class="py-20 bg-white dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Introduction -->
            <div class="text-center mb-16 fade-in">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    À propos de nous
                </h2>
                <div class="max-w-4xl mx-auto">
                    <p class="text-lg text-gray-600 dark:text-gray-300 leading-relaxed">
                        <strong>Amina Immobilier International</strong> est une société de promotion et de construction immobilière, 
                        ayant son siège social en France et une forte implantation en République de Guinée. 
                        Nous avons pour vocation de transformer le paysage urbain en Afrique de l'Ouest en proposant 
                        des solutions modernes, accessibles et durables dans le domaine de l'immobilier.
                    </p>
                </div>
            </div>

            <!-- Vision & Mission -->
            <div class="grid lg:grid-cols-2 gap-12 mb-20">
                <!-- Vision -->
                <div class="bg-gradient-to-br from-primary/5 to-blue-50 dark:from-primary/10 dark:to-gray-800 p-8 rounded-xl fade-in">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-eye text-2xl text-primary"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900 dark:text-white">Notre Vision</h3>
                    </div>
                    <p class="text-gray-700 dark:text-gray-300 leading-relaxed">
                        Être un acteur de référence dans le secteur immobilier en Afrique de l'Ouest, 
                        reconnu pour la qualité de nos projets, notre expertise et notre engagement 
                        pour un développement durable.
                    </p>
                </div>

                <!-- Mission -->
                <div class="bg-gradient-to-br from-green-50 to-emerald-50 dark:from-green-900/20 dark:to-emerald-900/20 p-8 rounded-xl fade-in">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-green-100 dark:bg-green-800 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-bullseye text-2xl text-green-600 dark:text-green-400"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900 dark:text-white">Notre Mission</h3>
                    </div>
                    <ul class="space-y-3 text-gray-700 dark:text-gray-300">
                        <li class="flex items-start">
                            <i class="fas fa-check text-green-500 mr-3 mt-1"></i>
                            <span>Construire et livrer des logements modernes, abordables et de qualité</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-green-500 mr-3 mt-1"></i>
                            <span>Développer des projets immobiliers adaptés aux besoins des populations</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-green-500 mr-3 mt-1"></i>
                            <span>Contribuer à réduire le déficit en logements en Guinée et en Afrique</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-green-500 mr-3 mt-1"></i>
                            <span>Offrir des solutions de financement souples grâce à des partenariats bancaires</span>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- Objectifs -->
            <div class="mb-20 fade-in">
                <div class="text-center mb-12">
                    <h3 class="text-3xl font-bold text-gray-900 dark:text-white mb-4">Nos Objectifs</h3>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl text-center hover-scale">
                        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-home text-2xl text-primary"></i>
                        </div>
                        <h4 class="font-semibold mb-3">500 Logements</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Construction moderne à Dubréka comme projet pilote</p>
                    </div>
                    
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl text-center hover-scale">
                        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-map-marked-alt text-2xl text-primary"></i>
                        </div>
                        <h4 class="font-semibold mb-3">Expansion</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Activités dans plusieurs grandes villes de Guinée</p>
                    </div>
                    
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl text-center hover-scale">
                        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-handshake text-2xl text-primary"></i>
                        </div>
                        <h4 class="font-semibold mb-3">Partenaires</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Attirer investisseurs pour la croissance du secteur</p>
                    </div>
                    
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl text-center hover-scale">
                        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-leaf text-2xl text-primary"></i>
                        </div>
                        <h4 class="font-semibold mb-3">Environnement</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Projets respectueux des normes internationales</p>
                    </div>
                </div>
            </div>

            <!-- Équipe -->
            <div class="mb-20 fade-in">
                <div class="text-center mb-12">
                    <h3 class="text-3xl font-bold text-gray-900 dark:text-white mb-4">Notre Équipe</h3>
                    <p class="text-lg text-gray-600 dark:text-gray-300">
                        Une équipe expérimentée et passionnée dirigée par des professionnels reconnus
                    </p>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Président Fondateur -->
                    <div class="text-center bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale">
                        <div class="w-20 h-20 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-user-tie text-3xl text-primary"></i>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Mandjou Camara</h4>
                        <p class="text-primary font-semibold mb-2">Président Fondateur</p>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Direction générale et vision stratégique</p>
                    </div>
                    
                    <!-- Directeur Technique -->
                    <div class="text-center bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale">
                        <div class="w-20 h-20 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-hard-hat text-3xl text-primary"></i>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Alber Sylla</h4>
                        <p class="text-primary font-semibold mb-2">Directeur Technique</p>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Supervision technique et qualité</p>
                    </div>
                    
                    <!-- Responsable Financier -->
                    <div class="text-center bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale">
                        <div class="w-20 h-20 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-calculator text-3xl text-primary"></i>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Abdourahamane Camara</h4>
                        <p class="text-primary font-semibold mb-2">Resp. Financier</p>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Gestion financière et administrative</p>
                    </div>
                    
                    <!-- Équipe Technique -->
                    <div class="text-center bg-white dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale">
                        <div class="w-20 h-20 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-users text-3xl text-primary"></i>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Équipe Technique</h4>
                        <p class="text-primary font-semibold mb-2">Architectes & Ingénieurs</p>
                        <p class="text-sm text-gray-600 dark:text-gray-300">Conception et réalisation des projets</p>
                    </div>
                </div>
            </div>

            <!-- Projets Phares & Partenaires -->
            <div class="grid lg:grid-cols-2 gap-12 mb-20">
                <!-- Projets Phares -->
                <div class="fade-in">
                    <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-6 flex items-center">
                        <i class="fas fa-star text-primary mr-3"></i>
                        Projets Phares
                    </h3>
                    <div class="space-y-4">
                        <div class="bg-gradient-to-r from-primary/5 to-transparent p-4 rounded-lg border-l-4 border-primary">
                            <h4 class="font-semibold mb-2">Cité Résidentielle de Dubréka</h4>
                            <p class="text-sm text-gray-600 dark:text-gray-300">500 logements modernes avec infrastructures complètes</p>
                        </div>
                        <div class="bg-gradient-to-r from-blue-50 to-transparent dark:from-blue-900/20 p-4 rounded-lg border-l-4 border-blue-400">
                            <h4 class="font-semibold mb-2">Lotissements Modernes</h4>
                            <p class="text-sm text-gray-600 dark:text-gray-300">Avec infrastructures de base (eau, électricité, voiries)</p>
                        </div>
                        <div class="bg-gradient-to-r from-green-50 to-transparent dark:from-green-900/20 p-4 rounded-lg border-l-4 border-green-400">
                            <h4 class="font-semibold mb-2">Partenariats Financiers</h4>
                            <p class="text-sm text-gray-600 dark:text-gray-300">Solutions de financement pour faciliter l'accès au logement</p>
                        </div>
                    </div>
                </div>

                <!-- Partenaires -->
                <div class="fade-in">
                    <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-6 flex items-center">
                        <i class="fas fa-handshake text-primary mr-3"></i>
                        Nos Partenaires
                    </h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow text-center">
                            <i class="fas fa-university text-2xl text-primary mb-2"></i>
                            <p class="text-sm font-semibold">Investisseurs</p>
                            <p class="text-xs text-gray-600 dark:text-gray-400">Privés & Institutionnels</p>
                        </div>
                        <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow text-center">
                            <i class="fas fa-piggy-bank text-2xl text-primary mb-2"></i>
                            <p class="text-sm font-semibold">Banques</p>
                            <p class="text-xs text-gray-600 dark:text-gray-400">Établissements Financiers</p>
                        </div>
                        <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow text-center">
                            <i class="fas fa-hammer text-2xl text-primary mb-2"></i>
                            <p class="text-sm font-semibold">Construction</p>
                            <p class="text-xs text-gray-600 dark:text-gray-400">Entreprises & Bureaux d'études</p>
                        </div>
                        <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow text-center">
                            <i class="fas fa-globe text-2xl text-primary mb-2"></i>
                            <p class="text-sm font-semibold">Développement</p>
                            <p class="text-xs text-gray-600 dark:text-gray-400">Organismes spécialisés</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Valeurs -->
            <div class="mb-20 fade-in">
                <div class="text-center mb-12">
                    <h3 class="text-3xl font-bold text-gray-900 dark:text-white mb-4">Nos Valeurs</h3>
                </div>
                <div class="grid md:grid-cols-3 lg:grid-cols-5 gap-6">
                    <div class="text-center bg-gradient-to-b from-primary/5 to-transparent p-6 rounded-xl">
                        <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-shield-alt text-2xl text-primary"></i>
                        </div>
                        <h4 class="font-semibold">Intégrité</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300 mt-2">& Transparence</p>
                    </div>
                    
                    <div class="text-center bg-gradient-to-b from-blue-50 to-transparent dark:from-blue-900/20 p-6 rounded-xl">
                        <div class="w-16 h-16 bg-blue-100 dark:bg-blue-800 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-award text-2xl text-blue-600 dark:text-blue-400"></i>
                        </div>
                        <h4 class="font-semibold">Qualité</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300 mt-2">& Innovation</p>
                    </div>
                    
                    <div class="text-center bg-gradient-to-b from-green-50 to-transparent dark:from-green-900/20 p-6 rounded-xl">
                        <div class="w-16 h-16 bg-green-100 dark:bg-green-800 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-users text-2xl text-green-600 dark:text-green-400"></i>
                        </div>
                        <h4 class="font-semibold">Accessibilité</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300 mt-2">Pour tous</p>
                    </div>
                    
                    <div class="text-center bg-gradient-to-b from-emerald-50 to-transparent dark:from-emerald-900/20 p-6 rounded-xl">
                        <div class="w-16 h-16 bg-emerald-100 dark:bg-emerald-800 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-leaf text-2xl text-emerald-600 dark:text-emerald-400"></i>
                        </div>
                        <h4 class="font-semibold">Développement</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300 mt-2">Durable</p>
                    </div>
                    
                    <div class="text-center bg-gradient-to-b from-orange-50 to-transparent dark:from-orange-900/20 p-6 rounded-xl">
                        <div class="w-16 h-16 bg-orange-100 dark:bg-orange-800 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i class="fas fa-heart text-2xl text-orange-600 dark:text-orange-400"></i>
                        </div>
                        <h4 class="font-semibold">Impact Social</h4>
                        <p class="text-sm text-gray-600 dark:text-gray-300 mt-2">Positif</p>
                    </div>
                </div>
            </div>

            <!-- Coordonnées -->
            <div class="bg-gray-50 dark:bg-gray-800 p-8 rounded-xl fade-in">
                <h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-8 text-center">Nos Coordonnées</h3>
                <div class="grid md:grid-cols-2 gap-8">
                    <!-- Siège France -->
                    <div class="bg-white dark:bg-gray-900 p-6 rounded-lg">
                        <h4 class="text-lg font-bold text-primary mb-4 flex items-center">
                            <i class="fas fa-map-marker-alt mr-2"></i>
                            Siège Social - France
                        </h4>
                        <div class="space-y-2 text-gray-600 dark:text-gray-300">
                            <p><strong>Adresse :</strong> 31560 Saint-Leon, Paris, France</p>
                            <p><strong>SIREN :</strong> 991097163</p>
                            <p><strong>SIRET :</strong> 99109716300018</p>
                        </div>
                    </div>
                    
                    <!-- Représentation Guinée -->
                    <div class="bg-white dark:bg-gray-900 p-6 rounded-lg">
                        <h4 class="text-lg font-bold text-primary mb-4 flex items-center">
                            <i class="fas fa-map-marker-alt mr-2"></i>
                            Représentation - Guinée
                        </h4>
                        <div class="space-y-2 text-gray-600 dark:text-gray-300">
                            <p><strong>Localisation :</strong> Dubréka, République de Guinée</p>
                            <p><strong>Société locale :</strong> Guinée Nouvelle Construction SARL</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    Nos Services
                </h2>
                <p class="text-xl text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
                    Des solutions immobilières complètes adaptées à vos besoins
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-home text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Vente de Propriétés</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Large sélection de propriétés résidentielles et commerciales en Guinée et à l'international.
                    </p>
                </div>
                
                <!-- Service 2 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-key text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Location</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Services de location pour particuliers et entreprises avec accompagnement personnalisé.
                    </p>
                </div>
                
                <!-- Service 3 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-chart-line text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Investissement</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Conseils en investissement immobilier et opportunités de placement rentables.
                    </p>
                </div>
                
                <!-- Service 4 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-tools text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Gestion de Propriétés</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Gestion complète de vos biens immobiliers avec maintenance et suivi locataires.
                    </p>
                </div>
                
                <!-- Service 5 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-handshake text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Conseil Juridique</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Accompagnement juridique pour toutes vos transactions immobilières.
                    </p>
                </div>
                
                <!-- Service 6 -->
                <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-xl shadow-lg hover-scale fade-in">
                    <div class="w-16 h-16 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-calculator text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Évaluation</h3>
                    <p class="text-gray-600 dark:text-gray-300">
                        Évaluation professionnelle de vos biens pour optimiser leur valeur marchande.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Activités Section -->
    <section id="activites" class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    Nos Activités
                </h2>
                <p class="text-xl text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
                    Construction et aménagement urbain pour un développement durable
                </p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <!-- Construction -->
                <div class="fade-in">
                    <div class="bg-white dark:bg-gray-900 p-8 rounded-xl shadow-lg">
                        <div class="flex items-center mb-6">
                            <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4">
                                <i class="fas fa-building text-xl text-primary"></i>
                            </div>
                            <h3 class="text-2xl font-bold">Construction</h3>
                        </div>
                        <p class="text-gray-600 dark:text-gray-300 mb-6">
                            Nous réalisons des projets de construction modernes et durables, 
                            respectant les normes internationales et adaptés au climat local.
                        </p>
                        <ul class="space-y-3">
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Résidences haut de gamme</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Complexes commerciaux</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Infrastructures publiques</span>
                            </li>
                        </ul>
                    </div>
                </div>
                
                <div class="hover-scale">
                    <img src="https://images.unsplash.com/photo-1541976590-713941681591?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=400" 
                         alt="Projet de construction" 
                         class="w-full h-80 object-cover rounded-xl shadow-lg">
                </div>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12 items-center mt-16">
                <div class="order-2 lg:order-1 hover-scale">
                    <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=400" 
                         alt="Aménagement urbain" 
                         class="w-full h-80 object-cover rounded-xl shadow-lg">
                </div>
                
                <!-- Aménagement Urbain -->
                <div class="order-1 lg:order-2 fade-in">
                    <div class="bg-white dark:bg-gray-900 p-8 rounded-xl shadow-lg">
                        <div class="flex items-center mb-6">
                            <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4">
                                <i class="fas fa-city text-xl text-primary"></i>
                            </div>
                            <h3 class="text-2xl font-bold">Aménagement Urbain</h3>
                        </div>
                        <p class="text-gray-600 dark:text-gray-300 mb-6">
                            Planification et développement d'espaces urbains intelligents, 
                            intégrant les dernières technologies pour un mode de vie moderne.
                        </p>
                        <ul class="space-y-3">
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Quartiers résidentiels</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Zones commerciales</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-primary mr-3"></i>
                                <span>Espaces verts et loisirs</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-20 bg-white dark:bg-gray-900">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    Questions Fréquentes
                </h2>
                <p class="text-xl text-gray-600 dark:text-gray-300">
                    Trouvez les réponses à vos questions les plus courantes
                </p>
            </div>
            
            <div class="space-y-4">
                <!-- FAQ Item 1 -->
                <div class="border border-gray-200 dark:border-gray-700 rounded-lg">
                    <button class="faq-button w-full px-6 py-4 text-left flex justify-between items-center hover:bg-gray-50 dark:hover:bg-gray-800 transition-colors">
                        <span class="font-semibold">Quels sont vos secteurs d'intervention ?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-content hidden px-6 pb-4">
                        <p class="text-gray-600 dark:text-gray-300">
                            Nous intervenons principalement en Guinée (Conakry, régions) et dans plusieurs pays d'Afrique de l'Ouest. 
                            Nous développons également notre présence à l'international.
                        </p>
                    </div>
                </div>
                
                <!-- FAQ Item 2 -->
                <div class="border border-gray-200 dark:border-gray-700 rounded-lg">
                    <button class="faq-button w-full px-6 py-4 text-left flex justify-between items-center hover:bg-gray-50 dark:hover:bg-gray-800 transition-colors">
                        <span class="font-semibold">Proposez-vous des facilités de paiement ?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-content hidden px-6 pb-4">
                        <p class="text-gray-600 dark:text-gray-300">
                            Oui, nous proposons des plans de financement flexibles adaptés à vos besoins, 
                            incluant des échéanciers personnalisés et des partenariats avec des institutions financières.
                        </p>
                    </div>
                </div>
                
                <!-- FAQ Item 3 -->
                <div class="border border-gray-200 dark:border-gray-700 rounded-lg">
                    <button class="faq-button w-full px-6 py-4 text-left flex justify-between items-center hover:bg-gray-50 dark:hover:bg-gray-800 transition-colors">
                        <span class="font-semibold">Combien de temps prend une transaction immobilière ?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-content hidden px-6 pb-4">
                        <p class="text-gray-600 dark:text-gray-300">
                            Le délai varie selon le type de transaction, mais nous nous engageons à finaliser 
                            les ventes en 30-60 jours et les locations en 7-15 jours, documents complets fournis.
                        </p>
                    </div>
                </div>
                
                <!-- FAQ Item 4 -->
                <div class="border border-gray-200 dark:border-gray-700 rounded-lg">
                    <button class="faq-button w-full px-6 py-4 text-left flex justify-between items-center hover:bg-gray-50 dark:hover:bg-gray-800 transition-colors">
                        <span class="font-semibold">Offrez-vous des garanties sur vos constructions ?</span>
                        <i class="fas fa-chevron-down transition-transform"></i>
                    </button>
                    <div class="faq-content hidden px-6 pb-4">
                        <p class="text-gray-600 dark:text-gray-300">
                            Absolument ! Nous offrons une garantie de 10 ans sur la structure et 2 ans sur les finitions. 
                            Notre service après-vente assure un suivi continu de la qualité.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    Actualités & Blog
                </h2>
                <p class="text-xl text-gray-600 dark:text-gray-300">
                    Restez informés de nos derniers projets et de l'actualité immobilière
                </p>
            </div>
            
            <!-- Articles Grid -->
            <div class="space-y-16">
                <!-- Article 1 - Marché immobilier 2024 -->
                <article class="bg-white dark:bg-gray-900 rounded-xl shadow-lg overflow-hidden fade-in">
                    <div class="grid lg:grid-cols-2 gap-8">
                        <div class="lg:order-1">
                            <img src="https://images.unsplash.com/photo-1560472354-b33ff0c44a43?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=400" 
                                 alt="Marché immobilier guinéen 2024" 
                                 class="w-full h-64 lg:h-full object-cover">
                        </div>
                        <div class="p-8 lg:order-2">
                            <span class="text-sm text-primary font-semibold">15 Mars 2024</span>
                            <h3 class="text-2xl lg:text-3xl font-bold mt-2 mb-4 text-gray-900 dark:text-white">
                                Le marché immobilier guinéen en 2024
                            </h3>
                            <div class="text-gray-600 dark:text-gray-300 space-y-4">
                                <p>
                                    Le secteur immobilier en Guinée connaît une transformation remarquable en 2024, marquée par une croissance soutenue et l'émergence de nouvelles opportunités d'investissement. Amina Immobilier International, en tant qu'acteur majeur de ce marché, observe des tendances prometteuses qui redéfinissent le paysage urbain du pays.
                                </p>
                                <p>
                                    La demande en logements résidentiels a augmenté de 35% par rapport à 2023, principalement due à l'urbanisation croissante et à l'amélioration du pouvoir d'achat de la classe moyenne guinéenne. Cette dynamique s'accompagne d'une modernisation des infrastructures urbaines, notamment dans la région de Conakry et ses environs, où notre projet phare de Dubréka illustre parfaitement cette évolution.
                                </p>
                                <p>
                                    Les investisseurs internationaux montrent un intérêt grandissant pour le marché guinéen, attirés par la stabilité politique croissante et les réformes économiques favorables. Le gouvernement guinéen a mis en place des mesures incitatives pour encourager l'investissement dans le secteur immobilier, incluant des exonérations fiscales pour les projets de logements sociaux et des facilités de création d'entreprises pour les promoteurs immobiliers.
                                </p>
                                <p>
                                    L'innovation technologique transforme également le secteur. L'adoption de nouvelles technologies de construction, l'utilisation de matériaux locaux durables et l'intégration de solutions énergétiques renouvelables deviennent des standards. Nos équipes techniques travaillent constamment sur l'amélioration des processus de construction pour réduire les coûts tout en maintenant une qualité optimale.
                                </p>
                                <p>
                                    Les perspectives pour la fin 2024 et 2025 restent très optimistes. Nous anticipons une consolidation du marché avec l'émergence de projets d'envergure, notamment dans le secteur des logements abordables et des complexes commerciaux intégrés. Amina Immobilier International se positionne comme un leader dans cette transformation, apportant expertise internationale et connaissance locale pour répondre aux besoins croissants du marché guinéen.
                                </p>
                            </div>
                        </div>
                    </div>
                </article>

                <!-- Article 2 - Construction écologique -->
                <article class="bg-white dark:bg-gray-900 rounded-xl shadow-lg overflow-hidden fade-in">
                    <div class="grid lg:grid-cols-2 gap-8">
                        <div class="lg:order-2">
                            <img src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=400" 
                                 alt="Construction écologique durable" 
                                 class="w-full h-64 lg:h-full object-cover">
                        </div>
                        <div class="p-8 lg:order-1">
                            <span class="text-sm text-primary font-semibold">10 Mars 2024</span>
                            <h3 class="text-2xl lg:text-3xl font-bold mt-2 mb-4 text-gray-900 dark:text-white">
                                Construction écologique et durable
                            </h3>
                            <div class="text-gray-600 dark:text-gray-300 space-y-4">
                                <p>
                                    Chez Amina Immobilier International, nous plaçons le développement durable au cœur de notre stratégie de construction. Nos initiatives écologiques ne sont pas seulement un engagement envers l'environnement, mais aussi une réponse aux défis climatiques spécifiques de l'Afrique de l'Ouest et aux besoins énergétiques croissants de la Guinée.
                                </p>
                                <p>
                                    Notre approche de construction écologique intègre plusieurs innovations révolutionnaires. Nous utilisons des matériaux locaux comme la terre stabilisée et les briques en argile, réduisant ainsi l'empreinte carbone liée au transport tout en soutenant l'économie locale. Ces matériaux offrent une excellente isolation thermique, particulièrement adaptée au climat tropical de la Guinée, permettant de réduire significativement les besoins en climatisation.
                                </p>
                                <p>
                                    L'intégration de systèmes solaires représente un pilier fondamental de nos constructions. Chaque projet d'Amina Immobilier incorpore des panneaux photovoltaïques dimensionnés pour couvrir au minimum 60% des besoins énergétiques des résidents. Cette approche permet non seulement de réduire les factures d'électricité des occupants, mais aussi de contribuer à l'indépendance énergétique nationale en réduisant la pression sur le réseau électrique traditionnel.
                                </p>
                                <p>
                                    La gestion durable de l'eau constitue un autre axe majeur de nos initiatives. Nous installons des systèmes de récupération des eaux pluviales et des dispositifs de traitement des eaux grises dans tous nos projets résidentiels. Ces systèmes permettent de réduire la consommation d'eau potable de 40% en moyenne, un avantage considérable dans un contexte où l'accès à l'eau reste un défi dans certaines régions guinéennes.
                                </p>
                                <p>
                                    Notre engagement écologique s'étend également à la préservation de la biodiversité locale. Chaque projet d'aménagement urbain inclut des espaces verts conçus avec des espèces végétales endémiques, créant des corridors écologiques urbains. Cette approche contribue à maintenir la qualité de l'air, à réguler la température urbaine et à offrir des espaces de vie agréables aux résidents, tout en préservant l'écosystème local pour les générations futures.
                                </p>
                            </div>
                        </div>
                    </div>
                </article>

                <!-- Article 3 - Guide d'investissement -->
                <article class="bg-white dark:bg-gray-900 rounded-xl shadow-lg overflow-hidden fade-in">
                    <div class="grid lg:grid-cols-2 gap-8">
                        <div class="lg:order-1">
                            <img src="https://images.unsplash.com/photo-1582407947304-fd86f028f716?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&h=400" 
                                 alt="Guide investissement immobilier" 
                                 class="w-full h-64 lg:h-full object-cover">
                        </div>
                        <div class="p-8 lg:order-2">
                            <span class="text-sm text-primary font-semibold">5 Mars 2024</span>
                            <h3 class="text-2xl lg:text-3xl font-bold mt-2 mb-4 text-gray-900 dark:text-white">
                                Guide d'investissement immobilier
                            </h3>
                            <div class="text-gray-600 dark:text-gray-300 space-y-4">
                                <p>
                                    L'investissement immobilier en Afrique de l'Ouest, et particulièrement en Guinée, présente des opportunités exceptionnelles pour les investisseurs avisés. Avec plus de dix années d'expérience sur le marché local, Amina Immobilier International partage ses conseils essentiels pour maximiser vos chances de succès dans ce secteur en pleine expansion.
                                </p>
                                <p>
                                    La première étape cruciale consiste à comprendre les spécificités du marché local. En Guinée, la demande est particulièrement forte pour les logements de standing moyen dans les zones urbaines périphériques, où les prix restent accessibles tout en offrant un potentiel d'appréciation élevé. Notre analyse montre que les investissements dans la région de Dubréka, par exemple, génèrent des rendements moyens de 12 à 15% par an, nettement supérieurs aux standards européens.
                                </p>
                                <p>
                                    Le choix de l'emplacement demeure le facteur déterminant du succès. Privilégiez les zones en développement bénéficiant d'infrastructures en cours d'amélioration : accès routier facilité, projets d'électrification, proximité des centres d'activité économique. Les investisseurs intelligents anticipent le développement urbain plutôt que de suivre les tendances établies. C'est précisément cette philosophie qui guide nos choix d'implantation et explique le succès de nos projets.
                                </p>
                                <p>
                                    La diversification de votre portefeuille immobilier s'avère indispensable pour minimiser les risques. Nous recommandons une répartition équilibrée entre logements résidentiels, espaces commerciaux et terrains constructibles. Cette stratégie permet de bénéficier des différents cycles du marché et de maintenir des revenus stables même en période d'incertitude économique. Nos experts accompagnent les investisseurs dans cette démarche de diversification intelligente.
                                </p>
                                <p>
                                    Enfin, l'accompagnement professionnel reste primordial pour naviguer dans l'environnement réglementaire et fiscal local. Amina Immobilier International propose des services complets d'accompagnement juridique, de gestion locative et de maintenance, permettant aux investisseurs de se concentrer sur leur stratégie globale. Notre expertise locale et notre réseau de partenaires financiers facilitent l'accès aux financements avantageux et optimisent la rentabilité de chaque investissement, garantissant ainsi une expérience d'investissement sereine et profitable.
                                </p>
                            </div>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white dark:bg-gray-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 dark:text-white mb-4">
                    Contactez-nous
                </h2>
                <p class="text-xl text-gray-600 dark:text-gray-300">
                    Prêt à concrétiser votre projet immobilier ? Parlons-en !
                </p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <!-- Contact Info -->
                <div class="space-y-8">
                    <div class="flex items-start">
                        <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4 mt-1">
                            <i class="fas fa-map-marker-alt text-primary"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold mb-2">Adresse</h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Kaloum, Conakry<br>
                                République de Guinée
                            </p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4 mt-1">
                            <i class="fas fa-phone text-primary"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold mb-2">Téléphone</h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                +224 628 388 822 (Guinée)<br>
                                +33 773 726 590 (France)
                            </p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4 mt-1">
                            <i class="fas fa-envelope text-primary"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold mb-2">Email</h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                mandjoucamara19@gmail.com<br>
                                contact@amina-immobilier.gn
                            </p>
                        </div>
                    </div>
                    
                    <div class="flex items-start">
                        <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mr-4 mt-1">
                            <i class="fas fa-clock text-primary"></i>
                        </div>
                        <div>
                            <h3 class="text-lg font-semibold mb-2">Horaires</h3>
                            <p class="text-gray-600 dark:text-gray-300">
                                Lundi - Vendredi: 8h00 - 18h00<br>
                                Samedi: 9h00 - 13h00
                            </p>
                        </div>
                    </div>
                </div>
                
                <!-- Contact Form -->
                <div class="bg-gray-50 dark:bg-gray-800 p-8 rounded-xl">
                    <form id="contact-form" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label for="nom" class="block text-sm font-medium mb-2">Nom complet</label>
                                <input type="text" id="nom" name="nom" required
                                       class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-700 dark:text-white">
                            </div>
                            <div>
                                <label for="email" class="block text-sm font-medium mb-2">Email</label>
                                <input type="email" id="email" name="email" required
                                       class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-700 dark:text-white">
                            </div>
                        </div>
                        
                        <div>
                            <label for="telephone" class="block text-sm font-medium mb-2">Téléphone</label>
                            <input type="tel" id="telephone" name="telephone"
                                   class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-700 dark:text-white">
                        </div>
                        
                        <div>
                            <label for="sujet" class="block text-sm font-medium mb-2">Sujet</label>
                            <select id="sujet" name="sujet" required
                                    class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-700 dark:text-white">
                                <option value="">Sélectionner un sujet</option>
                                <option value="achat">Achat de propriété</option>
                                <option value="vente">Vente de propriété</option>
                                <option value="location">Location</option>
                                <option value="construction">Construction</option>
                                <option value="investissement">Investissement</option>
                                <option value="autre">Autre</option>
                            </select>
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium mb-2">Message</label>
                            <textarea id="message" name="message" rows="5" required
                                      class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-700 dark:text-white"
                                      placeholder="Décrivez votre projet ou vos besoins..."></textarea>
                        </div>
                        
                        <button type="submit"
                                class="w-full bg-primary text-white py-3 px-6 rounded-lg font-semibold hover:bg-primary/90 transition-colors">
                            Envoyer le message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Company Info -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Amina Immobilier International</h3>
                    <p class="text-gray-300 mb-4">
                        Votre partenaire de confiance pour tous vos projets immobiliers en Guinée et à l'international.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-300 hover:text-primary transition-colors">
                            <i class="fab fa-facebook text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-primary transition-colors">
                            <i class="fab fa-twitter text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-primary transition-colors">
                            <i class="fab fa-linkedin text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-primary transition-colors">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <!-- Services -->
                <div>
                    <h4 class="text-lg font-semibold mb-4">Services</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li><a href="#" class="hover:text-primary transition-colors">Vente de propriétés</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Location</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Investissement</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Gestion de propriétés</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Conseil juridique</a></li>
                    </ul>
                </div>
                
                <!-- Activités -->
                <div>
                    <h4 class="text-lg font-semibold mb-4">Activités</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li><a href="#" class="hover:text-primary transition-colors">Construction</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Aménagement urbain</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Résidences</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Commerces</a></li>
                        <li><a href="#" class="hover:text-primary transition-colors">Infrastructures</a></li>
                    </ul>
                </div>
                
                <!-- Contact Info -->
                <div>
                    <h4 class="text-lg font-semibold mb-4">Contact</h4>
                    <div class="space-y-2 text-gray-300">
                        <p><i class="fas fa-map-marker-alt mr-2"></i>Kaloum, Conakry, Guinée</p>
                        <p><i class="fas fa-phone mr-2"></i>+224 628 388 822</p>
                        <p><i class="fas fa-envelope mr-2"></i>mandjoucamara19@gmail.com</p>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-12 pt-8 text-center text-gray-300">
                <p>&copy; 2024 Amina Immobilier International. Tous droits réservés.</p>
                <p class="text-sm mt-2">SIREN : 991097163 | SIRET : 99109716300018</p>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script>
        // Dark mode detection
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.documentElement.classList.add('dark');
        }
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
            if (event.matches) {
                document.documentElement.classList.add('dark');
            } else {
                document.documentElement.classList.remove('dark');
            }
        });

        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking on a link
        const mobileMenuLinks = document.querySelectorAll('#mobile-menu a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // FAQ Toggle
        const faqButtons = document.querySelectorAll('.faq-button');
        faqButtons.forEach(button => {
            button.addEventListener('click', () => {
                const content = button.nextElementSibling;
                const icon = button.querySelector('i');
                
                // Close other FAQ items
                faqButtons.forEach(otherButton => {
                    if (otherButton !== button) {
                        const otherContent = otherButton.nextElementSibling;
                        const otherIcon = otherButton.querySelector('i');
                        otherContent.classList.add('hidden');
                        otherIcon.style.transform = 'rotate(0deg)';
                    }
                });
                
                // Toggle current FAQ item
                content.classList.toggle('hidden');
                if (content.classList.contains('hidden')) {
                    icon.style.transform = 'rotate(0deg)';
                } else {
                    icon.style.transform = 'rotate(180deg)';
                }
            });
        });

        // Custom modal functions
        function showAlert(message) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
            modal.innerHTML = `
                <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                    <div class="flex items-center mb-4">
                        <i class="fas fa-info-circle text-primary text-2xl mr-3"></i>
                        <h3 class="text-lg font-semibold">Information</h3>
                    </div>
                    <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                    <div class="flex justify-end">
                        <button class="px-4 py-2 bg-primary text-white hover:bg-primary/90 rounded" onclick="this.closest('.fixed').remove()">OK</button>
                    </div>
                </div>
            `;
            document.body.appendChild(modal);
        }

        // Contact form submission
        document.getElementById('contact-form').addEventListener('submit', (e) => {
            e.preventDefault();
            
            const formData = new FormData(e.target);
            const data = Object.fromEntries(formData);
            
            // Simple validation
            if (!data.nom || !data.email || !data.sujet || !data.message) {
                showAlert('Veuillez remplir tous les champs obligatoires.');
                return;
            }
            
            // Simulate form submission
            showAlert('Votre message a été envoyé avec succès ! Nous vous contacterons bientôt.');
            e.target.reset();
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add fade-in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observe all elements with fade-in class
        document.querySelectorAll('.fade-in').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(20px)';
            el.style.transition = 'opacity 0.8s ease, transform 0.8s ease';
            observer.observe(el);
        });
    </script>
</body>
</html>
