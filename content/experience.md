---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
# sections:
#  - block: resume-experience
#    content:
#      username: admin
#    design:
#      # Hugo date format
#      date_format: 'January 2006'
#      # Education or Experience section first?
#      is_education_first: false
#  - block: resume-skills
#    content:
#      title: Skills & Hobbies
#      username: admin
#    design:
#      show_skill_percentage: false
#  - block: resume-awards
#    content:
#      title: Awards
#      username: admin
#  - block: resume-languages
#    content:
#      title: Languages
#      username: admin
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experience | Hugo Academic CV Theme</title>

    <!-- Stylesheets -->
    <link rel="stylesheet" href="emerald.min.css">
    <link rel="stylesheet" href="wc.min.css">
    <link rel="stylesheet" href="pagefind-ui.be766eb419317a14ec769d216e9779bfe8f3737c80e780f4ba0dafb57a41a482.css">

    <!-- Scripts -->
    <script src="pagefind-ui.87693d7c6f2b3b347ce359d0ede762c033419f0a32b22ce508c335a81d841f1b.js" defer></script>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            console.log("Page loaded successfully");
        });
    </script>
</head>
<body class="dark:bg-hb-dark dark:text-white page-wrapper" id="top">
    <header class="page-header sticky top-0 z-30">
        <nav class="navbar px-3 flex justify-left">
            <div class="order-0 h-100">
                <a class="navbar-brand" href="/" title="Hugo Academic CV Theme">Your Name</a>
            </div>
            <ul class="navbar-nav order-3 hidden lg:flex w-full pb-6 lg:order-1 lg:w-auto lg:space-x-2 lg:pb-0 xl:space-x-8 justify-left">
                <li class="nav-item"><a class="nav-link" href="/">Bio</a></li>
                <li class="nav-item"><a class="nav-link" href="#papers">Papers</a></li>
                <li class="nav-item"><a class="nav-link" href="#talks">Talks</a></li>
                <li class="nav-item"><a class="nav-link" href="#news">News</a></li>
                <li class="nav-item"><a class="nav-link active" href="/experience/">Experience</a></li>
            </ul>
        </nav>
    </header>

    <main class="page-body">
        <section id="section-resume-experience" class="relative hbb-section blox-resume-experience" style="padding: 5rem 0;">
            <div class="home-section-bg"></div>
            <div class="flex flex-col items-center max-w-prose mx-auto">
                <h3 class="mb-6 text-3xl font-bold text-gray-900 dark:text-white">Experience</h3>
                <ol class="relative border-s border-gray-200 dark:border-gray-700">
                    <li class="mb-10 ms-6">
                        <span class="absolute flex items-center justify-center w-6 h-6 bg-primary-100 rounded-full -start-3 ring-8 ring-white dark:ring-gray-900 dark:bg-primary-900"></span>
                        <h3 class="flex items-center mb-1 text-lg font-semibold text-gray-900 dark:text-white">Director of Cloud Infrastructure</h3>
                        <span class="block mb-2 text-sm font-normal text-gray-500 dark:text-gray-300">GenCoin</span>
                        <time class="block mb-3 text-sm font-normal text-gray-500 dark:text-gray-300">January 2021 – Present</time>
                        <div class="text-base font-normal text-gray-500 dark:text-gray-300 prose prose-slate dark:prose-invert">
                            <p>Responsibilities include:</p>
                            <ul>
                                <li>Lorem ipsum dolor sit amet.</li>
                                <li>Consectetur adipiscing elit.</li>
                                <li>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</li>
                            </ul>
                        </div>
                    </li>
                </ol>
            </div>
        </section>
    </main>
</body>
</html>