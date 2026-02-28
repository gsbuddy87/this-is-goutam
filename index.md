---
layout: default
title: Home
---

<!-- Intro Section -->
<!-- Intro Section -->
<section class="intro-section">
    <div class="container">
        <!-- Initial Greeting -->
        <div class="intro-greeting" style="text-align: center; width: 100%;">
            <p class="intro-text-schoolbell" style="font-size: 3rem; margin-bottom: 2rem;">
                Hi there, and thanks for stopping by!
            </p>
            <button onclick="toggleIntro()" id="who-am-i-btn" class="btn-explore" style="background: transparent; cursor: pointer; font-size: 1.1rem; padding: 0; border: none; color: #2563eb; display: inline-block;">
                Who am I? &darr;
            </button>
        </div>

        <!-- Hidden Details -->
        <div id="intro-details" style="display: none; animation: fadeIn 0.5s ease-in-out;">
            <p class="intro-text">
                I’m a <strong>software architect with 16+ years of experience</strong> designing innovative solutions that merge technology with creativity. My expertise spans end‑to‑end architecture design, from <strong>conceptualization to deployment</strong>, with a strong focus on <strong>problem‑solving</strong> and <strong>building resilient systems</strong>. Over the years, I’ve worked across diverse domains including banking, retail, insurance, and rail, where I’ve delivered solutions that balance technical precision with business impact. Recently, my work has expanded into the cutting‑edge area of <strong>Generative AI</strong>, particularly <strong>Retrieval‑Augmented Generation (RAG)</strong>, where I’m exploring how AI can transform enterprise knowledge systems and unlock new possibilities for intelligent applications.
            </p>
            <p class="intro-text" style="margin-top: 2rem;">
                Beyond the world of code, I’m a <strong>passionate traveler</strong> who has explored diverse destinations across India and abroad, often with a camera in hand. <strong>Photography, film-making, and movies</strong> fuel my creativity and curiosity, inspiring me to see the world through both technical and artistic lenses. I also love <strong>writing</strong> about my <strong>movie experiences</strong>—whether as a blog post or a quick reflection on Facebook—because sharing stories helps me connect with others who see cinema as more than entertainment. This site is where my professional expertise meets my personal passions—welcome to my world!
            </p>
            <p class="intro-text" style="margin-top: 2rem;">
                This site is where my professional expertise meets my personal passions—<strong>welcome to my world!</strong>
            </p>
            <div style="margin-top: 2rem; background-color: #eff6ff; padding: 1.5rem; border-radius: 8px; font-family: var(--font-sans); color: #1e3a8a;">
                <p style="margin: 0; font-size: 1.05rem;">
                    I’ve written a short note on how I think about design, systems, and why clarity matters more than scale.
                </p>
                <a href="{{ '/manifesto-full/' | relative_url }}" style="color: #2563eb; font-weight: 600; text-decoration: underline; text-underline-offset: 4px; display: inline-block; margin-top: 0.5rem;">Read the Manifesto &rarr;</a>
            </div>
        </div>
    </div>
    
    <script>
        function toggleIntro() {
            var details = document.getElementById('intro-details');
            var mainContent = document.getElementById('main-content');
            var btn = document.getElementById('who-am-i-btn');
            if (details.style.display === 'none') {
                details.style.display = 'block';
                if (mainContent) mainContent.style.display = 'block';
                btn.style.display = 'none'; // Hide button after clicking
            }
        }
    </script>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</section>

<!-- Content hidden initially -->
<div id="main-content" style="display: none; animation: fadeIn 1s ease-in-out;">

<div class="container">
    <div class="divider"></div>
</div>

<!-- Projects List -->
<section id="work">
    <div class="container">
        <div class="project-list">
            
            <!-- Item 1: Software -->
            <div class="project-item">
                <div class="project-content">
                    <span class="category-label">Development</span>
                    <h3 class="project-title">Scalable Architecture and Systems</h3>
                    <p>Designing maintainable backends and refactoring legacy systems to ensure clarity and future-proofing.</p>
                    <a href="{{ '/technical-blogs/' | relative_url }}" class="btn-explore">Explore Blogs</a>
                </div>
                <div class="project-image">
                    <img src="{{ '/assets/img/work.jpg' | relative_url }}" alt="Scalable Architecture" loading="lazy">
                </div>
            </div>

            <!-- Item 2: Passion (Merged) -->
            <div class="project-item" id="passion">
                <div class="project-content">
                    <span class="category-label">Passion</span>
                    <h3 class="project-title">Visual Storytelling</h3>
                    <p>Filmmaking and Photography. Exploring perspectives through the lens, from short films to portraiture.</p>
                    <a href="{{ '/passion/' | relative_url }}" class="btn-explore">Explore Passion</a>
                </div>
                <div class="project-image">
                    <img src="{{ '/assets/img/passion.png' | relative_url }}" alt="Photography and Film" loading="lazy">
                </div>
            </div>

             <!-- Item 3: Manifesto -->
             <div class="project-item" id="manifesto">
                <div class="project-content">
                    <span class="category-label">Philosophy</span>
                    <h3 class="project-title">The Manifesto</h3>
                    <p>A short note on how I think about design, systems, and creative work. Why clarity matters more than scale.</p>
                    <a href="{{ '/manifesto-full/' | relative_url }}" class="btn-explore">Read More</a>
                </div>
                <div class="project-image">
                    <img src="{{ '/assets/img/manifesto.png' | relative_url }}" alt="Photography and Film" loading="lazy">
                </div>
            </div>

</div> <!-- End main-content -->
