<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>DevPortfolio - AI &amp; Full Stack Engineer</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&amp;family=Noto+Sans:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#1337ec",
                        "background-light": "#f6f6f8",
                        "background-dark": "#101322",
                        "card-dark": "#191e33",
                        "border-dark": "#232948",
                        "text-secondary": "#929bc9"
                    },
                    fontFamily: {
                        "display": ["Space Grotesk", "sans-serif"],
                        "body": ["Noto Sans", "sans-serif"]
                    },
                    borderRadius: {
                        "DEFAULT": "0.5rem",
                        "lg": "0.75rem",
                        "xl": "1rem",
                        "full": "9999px"
                    },
                },
            },
        }
    </script>
<style>
        body {
            font-family: 'Space Grotesk', sans-serif;
        }
        .material-symbols-outlined {
            font-variation-settings:
            'FILL' 0,
            'wght' 400,
            'GRAD' 0,
            'opsz' 24
        }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark text-slate-900 dark:text-white overflow-x-hidden transition-colors duration-300">
<!-- Navbar -->
<header class="sticky top-0 z-50 w-full border-b border-solid border-slate-200 dark:border-border-dark bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-md">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex h-16 items-center justify-between">
<!-- Logo -->
<div class="flex items-center gap-3">
<div class="flex items-center justify-center size-8 text-primary">
<span class="material-symbols-outlined !text-[32px]">terminal</span>
</div>
<h2 class="text-xl font-bold tracking-tight">Dev<span class="text-primary">Portfolio</span></h2>
</div>
<!-- Desktop Nav -->
<nav class="hidden md:flex items-center gap-8">
<a class="text-sm font-medium hover:text-primary transition-colors" href="#about">About</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#tech-stack">Tech Stack</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#projects">Projects</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#contact">Contact</a>
<button class="bg-primary hover:bg-blue-700 text-white text-sm font-bold px-5 py-2 rounded-lg transition-colors duration-200">
                        Resume
                    </button>
</nav>
<!-- Mobile Menu Icon (Placeholder) -->
<button class="md:hidden p-2 text-slate-600 dark:text-slate-300">
<span class="material-symbols-outlined">menu</span>
</button>
</div>
</div>
</header>
<main class="flex flex-col w-full">
<!-- Hero Section -->
<section class="relative w-full py-20 lg:py-32 px-4 sm:px-6 lg:px-8 overflow-hidden">
<!-- Background Glow Effect -->
<div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 bg-primary/20 rounded-full blur-3xl pointer-events-none"></div>
<div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 bg-primary/10 rounded-full blur-3xl pointer-events-none"></div>
<div class="max-w-[1200px] mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="flex flex-col gap-6 z-10">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary/10 border border-primary/20 w-fit">
<span class="relative flex h-2 w-2">
<span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-primary opacity-75"></span>
<span class="relative inline-flex rounded-full h-2 w-2 bg-primary"></span>
</span>
<span class="text-xs font-semibold text-primary uppercase tracking-wider">Available for work</span>
</div>
<h1 class="text-5xl md:text-6xl lg:text-7xl font-bold leading-tight tracking-tight">
                        Hi, I'm Alex. <br/>
<span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-blue-400">Intelligent Solutions</span> Builder.
                    </h1>
<p class="text-lg text-slate-600 dark:text-text-secondary max-w-lg leading-relaxed">
                        Full-Stack Engineer &amp; AI Enthusiast bridging the gap between traditional software engineering and modern AI capabilities.
                    </p>
<div class="flex flex-wrap gap-4 pt-4">
<button class="bg-primary hover:bg-blue-700 text-white font-bold px-8 py-3 rounded-lg transition-all shadow-lg shadow-primary/25">
                            View Projects
                        </button>
<button class="bg-transparent border border-slate-300 dark:border-border-dark hover:bg-slate-100 dark:hover:bg-card-dark text-slate-900 dark:text-white font-medium px-8 py-3 rounded-lg transition-all flex items-center gap-2">
<span class="material-symbols-outlined text-[20px]">hub</span>
<span>GitHub Profile</span>
</button>
</div>
</div>
<div class="relative w-full h-[400px] lg:h-[500px] rounded-2xl overflow-hidden bg-card-dark border border-border-dark shadow-2xl z-10 group" data-alt="Abstract code visualization with glowing nodes on a dark background">
<div class="absolute inset-0 bg-cover bg-center opacity-80 mix-blend-overlay" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuAz_arrB3Aa2jKgPTiixFPHSf1IGHWFGH84I-87zIGf1JZ9Gf0mnfPq6Np-yQU4QMFydIotp1M0W4W0q4WyhW7VvXzqGAJGD0bUjSHu4XaAnPob28INteXvv0shiLv1gLrJYKd2A8ZlQbbefXrW_PgQwvWJDTJcZsVPO5hBsoXSk3SGiW2Pz7Pdg-cHhTLgwEiaZTocKp_sbpoWUQDHLjZ24Xc0zPjeOvGfiKJyP3DajyU9KU_hI6UGNJojElB-PNt1cdCs-Otq-SE7');"></div>
<!-- Decorative UI elements inside image container -->
<div class="absolute inset-0 bg-gradient-to-t from-background-dark via-transparent to-transparent"></div>
<div class="absolute bottom-6 left-6 right-6 p-4 bg-background-dark/80 backdrop-blur-md border border-border-dark rounded-xl">
<div class="flex items-center gap-3 mb-2">
<span class="material-symbols-outlined text-primary">smart_toy</span>
<span class="text-sm font-bold text-white">AI Model Training</span>
</div>
<div class="w-full bg-slate-700 rounded-full h-2 mb-2">
<div class="bg-primary h-2 rounded-full" style="width: 78%"></div>
</div>
<div class="flex justify-between text-xs text-text-secondary font-mono">
<span>Epoch: 1024/5000</span>
<span>Loss: 0.042</span>
</div>
</div>
</div>
</div>
</section>
<!-- About Section -->
<section class="py-20 bg-slate-50 dark:bg-black/20" id="about">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex flex-col md:flex-row gap-12">
<div class="md:w-1/3">
<h2 class="text-3xl font-bold mb-4 flex items-center gap-2">
<span class="w-8 h-1 bg-primary rounded-full inline-block"></span>
                            About Me
                        </h2>
</div>
<div class="md:w-2/3">
<h3 class="text-2xl md:text-3xl font-bold mb-6 leading-relaxed">
                            Engineering the Future with <span class="text-primary">Code &amp; Data</span>.
                        </h3>
<p class="text-slate-600 dark:text-text-secondary text-lg mb-8 leading-relaxed">
                            I am a passionate developer bridging the gap between traditional software engineering and modern AI capabilities. My goal is to create intuitive, data-driven applications that solve real-world problems. With over 5 years of experience in full-stack development, I've recently pivoted to integrating LLMs and computer vision into scalable web architectures.
                        </p>
<div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
<!-- Feature 1 -->
<div class="bg-white dark:bg-card-dark p-6 rounded-xl border border-slate-200 dark:border-border-dark shadow-sm hover:border-primary/50 transition-colors">
<div class="w-12 h-12 rounded-lg bg-primary/10 flex items-center justify-center text-primary mb-4">
<span class="material-symbols-outlined">code</span>
</div>
<h4 class="font-bold text-lg mb-2">Full-Stack</h4>
<p class="text-sm text-slate-500 dark:text-text-secondary">Building scalable web apps with React and Node.js.</p>
</div>
<!-- Feature 2 -->
<div class="bg-white dark:bg-card-dark p-6 rounded-xl border border-slate-200 dark:border-border-dark shadow-sm hover:border-primary/50 transition-colors">
<div class="w-12 h-12 rounded-lg bg-primary/10 flex items-center justify-center text-primary mb-4">
<span class="material-symbols-outlined">smartphone</span>
</div>
<h4 class="font-bold text-lg mb-2">Mobile Dev</h4>
<p class="text-sm text-slate-500 dark:text-text-secondary">Creating cross-platform mobile experiences with React Native.</p>
</div>
<!-- Feature 3 -->
<div class="bg-white dark:bg-card-dark p-6 rounded-xl border border-slate-200 dark:border-border-dark shadow-sm hover:border-primary/50 transition-colors">
<div class="w-12 h-12 rounded-lg bg-primary/10 flex items-center justify-center text-primary mb-4">
<span class="material-symbols-outlined">psychology</span>
</div>
<h4 class="font-bold text-lg mb-2">AI Integration</h4>
<p class="text-sm text-slate-500 dark:text-text-secondary">Leveraging OpenAI and TensorFlow for intelligent features.</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Tech Stack Section -->
<section class="py-20 w-full" id="tech-stack">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="text-center max-w-3xl mx-auto mb-16">
<h2 class="text-3xl font-bold mb-4">My Tech Stack</h2>
<p class="text-slate-600 dark:text-text-secondary">Tools and technologies I use to bring ideas to life.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-4">
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-blue-500 mb-2">html</span>
<span class="font-medium text-sm">HTML5</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-yellow-500 mb-2">css</span>
<span class="font-medium text-sm">CSS3</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-yellow-300 mb-2">javascript</span>
<span class="font-medium text-sm">JavaScript</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-cyan-400 mb-2">code_blocks</span>
<span class="font-medium text-sm">React</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-white mb-2">keyboard_command_key</span>
<span class="font-medium text-sm">Next.js</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-green-500 mb-2">terminal</span>
<span class="font-medium text-sm">Node.js</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-blue-400 mb-2">data_object</span>
<span class="font-medium text-sm">Python</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-orange-500 mb-2">neurology</span>
<span class="font-medium text-sm">TensorFlow</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-indigo-400 mb-2">database</span>
<span class="font-medium text-sm">PostgreSQL</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-red-500 mb-2">deployed_code</span>
<span class="font-medium text-sm">Git</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-blue-600 mb-2">cloud</span>
<span class="font-medium text-sm">Docker</span>
</div>
<!-- Tech Item -->
<div class="flex flex-col items-center justify-center p-6 bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl hover:-translate-y-1 transition-transform cursor-default">
<span class="material-symbols-outlined text-4xl text-white mb-2">robot_2</span>
<span class="font-medium text-sm">OpenAI API</span>
</div>
</div>
</div>
</section>
<!-- Projects Section -->
<section class="py-20 bg-slate-50 dark:bg-black/20" id="projects">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex flex-col sm:flex-row justify-between items-end mb-12 gap-4">
<div>
<h2 class="text-3xl font-bold mb-2">Featured Projects</h2>
<p class="text-slate-600 dark:text-text-secondary">A selection of my recent work.</p>
</div>
<a class="text-primary hover:text-blue-400 font-medium flex items-center gap-1" href="#">
                        View all archives <span class="material-symbols-outlined text-lg">arrow_forward</span>
</a>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Project Card 1 -->
<article class="bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl overflow-hidden hover:shadow-2xl hover:shadow-primary/10 transition-all duration-300 flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<div class="absolute inset-0 bg-primary/20 group-hover:bg-transparent transition-colors z-10"></div>
<div class="w-full h-full bg-cover bg-center group-hover:scale-105 transition-transform duration-500" data-alt="Screenshot of an AI Chatbot interface" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuC6VZE0ww-FkJAGxIUUTqrbsdZiArKCjoUfUxcwIo9EKYF5Hw72OY1Oji3uzAZHbcG8hu0qwPHv8RGWeooboj7C7thI5X7l4uDO98iKuYQIn5k4S9SNZHE0XGW5j_ySTta_IiOhbDX24yVR1bgl5DE2XIL0ZV0d5mVMw5xs9HSL-Yx1_GI5ZoHxIJotfwWDuyxezLjXXW4xVz-Gylukx3tsNdbcrcI9R9OmXF4z-rKAKuwFyoYr7KR2oRX92Il2CHG7lJRo6WtyUoX0');"></div>
</div>
<div class="p-6 flex flex-col flex-1">
<div class="flex justify-between items-start mb-4">
<h3 class="text-xl font-bold group-hover:text-primary transition-colors">NeuralChat Bot</h3>
<div class="flex gap-2">
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">code</span></a>
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">open_in_new</span></a>
</div>
</div>
<p class="text-slate-600 dark:text-text-secondary text-sm mb-6 flex-1">
                                An intelligent conversational agent built with Python and OpenAI's GPT-4 API. Features context retention and custom knowledge base integration.
                            </p>
<div class="flex flex-wrap gap-2 mt-auto">
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">Python</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">React</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">OpenAI</span>
</div>
</div>
</article>
<!-- Project Card 2 -->
<article class="bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl overflow-hidden hover:shadow-2xl hover:shadow-primary/10 transition-all duration-300 flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<div class="absolute inset-0 bg-primary/20 group-hover:bg-transparent transition-colors z-10"></div>
<div class="w-full h-full bg-cover bg-center group-hover:scale-105 transition-transform duration-500" data-alt="E-commerce mobile application screens" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBuha3kdZmsk_X9ebnqLpUZN3bRCljE0J194m7K-nx2lcp3Dpl_su2NxuLDtIekp8NJFy6pc7b74jY0NSMkvDcH6tqNK3w_O5ZCHQqgFqA9xy7nAYVtBUMMEyZxUkC7hV_bT-qKe2Ek5gR1biYxSWvuEzcU7Aq5hgXjX9BjMtUUs3Yu9AGPs61a66oQrglUgnCIVkmsw8hUEkef17e7GrdaVkau9zn1U0bGggITyu6ZiOCvkxy1FTu_sl8jM5jN6WNfG6jRozkKCSPP');"></div>
</div>
<div class="p-6 flex flex-col flex-1">
<div class="flex justify-between items-start mb-4">
<h3 class="text-xl font-bold group-hover:text-primary transition-colors">ShopSwift Mobile</h3>
<div class="flex gap-2">
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">code</span></a>
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">open_in_new</span></a>
</div>
</div>
<p class="text-slate-600 dark:text-text-secondary text-sm mb-6 flex-1">
                                A high-performance e-commerce mobile application. Includes real-time inventory tracking, secure Stripe payments, and AR product preview.
                            </p>
<div class="flex flex-wrap gap-2 mt-auto">
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">React Native</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">Node.js</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">Firebase</span>
</div>
</div>
</article>
<!-- Project Card 3 -->
<article class="bg-white dark:bg-card-dark border border-slate-200 dark:border-border-dark rounded-xl overflow-hidden hover:shadow-2xl hover:shadow-primary/10 transition-all duration-300 flex flex-col h-full group">
<div class="h-48 overflow-hidden relative">
<div class="absolute inset-0 bg-primary/20 group-hover:bg-transparent transition-colors z-10"></div>
<div class="w-full h-full bg-cover bg-center group-hover:scale-105 transition-transform duration-500" data-alt="SaaS analytics dashboard interface" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDsShgRNCm48RDAyn1vYz-y499vfDw_yKw1Da93Y4lqw_dc9s_L5QOfF_0B5jMOX--zrK-hDE7SXLLNPsyDeDcFtBO_4yNlFtdaH4RQGP0FC9NzqT0NpU-cDUd8csiet9P2DbU8oB1fa8eSC6aPhFsPlH8xQyi9mSbEpj_jG4ISsFH10L3GnjYcR-vShyYL6k0svAIR1WSCpH94LSN1M7JBPk6PCjJ0VTD8oI8PgIT2Bp6QgOuESaLQ-c30fl6jfgNi2iR2xks8bSrb');"></div>
</div>
<div class="p-6 flex flex-col flex-1">
<div class="flex justify-between items-start mb-4">
<h3 class="text-xl font-bold group-hover:text-primary transition-colors">Vision Analytics</h3>
<div class="flex gap-2">
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">code</span></a>
<a class="text-slate-400 hover:text-white" href="#"><span class="material-symbols-outlined">open_in_new</span></a>
</div>
</div>
<p class="text-slate-600 dark:text-text-secondary text-sm mb-6 flex-1">
                                A SaaS dashboard for visualizing complex datasets. Uses machine learning to predict trends and anomalies in user data streams.
                            </p>
<div class="flex flex-wrap gap-2 mt-auto">
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">Next.js</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">D3.js</span>
<span class="px-3 py-1 bg-background-light dark:bg-background-dark rounded-full text-xs font-mono text-primary">SciKit Learn</span>
</div>
</div>
</article>
</div>
</div>
</section>
<!-- GitHub Stats Section -->
<section class="py-20 w-full border-y border-border-dark bg-card-dark">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="flex flex-col lg:flex-row gap-8 items-center">
<div class="lg:w-1/3">
<h2 class="text-3xl font-bold mb-4">Code Activity</h2>
<p class="text-text-secondary mb-6">
                            I code every day. Here is a snapshot of my contributions over the last year. Always shipping.
                        </p>
<div class="grid grid-cols-2 gap-4">
<div class="bg-background-dark p-4 rounded-lg border border-border-dark">
<span class="block text-2xl font-bold text-white mb-1">1,240</span>
<span class="text-xs text-text-secondary uppercase tracking-wider">Total Commits</span>
</div>
<div class="bg-background-dark p-4 rounded-lg border border-border-dark">
<span class="block text-2xl font-bold text-white mb-1">45</span>
<span class="text-xs text-text-secondary uppercase tracking-wider">Repositories</span>
</div>
</div>
</div>
<!-- Simulated GitHub Graph -->
<div class="lg:w-2/3 w-full overflow-x-auto pb-4 lg:pb-0">
<div class="min-w-[600px] flex flex-col gap-1">
<div class="flex justify-between text-xs text-text-secondary mb-2 font-mono">
<span>Jan</span><span>Feb</span><span>Mar</span><span>Apr</span><span>May</span><span>Jun</span><span>Jul</span><span>Aug</span><span>Sep</span><span>Oct</span><span>Nov</span><span>Dec</span>
</div>
<!-- 7 rows for days of week -->
<!-- We will just create a visual pattern using flex and small divs -->
<div class="flex gap-1">
<!-- Generating random blocks pattern with JS would be ideal, but for HTML only we do a static robust pattern -->
<div class="grid grid-rows-7 grid-flow-col gap-1 w-full">
<!-- Using CSS grid to simulate the chart dots -->
<style>
                                        .gh-dot { width: 10px; height: 10px; border-radius: 2px; }
                                        .l0 { background-color: #1e2538; }
                                        .l1 { background-color: #0e247a; }
                                        .l2 { background-color: #1337ec; }
                                        .l3 { background-color: #5875ff; }
                                        .l4 { background-color: #aebcff; }
                                    </style>
<!-- Just a few static columns for visual rep -->
<!-- Column 1 --> <div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div>
<!-- Column 2 --> <div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div>
<!-- Column 3 --> <div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div>
<!-- Column 4 --> <div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l4"></div><div class="gh-dot l1"></div>
<!-- Column 5 --> <div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l2"></div>
<!-- Column 6 --> <div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div>
<!-- Column 7 --> <div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div>
<!-- Column 8 --> <div class="gh-dot l0"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div>
<!-- Repeat pattern roughly -->
<!-- Column 9 --> <div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 10 --> <div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l0"></div>
<!-- Column 11 --> <div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div>
<!-- Column 12 --> <div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div>
<!-- Column 13 --> <div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div>
<!-- Column 14 --> <div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div>
<!-- Column 15 --> <div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div>
<!-- Column 16 --> <div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 17 --> <div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div>
<!-- Column 18 --> <div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 19 --> <div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div>
<!-- Column 20 --> <div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div>
<!-- Column 21 --> <div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div>
<!-- Column 22 --> <div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 23 --> <div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div>
<!-- Column 24 --> <div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div>
<!-- Column 25 --> <div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 26 --> <div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div>
<!-- Column 27 --> <div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 28 --> <div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div>
<!-- Column 29 --> <div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div>
<!-- Column 30 --> <div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 31 --> <div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div>
<!-- Column 32 --> <div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div>
<!-- Column 33 --> <div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div>
<!-- Column 34 --> <div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div>
<!-- Column 35 --> <div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l3"></div>
<!-- Column 36 --> <div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div>
<!-- Column 37 --> <div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l1"></div>
<!-- Column 38 --> <div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l4"></div>
<!-- Column 39 --> <div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 40 --> <div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div>
<!-- Column 41 --> <div class="gh-dot l4"></div><div class="gh-dot l4"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l1"></div><div class="gh-dot l2"></div>
<!-- Column 42 --> <div class="gh-dot l3"></div><div class="gh-dot l3"></div><div class="gh-dot l2"></div><div class="gh-dot l1"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div><div class="gh-dot l0"></div>
</div>
</div>
<div class="flex items-center gap-1 text-xs text-text-secondary mt-2 justify-end font-mono">
<span>Less</span>
<div class="gh-dot l0"></div>
<div class="gh-dot l1"></div>
<div class="gh-dot l2"></div>
<div class="gh-dot l3"></div>
<div class="gh-dot l4"></div>
<span>More</span>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section class="py-20 bg-slate-50 dark:bg-black/20" id="contact">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div class="flex flex-col gap-6">
<h2 class="text-4xl font-bold">Let's build something <span class="text-primary">intelligent</span> together.</h2>
<p class="text-slate-600 dark:text-text-secondary text-lg">
                            I'm currently available for freelance projects and open to full-time opportunities. If you have a project that needs some AI magic, let's talk.
                        </p>
<div class="flex flex-col gap-4 mt-4">
<a class="flex items-center gap-3 text-lg font-medium hover:text-primary transition-colors" href="mailto:hello@alexdev.com">
<span class="material-symbols-outlined text-primary">mail</span>
                                hello@alexdev.com
                            </a>
<a class="flex items-center gap-3 text-lg font-medium hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined text-primary">location_on</span>
                                San Francisco, CA (Remote Friendly)
                            </a>
</div>
</div>
<!-- Contact Form -->
<div class="bg-white dark:bg-card-dark p-8 rounded-xl border border-slate-200 dark:border-border-dark shadow-lg">
<form class="flex flex-col gap-4">
<div class="grid grid-cols-2 gap-4">
<div class="flex flex-col gap-2">
<label class="text-sm font-bold text-slate-700 dark:text-slate-300">Name</label>
<input class="w-full h-12 px-4 rounded-lg bg-background-light dark:bg-background-dark border border-slate-300 dark:border-border-dark focus:border-primary focus:ring-1 focus:ring-primary outline-none transition-all" placeholder="John Doe" type="text"/>
</div>
<div class="flex flex-col gap-2">
<label class="text-sm font-bold text-slate-700 dark:text-slate-300">Email</label>
<input class="w-full h-12 px-4 rounded-lg bg-background-light dark:bg-background-dark border border-slate-300 dark:border-border-dark focus:border-primary focus:ring-1 focus:ring-primary outline-none transition-all" placeholder="john@example.com" type="email"/>
</div>
</div>
<div class="flex flex-col gap-2">
<label class="text-sm font-bold text-slate-700 dark:text-slate-300">Subject</label>
<input class="w-full h-12 px-4 rounded-lg bg-background-light dark:bg-background-dark border border-slate-300 dark:border-border-dark focus:border-primary focus:ring-1 focus:ring-primary outline-none transition-all" placeholder="Project Inquiry" type="text"/>
</div>
<div class="flex flex-col gap-2">
<label class="text-sm font-bold text-slate-700 dark:text-slate-300">Message</label>
<textarea class="w-full h-32 px-4 py-3 rounded-lg bg-background-light dark:bg-background-dark border border-slate-300 dark:border-border-dark focus:border-primary focus:ring-1 focus:ring-primary outline-none transition-all resize-none" placeholder="Tell me about your project..."></textarea>
</div>
<button class="bg-primary hover:bg-blue-700 text-white font-bold h-12 rounded-lg mt-2 transition-colors flex items-center justify-center gap-2">
<span>Send Message</span>
<span class="material-symbols-outlined text-sm">send</span>
</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="border-t border-slate-200 dark:border-border-dark py-8 bg-background-light dark:bg-background-dark">
<div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4">
<p class="text-slate-500 dark:text-text-secondary text-sm">
                    © 2023 Alex Developer. Built with Tailwind CSS &amp; Space Grotesk.
                </p>
<div class="flex gap-6">
<a class="text-slate-500 hover:text-primary transition-colors" href="#">LinkedIn</a>
<a class="text-slate-500 hover:text-primary transition-colors" href="#">Twitter</a>
<a class="text-slate-500 hover:text-primary transition-colors" href="#">GitHub</a>
</div>
</div>
</footer>
</main>
</body></html>
