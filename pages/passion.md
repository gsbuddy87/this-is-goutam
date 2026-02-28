---
layout: default
title: Passion
permalink: /passion/
---

<section class="work-intro">
    <div class="container">
        <h1>My Passions</h1>
        <p style="font-size: 1.5rem; margin-top: 0.5rem;">
            Beyond codes and architecture, these are the stories and experiences that fuel my creativity.
        </p>
    </div>
</section>

<div class="container">
    <div class="divider" style="margin: 1rem 0;"></div>

    <div style="max-width: 900px; line-height: 1.8; margin-top: 2rem;">
        
        <p style="font-size: 1.1rem; margin-bottom: 3rem;">
            I believe that creativity isn't confined to a single domain. Whether it's the structured logic of a software system or the emotional depth of a cinematic frame, the core essence remains the same—storytelling and problem-solving. Here’s a glimpse into the worlds I explore when I’m not at my desk.
        </p>

        <!-- Passion Grid/List -->
        <div style="display: grid; gap: 4rem;">

            <!-- Filmmaking -->
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center;">
                <div>
                    <h2 style="margin-top: 0; color: #2c5282;">Filmmaking</h2>
                    <p>
                        Cinema is my greatest canvas. From zero-budget short films to dreaming of large-scale narratives, I explore human emotions and social reflections through the lens. My journey has taken me from the local streets of Kolkata to screenings at the Kolkata Film Festival.
                    </p>
                    <a href="{{ '/films/' | relative_url }}" class="btn-explore" style="display: inline-block; margin-top: 1rem;">What to Know More ? &rarr;</a>
                </div>
                <div style="aspect-ratio: 16/9; background: #000; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1);">
                    <iframe width="100%" height="100%" src="https://www.youtube.com/embed/pycYmOXbQtI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>
            </div>

            <!-- Photography -->
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center;">
                <div style="order: 2;">
                    <h2 style="margin-top: 0; color: #2c5282;">Photography</h2>
                    <p>
                        Photography is about capturing the "quiet moments" in a chaotic world. I love exploring perspectives through my camera—whether it's street photography, portraits, or landscapes, each frame tells a story that words often miss.
                    </p>
                    <a href="{{ '/photography/' | relative_url }}" class="btn-explore" style="display: inline-block; margin-top: 1rem;">View Gallery &rarr;</a>
                </div>
                <div style="aspect-ratio: 16/9; background: #f1f5f9; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1); order: 1;">
                    <img src="{{ '/assets/img/photography_preview.png' | relative_url }}" alt="Photography Preview" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>

            <!-- Travelling -->
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center;">
                <div>
                    <h2 style="margin-top: 0; color: #2c5282;">Travelling</h2>
                    <p>
                        Exploring new horizons across India and abroad keeps my curiosity alive. Travel isn't just about the destination; it's about the cultures, the people, and the stories encountered along the way that constantly redefine my perspective on life and design.
                    </p>
                    <a href="{{ '/travelling/' | relative_url }}" class="btn-explore" style="display: inline-block; margin-top: 1rem;">Follow My Travels &rarr;</a>
                </div>
                <div style="aspect-ratio: 16/9; background: #f1f5f9; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1);">
                    <img src="{{ '/assets/img/travel_preview.png' | relative_url }}" alt="Travel Preview" style="width: 100%; height: 100%; object-fit: cover;">
                </div>
            </div>

        </div>

        <div class="divider" style="margin-top: 5rem;"></div>
        
        <div style="margin-top: 2rem; margin-bottom: 4rem;">
            <a href="{{ '/' | relative_url }}" style="text-decoration: underline; font-weight: bold;">&larr; Back to Home</a>
        </div>
    </div>
</div>
