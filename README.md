<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>AlexDev - GitHub Profile Portfolio</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Spline+Sans:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<!-- Theme Config -->
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "primary": "#f9f506",
              "background-light": "#fcfcf8",
              "background-dark": "#1c1c0d",
              "surface-light": "#ffffff",
              "surface-dark": "#262618",
              "border-light": "#f4f4e6",
              "border-dark": "#363628",
              "text-main": "#1c1c0d",
              "text-muted": "#5c5c4f",
              "text-main-dark": "#f2f2e6",
              "text-muted-dark": "#a3a395",
            },
            fontFamily: {
              "display": ["Spline Sans", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "1rem", "lg": "1.5rem", "xl": "2rem", "2xl": "2.5rem", "full": "9999px"},
          },
        },
      }
    </script>
</head>
<body class="font-display bg-background-light dark:bg-background-dark text-text-main dark:text-text-main-dark transition-colors duration-200">
<div class="relative flex min-h-screen w-full flex-col overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<!-- Navbar -->
<header class="sticky top-0 z-50 w-full border-b border-border-light dark:border-border-dark bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-md">
<div class="flex items-center justify-between px-6 py-4 lg:px-20 max-w-[1200px] mx-auto w-full">
<div class="flex items-center gap-3">
<div class="flex h-8 w-8 items-center justify-center rounded-lg bg-primary text-text-main">
<span class="material-symbols-outlined text-xl">terminal</span>
</div>
<h2 class="text-lg font-bold tracking-tight">AlexDev</h2>
</div>
<nav class="hidden md:flex items-center gap-8">
<a class="text-sm font-medium hover:text-primary transition-colors" href="#about">About</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#toolbox">Toolbox</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#projects">Projects</a>
<a class="text-sm font-medium hover:text-primary transition-colors" href="#stats">Stats</a>
</nav>
<div class="flex items-center gap-4">
<button class="hidden sm:flex h-10 items-center justify-center rounded-full bg-surface-light dark:bg-surface-dark border border-border-light dark:border-border-dark px-4 text-sm font-bold shadow-sm hover:bg-gray-50 dark:hover:bg-gray-800 transition-colors">
<span class="truncate">Contact</span>
</button>
<button class="flex h-10 items-center justify-center rounded-full bg-primary px-5 text-sm font-bold text-text-main hover:bg-yellow-300 transition-colors">
<span class="truncate">Hire Me</span>
</button>
</div>
</div>
</header>
<main class="flex-1 flex flex-col items-center w-full">
<div class="w-full max-w-[960px] px-6 lg:px-0 py-8 flex flex-col gap-12">
<!-- Profile Header -->
<section class="flex flex-col gap-6 pt-10" id="about">
<div class="flex flex-col md:flex-row items-start md:items-center gap-8">
<div class="relative group">
<div class="h-32 w-32 md:h-40 md:w-40 rounded-full border-4 border-surface-light dark:border-surface-dark shadow-xl overflow-hidden bg-gray-200">
<img alt="Portrait of a smiling developer in a casual shirt" class="h-full w-full object-cover" data-alt="Portrait of a smiling developer in a casual shirt" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7kglaOSzvCLkt3AOozqhpLTg-jj35sGQ1BDO_557C3GUWpJClKbUJF1xsvgulN1ojsMMmgWXvYL7eBFKoU_M7eqyyKWk_j128mKFQv7iFc68L2tSSHc105mvw1EQi6twFIYvPSG192zMgPIVLX6XCSebWygqHfnjpU7XIFlIZJQyIn3KzNMqSSJ9cAL7SePF7hj9I9wxmqLvv7hMk9ICdQjx-W1T5ntHeCdhiG7-YPxkKMnnXcOCFbQSxOatfhDaQtDr6_aWxIeYU"/>
</div>
<div class="absolute bottom-1 right-1 flex h-8 w-8 items-center justify-center rounded-full bg-primary text-text-main shadow-lg border-2 border-surface-light dark:border-surface-dark">
<span class="material-symbols-outlined text-sm font-bold">waving_hand</span>
</div>
</div>
<div class="flex flex-col gap-3 flex-1">
<h1 class="text-4xl md:text-5xl font-bold leading-tight tracking-tight">
                                Hi, I'm Alex <span class="text-primary">👋</span>
</h1>
<p class="text-xl text-text-muted dark:text-text-muted-dark font-medium max-w-2xl">
                                A <span class="text-text-main dark:text-text-main-dark font-bold decoration-primary decoration-4 underline underline-offset-4">Full-Stack Developer</span> passionate about building accessible web apps and open source tools.
                            </p>
<div class="flex flex-wrap items-center gap-4 mt-2 text-sm text-text-muted dark:text-text-muted-dark">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-lg">location_on</span>
<span>San Francisco, CA</span>
</div>
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-lg">apartment</span>
<span>Senior Engineer @ TechCorp</span>
</div>
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-lg">link</span>
<a class="hover:text-primary transition-colors" href="#">alex.dev</a>
</div>
</div>
</div>
</div>
<!-- Intro Text -->
<div class="bg-surface-light dark:bg-surface-dark p-6 md:p-8 rounded-xl border border-border-light dark:border-border-dark mt-4">
<p class="text-lg leading-relaxed text-text-muted dark:text-text-muted-dark">
                            I am a software engineer with over 5 years of experience in building scalable web applications. I specialize in the JavaScript ecosystem, crafting clean code and intuitive user experiences. When I'm not coding, I'm likely contributing to open source or writing technical blogs.
                        </p>
<div class="flex gap-4 mt-6">
<button class="flex items-center gap-2 text-sm font-bold text-text-main dark:text-text-main-dark bg-border-light dark:bg-border-dark hover:bg-primary/20 hover:text-primary dark:hover:text-primary px-4 py-2 rounded-full transition-all">
<span class="material-symbols-outlined text-lg">description</span>
                                Download Resume
                            </button>
<button class="flex items-center gap-2 text-sm font-bold text-text-main dark:text-text-main-dark bg-border-light dark:bg-border-dark hover:bg-primary/20 hover:text-primary dark:hover:text-primary px-4 py-2 rounded-full transition-all">
<span class="material-symbols-outlined text-lg">mail</span>
                                Email Me
                            </button>
</div>
</div>
</section>
<!-- Skills Section -->
<section class="flex flex-col gap-6" id="toolbox">
<div class="flex items-center gap-3 px-2">
<div class="h-8 w-1.5 bg-primary rounded-full"></div>
<h2 class="text-2xl font-bold">My Toolbox</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<!-- Languages -->
<div class="bg-surface-light dark:bg-surface-dark p-6 rounded-xl border border-border-light dark:border-border-dark">
<h3 class="text-sm font-bold uppercase tracking-wider text-text-muted dark:text-text-muted-dark mb-4">Languages</h3>
<div class="flex flex-wrap gap-2">
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">JavaScript</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">TypeScript</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Python</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Go</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">HTML5</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">CSS3</span>
</div>
</div>
<!-- Frameworks & Libraries -->
<div class="bg-surface-light dark:bg-surface-dark p-6 rounded-xl border border-border-light dark:border-border-dark">
<h3 class="text-sm font-bold uppercase tracking-wider text-text-muted dark:text-text-muted-dark mb-4">Frameworks</h3>
<div class="flex flex-wrap gap-2">
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium flex items-center gap-2">
<span class="w-2 h-2 rounded-full bg-[#61DAFB]"></span> React
                                </span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium flex items-center gap-2">
<span class="w-2 h-2 rounded-full bg-[#000000] dark:bg-white"></span> Next.js
                                </span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Node.js</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Tailwind CSS</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Express</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Django</span>
</div>
</div>
<!-- Tools & DevOps -->
<div class="bg-surface-light dark:bg-surface-dark p-6 rounded-xl border border-border-light dark:border-border-dark md:col-span-2">
<h3 class="text-sm font-bold uppercase tracking-wider text-text-muted dark:text-text-muted-dark mb-4">Tools &amp; DevOps</h3>
<div class="flex flex-wrap gap-2">
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Git</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Docker</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">AWS</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Figma</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">PostgreSQL</span>
<span class="px-3 py-1.5 rounded-full bg-background-light dark:bg-background-dark border border-border-light dark:border-border-dark text-sm font-medium">Vercel</span>
</div>
</div>
</div>
</section>
<!-- Featured Projects -->
<section class="flex flex-col gap-6" id="projects">
<div class="flex items-center justify-between px-2">
<div class="flex items-center gap-3">
<div class="h-8 w-1.5 bg-primary rounded-full"></div>
<h2 class="text-2xl font-bold">Featured Projects</h2>
</div>
<a class="text-sm font-bold text-text-muted hover:text-primary transition-colors flex items-center gap-1" href="#">
                            View All <span class="material-symbols-outlined text-sm">arrow_forward</span>
</a>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<!-- Project 1 -->
<div class="group flex flex-col bg-surface-light dark:bg-surface-dark rounded-xl border border-border-light dark:border-border-dark overflow-hidden hover:border-primary/50 transition-all hover:shadow-lg">
<div class="h-40 w-full bg-background-light dark:bg-background-dark relative overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-tr from-gray-100 to-gray-200 dark:from-gray-800 dark:to-gray-900" data-alt="Abstract gradient background for project thumbnail"></div>
<div class="absolute top-4 right-4 bg-surface-light dark:bg-surface-dark px-2 py-1 rounded-md text-xs font-bold border border-border-light dark:border-border-dark shadow-sm">
                                    Public
                                </div>
</div>
<div class="p-6 flex flex-col flex-1 gap-3">
<div class="flex items-center justify-between">
<h3 class="text-lg font-bold group-hover:text-primary transition-colors">alexdev/ecommerce-api</h3>
<a class="text-text-muted hover:text-text-main dark:text-text-muted-dark dark:hover:text-text-main-dark" href="#">
<span class="material-symbols-outlined">open_in_new</span>
</a>
</div>
<p class="text-text-muted dark:text-text-muted-dark text-sm flex-1">
                                    A robust RESTful API for e-commerce platforms built with Node.js and Express. Features include JWT authentication, Stripe integration, and inventory management.
                                </p>
<div class="flex items-center gap-4 mt-2 text-xs text-text-muted dark:text-text-muted-dark font-medium">
<div class="flex items-center gap-1.5">
<span class="w-3 h-3 rounded-full bg-[#f9f506]"></span>
                                        JavaScript
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">star</span>
                                        1.2k
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">call_split</span>
                                        142
                                    </div>
</div>
</div>
</div>
<!-- Project 2 -->
<div class="group flex flex-col bg-surface-light dark:bg-surface-dark rounded-xl border border-border-light dark:border-border-dark overflow-hidden hover:border-primary/50 transition-all hover:shadow-lg">
<div class="h-40 w-full bg-background-light dark:bg-background-dark relative overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-bl from-gray-200 to-white dark:from-gray-900 dark:to-black" data-alt="Abstract monochrome gradient for project thumbnail"></div>
</div>
<div class="p-6 flex flex-col flex-1 gap-3">
<div class="flex items-center justify-between">
<h3 class="text-lg font-bold group-hover:text-primary transition-colors">alexdev/task-master-v2</h3>
<a class="text-text-muted hover:text-text-main dark:text-text-muted-dark dark:hover:text-text-main-dark" href="#">
<span class="material-symbols-outlined">open_in_new</span>
</a>
</div>
<p class="text-text-muted dark:text-text-muted-dark text-sm flex-1">
                                    A collaborative task management dashboard with real-time updates using WebSockets. Built with React and Firebase.
                                </p>
<div class="flex items-center gap-4 mt-2 text-xs text-text-muted dark:text-text-muted-dark font-medium">
<div class="flex items-center gap-1.5">
<span class="w-3 h-3 rounded-full bg-[#3178C6]"></span>
                                        TypeScript
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">star</span>
                                        850
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">call_split</span>
                                        89
                                    </div>
</div>
</div>
</div>
<!-- Project 3 -->
<div class="group flex flex-col bg-surface-light dark:bg-surface-dark rounded-xl border border-border-light dark:border-border-dark overflow-hidden hover:border-primary/50 transition-all hover:shadow-lg">
<div class="h-40 w-full bg-background-light dark:bg-background-dark relative overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-br from-[#f9f506]/20 to-transparent" data-alt="Subtle yellow gradient background for project thumbnail"></div>
</div>
<div class="p-6 flex flex-col flex-1 gap-3">
<div class="flex items-center justify-between">
<h3 class="text-lg font-bold group-hover:text-primary transition-colors">alexdev/portfolio-theme</h3>
<a class="text-text-muted hover:text-text-main dark:text-text-muted-dark dark:hover:text-text-main-dark" href="#">
<span class="material-symbols-outlined">open_in_new</span>
</a>
</div>
<p class="text-text-muted dark:text-text-muted-dark text-sm flex-1">
                                    A highly customizable, accessible, and performant portfolio theme for developers. Includes dark mode and SEO optimization.
                                </p>
<div class="flex items-center gap-4 mt-2 text-xs text-text-muted dark:text-text-muted-dark font-medium">
<div class="flex items-center gap-1.5">
<span class="w-3 h-3 rounded-full bg-[#563D7C]"></span>
                                        CSS
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">star</span>
                                        432
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">call_split</span>
                                        56
                                    </div>
</div>
</div>
</div>
<!-- Project 4 -->
<div class="group flex flex-col bg-surface-light dark:bg-surface-dark rounded-xl border border-border-light dark:border-border-dark overflow-hidden hover:border-primary/50 transition-all hover:shadow-lg">
<div class="h-40 w-full bg-background-light dark:bg-background-dark relative overflow-hidden">
<div class="absolute inset-0 bg-gradient-to-r from-gray-50 to-gray-100 dark:from-gray-800 dark:to-gray-900" data-alt="Subtle gray noise pattern background"></div>
</div>
<div class="p-6 flex flex-col flex-1 gap-3">
<div class="flex items-center justify-between">
<h3 class="text-lg font-bold group-hover:text-primary transition-colors">alexdev/cli-helper</h3>
<a class="text-text-muted hover:text-text-main dark:text-text-muted-dark dark:hover:text-text-main-dark" href="#">
<span class="material-symbols-outlined">open_in_new</span>
</a>
</div>
<p class="text-text-muted dark:text-text-muted-dark text-sm flex-1">
                                    A command-line tool to automate repetitive git tasks and scaffold new projects instantly.
                                </p>
<div class="flex items-center gap-4 mt-2 text-xs text-text-muted dark:text-text-muted-dark font-medium">
<div class="flex items-center gap-1.5">
<span class="w-3 h-3 rounded-full bg-[#00ADD8]"></span>
                                        Go
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">star</span>
                                        320
                                    </div>
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-sm">call_split</span>
                                        28
                                    </div>
</div>
</div>
</div>
</div>
</section>
<!-- GitHub Stats Visualization -->
<section class="flex flex-col gap-6" id="stats">
<div class="flex items-center gap-3 px-2">
<div class="h-8 w-1.5 bg-primary rounded-full"></div>
<h2 class="text-2xl font-bold">2023 Contributions</h2>
</div>
<div class="bg-surface-light dark:bg-surface-dark p-6 md:p-8 rounded-xl border border-border-light dark:border-border-dark overflow-x-auto">
<div class="flex flex-col min-w-[600px] gap-4">
<!-- Stats Overview Row -->
<div class="flex gap-8 pb-4 border-b border-border-light dark:border-border-dark">
<div>
<div class="text-xs text-text-muted dark:text-text-muted-dark font-bold uppercase">Total Contributions</div>
<div class="text-2xl font-bold mt-1">2,456</div>
</div>
<div>
<div class="text-xs text-text-muted dark:text-text-muted-dark font-bold uppercase">Current Streak</div>
<div class="text-2xl font-bold mt-1 text-primary drop-shadow-[0_1px_1px_rgba(0,0,0,0.8)] dark:drop-shadow-none dark:text-primary">14 Days</div>
</div>
<div>
<div class="text-xs text-text-muted dark:text-text-muted-dark font-bold uppercase">Repositories</div>
<div class="text-2xl font-bold mt-1">42</div>
</div>
</div>
<!-- Heatmap Mockup -->
<div class="flex gap-1">
<!-- Days Labels -->
<div class="flex flex-col justify-between text-[10px] text-text-muted pr-2 pt-8 pb-2 h-32">
<span>Mon</span>
<span>Wed</span>
<span>Fri</span>
</div>
<!-- Grid -->
<div class="flex-1 grid grid-cols-[repeat(52,1fr)] grid-rows-7 gap-1 h-32">
<!-- Generating some random cells to look like a heatmap -->
<!-- In a real app this would be loop generated. I'll simulate a pattern -->
<style>
                                        .c-0 { @apply bg-gray-100 dark:bg-gray-800; }
                                        .c-1 { @apply bg-primary/20; }
                                        .c-2 { @apply bg-primary/40; }
                                        .c-3 { @apply bg-primary/70; }
                                        .c-4 { @apply bg-primary; }
                                        .c-cell { @apply rounded-[2px] w-full h-full; }
                                    </style>
<!-- A simplified manual representation of a heatmap grid -->
<!-- Row 1 -->
<div class="c-cell c-1"></div><div class="c-cell c-0"></div><div class="c-cell c-2"></div><div class="c-cell c-3"></div><div class="c-cell c-4"></div><div class="c-cell c-2"></div><div class="c-cell c-1"></div>
<div class="c-cell c-0"></div><div class="c-cell c-3"></div><div class="c-cell c-4"></div><div class="c-cell c-1"></div><div class="c-cell c-0"></div><div class="c-cell c-2"></div><div class="c-cell c-3"></div>
<div class="c-cell c-2"></div><div class="c-cell c-4"></div><div class="c-cell c-1"></div><div class="c-cell c-0"></div><div class="c-cell c-3"></div><div class="c-cell c-2"></div><div class="c-cell c-4"></div>
<!-- ... Just simulating a few columns with standard html repetition is verbose, will use a visual trick via css background for the rest to keep code clean -->
<div class="col-span-49 row-span-7 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAiIGhlaWdodD0iMTAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHJlY3Qgd2lkdGg9IjgiIGhlaWdodD0iOCIgeD0iMSIgeT0iMSIgZmlsbD0iI2Y5ZjUwNiIgZmlsbC1vcGFjaXR5PSIwLjMiIHJ4PSIyIiByeT0iMiIvPjwvc3ZnPg==')] opacity-50"></div>
</div>
</div>
<div class="flex items-center justify-end gap-2 text-xs text-text-muted mt-2">
<span>Less</span>
<div class="flex gap-1">
<div class="w-3 h-3 rounded-[2px] bg-gray-100 dark:bg-gray-800"></div>
<div class="w-3 h-3 rounded-[2px] bg-primary/20"></div>
<div class="w-3 h-3 rounded-[2px] bg-primary/40"></div>
<div class="w-3 h-3 rounded-[2px] bg-primary/70"></div>
<div class="w-3 h-3 rounded-[2px] bg-primary"></div>
</div>
<span>More</span>
</div>
</div>
</div>
</section>
<!-- Footer CTA -->
<footer class="mt-12 mb-8 flex flex-col items-center gap-8 py-10 border-t border-border-light dark:border-border-dark w-full">
<h2 class="text-3xl font-bold text-center">Let's build something <span class="text-primary underline decoration-4 underline-offset-4">amazing</span> together.</h2>
<div class="flex gap-6">
<a class="h-12 w-12 flex items-center justify-center rounded-full bg-surface-light dark:bg-surface-dark border border-border-light dark:border-border-dark hover:scale-110 hover:border-primary hover:text-primary transition-all shadow-sm" href="#">
<span class="material-symbols-outlined">mail</span>
</a>
<!-- LinkedIn Mock -->
<a class="h-12 w-12 flex items-center justify-center rounded-full bg-surface-light dark:bg-surface-dark border border-border-light dark:border-border-dark hover:scale-110 hover:border-primary hover:text-primary transition-all shadow-sm" href="#">
<span class="material-symbols-outlined">group</span>
</a>
<!-- Twitter/X Mock -->
<a class="h-12 w-12 flex items-center justify-center rounded-full bg-surface-light dark:bg-surface-dark border border-border-light dark:border-border-dark hover:scale-110 hover:border-primary hover:text-primary transition-all shadow-sm" href="#">
<span class="material-symbols-outlined">alternate_email</span>
</a>
<!-- GitHub Mock -->
<a class="h-12 w-12 flex items-center justify-center rounded-full bg-surface-light dark:bg-surface-dark border border-border-light dark:border-border-dark hover:scale-110 hover:border-primary hover:text-primary transition-all shadow-sm" href="#">
<span class="material-symbols-outlined">code</span>
</a>
</div>
<p class="text-sm text-text-muted dark:text-text-muted-dark">
                        © 2023 AlexDev. All rights reserved.
                    </p>
</footer>
</div>
</main>
</div>
</div>
<script>
    // Simple script to toggle mock theme for preview if needed, though Tailwind handles 'class' strategy
    // In a real app this would be a button toggle
</script>
</body></html>
