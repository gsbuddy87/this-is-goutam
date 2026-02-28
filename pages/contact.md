---
layout: default
title: Contact
permalink: /contact/
---

<section class="work-intro">
    <div class="container">
        <h1>Get in Touch</h1>
        <p style="font-size: 1.5rem; margin-top: 0.5rem;">
            Architecture queries, collaboration, or just a friendly hello.
        </p>
    </div>
</section>

<div class="container" style="max-width: 800px; padding-bottom: 4rem;">
    <div class="divider" style="margin: 1rem 0 3rem 0;"></div>

    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; align-items: start;">
        
        <!-- Socials -->
        <div style="background: #f9fafb; padding: 2rem; border-radius: 12px;">
            <h3 style="margin-bottom: 1.5rem; color: #330066;">Connect</h3>
            <div style="display: flex; flex-direction: column; gap: 1rem;">
                <a href="https://x.com/GoutamSett" target="_blank" class="contact-link">
                    <span style="font-weight: 600;">X (Twitter)</span>
                    <span style="opacity: 0.6;">&nearr;</span>
                </a>
                <a href="https://www.linkedin.com/in/goutam-sett" target="_blank" class="contact-link">
                    <span style="font-weight: 600;">LinkedIn</span>
                    <span style="opacity: 0.6;">&nearr;</span>
                </a>
            </div>
        </div>

        <!-- Email Request UI -->
        <div style="background: #fff; padding: 2rem; border-radius: 12px; border: 1px solid #eee; box-shadow: 0 4px 12px rgba(0,0,0,0.03);">
            <h3 style="margin-bottom: 0.5rem; color: #330066;">Email Access</h3>
            <p style="font-size: 0.9rem; color: #666; margin-bottom: 1.5rem;">
                I keep my inbox spam-free. Please enter your email to request direct contact details.
            </p>
            
            <form id="email-request-form" onsubmit="handleEmailRequest(event)" style="display: flex; flex-direction: column; gap: 1rem;">
                <input type="email" placeholder="name@company.com" required 
                       style="padding: 0.8rem; border: 1px solid #ddd; border-radius: 6px; font-family: var(--font-sans); font-size: 1rem;">
                <button type="submit" class="btn-explore" style="width: 100%; text-align: center; cursor: pointer; background: #2563eb; color: white; border: none;">
                    Request Email ID
                </button>
            </form>
            
            <div id="request-success" style="display: none; margin-top: 1rem; color: #059669; font-weight: 500; font-size: 0.9rem;">
                &check; Request sent. If you are not a bot, I'll reach out!
            </div>
        </div>
    </div>
</div>

<style>
    .contact-link {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem;
        background: white;
        border: 1px solid #eee;
        border-radius: 8px;
        text-decoration: none;
        color: #333;
        transition: all 0.2s ease;
    }
    .contact-link:hover {
        border-color: #2563eb;
        color: #2563eb;
        transform: translateY(-2px);
        box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    }
    @media (max-width: 768px) {
        div[style*="grid-template-columns"] {
            grid-template-columns: 1fr !important;
        }
    }
</style>

<script>
    function handleEmailRequest(e) {
        e.preventDefault();
        // Mock functionality as requested - strictly UI
        var form = document.getElementById('email-request-form');
        var successMsg = document.getElementById('request-success');
        
        form.style.opacity = '0.5';
        form.style.pointerEvents = 'none';
        successMsg.style.display = 'block';
    }
</script>
