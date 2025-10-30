---
title: Home
icon: fas fa-home
order: 1
---

<style>
/* ===== Home Page Styling (Light + Dark Mode) ===== */

.home-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 2rem;
  animation: fadeIn 1.2s ease-in-out;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Profile Photo */
.home-photo {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  border: 3px solid #0078ff;
  animation: fadeIn 1.5s ease-in-out;
}

[data-theme="dark"] .home-photo {
  border: 3px solid #4fc3f7;
}

/* Name */
.home-name {
  font-size: 1.9rem;
  font-weight: 700;
  margin-bottom: 0.3rem;
  animation: fadeIn 1.8s ease-in-out;
}

/* Tagline */
.home-tagline {
  font-size: 1.1rem;
  color: #0078ff;
  margin-bottom: 1rem;
  animation: fadeIn 2s ease-in-out;
}

[data-theme="dark"] .home-tagline {
  color: #4fc3f7;
}

/* About section */
.home-about {
  max-width: 720px;
  font-size: 1.05rem;
  line-height: 1.7;
  color: #333;
  animation: fadeIn 2.2s ease-in-out;
}

[data-theme="dark"] .home-about {
  color: #e0e0e0;
}

/* Resume button */
.resume-btn {
  display: inline-block;
  background: #0078ff;
  color: white;
  padding: 10px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  margin-top: 1.5rem;
  transition: all 0.3s ease;
  animation: fadeIn 2.4s ease-in-out;
}

.resume-btn:hover {
  background: #005fcc;
  transform: scale(1.05);
}

</style>

<div class="home-container">

<img src="/assets/jobprofile.png" alt="Profile photo" class="home-photo">

<div class="home-name">Job Ochieng</div>

<div class="home-tagline">Engineer • Ethical Hacker • Innovator</div>

<div class="home-about">
I’m passionate about building, breaking, and rebuilding technology to make it smarter, safer, and more sustainable.  
My work sits at the intersection of <strong>engineering, cybersecurity, and artificial intelligence</strong> — where logic meets creativity and data fuels innovation.  

I believe that great technology isn’t just about efficiency; it’s about <strong>impact</strong> — how it transforms communities, empowers people, and drives change.  
Whether I’m designing systems, securing networks, or exploring the future of AI-driven infrastructure, I’m always asking one question:  
<strong>“How can this make the world better?”</strong>

Here, you’ll find a collection of my projects, challenges, and experiments — each one a reflection of curiosity, resilience, and purpose.
</div>

<a href="/tabs/resume/" class="resume-btn">View My Resume</a>

</div>

<!-- ===== Recent Blog Posts Section ===== -->
<div class="recent-posts">
  <h2>📰 Recent Blog Posts</h2>
  <div class="post-list">
    {% for post in site.posts limit:3 %}
    <div class="post-item">
      <a href="{{ post.url }}">
        <div class="post-title">{{ post.title }}</div>
        <div class="post-date">{{ post.date | date: "%B %d, %Y" }}</div>
        <p>{{ post.excerpt | strip_html | truncate: 100 }}</p>
      </a>
    </div>
    {% endfor %}
  </div>
</div>

