---
layout: article
title: Full-stack Engineer
lightbox: true
show_title: false
aside:
  toc: true
---

<style>
  h1, h2, h3 {
    clear: both;
  }

  h4 {  
    padding-left: 10px;
    border-left: 2px solid transparent;
    border-image: linear-gradient(to bottom, transparent, #ff9500) 1;
  }

  .article__content h2 {
    border-image: linear-gradient(to right, #444444 80%, transparent) 1;
  }

  .crm-grid, .tour-grid, .lib-grid {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 1.5rem;
  }

  .crm-grid *, .tour-grid *, .lib-grid * {
    height: 100%;
    width: 100%;
  }

  .crm-grid > *:first-child {
    grid-column: span 6;
  }

  .crm-grid > *:nth-child(2) {
    grid-column: span 4;
  }

  .crm-grid > *:where(:nth-child(3), :nth-child(4), :nth-child(5), :nth-child(6)) {
    grid-column: span 2;
  }

  .tour-grid > *:first-child {
    grid-column: span 6;
  }

  .tour-grid > *:nth-child(n+2) {
    grid-column: span 3;
  }

  .lib-grid > *:first-child {
    display: block;
    grid-column: span 6;
  }

  .lib-grid > *:nth-child(2) {
    grid-column: span 4;
  }

  .lib-grid > *:nth-child(3) {
    grid-column: span 2;
  }

  @media (max-width: 768px) {
    .crm-grid > *:where(:nth-child(4), :nth-child(5)) {
      grid-column: span 3;
    }

    .crm-grid > *:where(:nth-child(6)) {
      grid-column: span 6;
    }

    .tour-grid > * {
      grid-column: span 6 !important;
    }
  }

  @media (max-width: 576px) {
    .crm-grid > * {
      grid-column: span 6 !important;
    }

    .lib-grid > * {
      grid-column: span 6 !important;
    }
  }

.tech-stack {
    display: inline-flex;
    gap: 1.5rem;
    align-items: center;
    margin-bottom: 2rem;
    background-clip: border-box;
    border-radius: 0px 8px 0px 8px;
    background-image: linear-gradient(to top right, #ff950033, transparent 57%);
    border-left: 2px solid #ff9500;
    border-bottom: 2px solid #ff9500;
    padding: 0.5rem 0.8rem;
}

  .tech-stack img {
    height: 1.25rem;
  }

  .article__content a.external-link::after {
    content: " ↗";
  }

  .tech-square {
    display: flex;
    flex-direction: column;
    align-items: center;
    row-gap: .75rem;
    width: 150px;
    flex-shrink: 0;
  }

  .tech-icon {
    max-width: 100%;
    position: relative;
    border-radius: 8px;
    padding: 2rem;
    background-image: radial-gradient(circle at top left, #ff950033 5%, transparent 20%), radial-gradient(circle at bottom right, #ff950033 5%, transparent 20%);
    min-width: 100%;
    min-height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .tech-icon img {
    max-height: 100%;
  }

  .tech-icon::before {
    content: '';
    position: absolute;
    inset: 0;
    padding: 2px;
    border-radius: 8px;
    background: linear-gradient(to bottom right, #ffa824, #ff9500 5%, transparent 25%, transparent 75%, #ff9500 95%, #ffa824);
    -webkit-mask: 
    linear-gradient(#fff 0 0) content-box, 
    linear-gradient(#fff 0 0);
    -webkit-mask-composite: xor;
    mask-composite: exclude;
  }

  .tech-caption {
    text-align: center;
  }

  .tech-array {
    display: flex;
    row-gap: 2.5rem;
    column-gap: 3rem;
    justify-content: center;
    flex-wrap: wrap;
  }

  .project-header {
    display: flex;
    align-items: center;
    margin-top: 40px;
  }

  .project-header h4 {
    margin-right: auto;
  }

  .view-code-button {
    display: flex;
    align-items: center;
    column-gap: 7px;
    padding-block: 5px;
    padding-inline: 10px;
    border-radius: 5px;
    border: 2px solid rgba(255, 255, 255, 0.8);
    color: rgba(255, 255, 255, 0.8) !important;
    background-color: transparent;
    text-decoration: none !important;
    transform: translateY(75%);
  }

  .view-code-button:hover {
    color: #ff9500 !important;
    border-color: #ff9500;
  }

  .view-code-button path {
    fill: rgba(255, 255, 255, 0.8);
    transition: all 0.2s ease-in-out;
  }

  .view-code-button:hover path {
    fill: #ff9500;
  }

  .quote {
    position: relative;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .quote p {
    font-size: 1.2rem;
    font-weight: 100;
    font-style: italic;
  }

  .quote p::before {
    content: "\201D";
  }

  .quote p::after {
    content: "\201D";
  }

  .quote span {
    display: block;
    text-align: right;
  }

  .quote span::before {
    content: '— ';
  }

  .reference {
    display: flex;
    gap: 1rem;
  }

  .reference-body {
     display: flex;
     flex-direction: column;
  }

  .reference-name {
     font-weight: bold;
     font-size: 1.5rem;
  }

  .reference-title {
     font-weight: 300;
     margin-top: -3px;
  }
</style>

## About me

<p style="font-size: 20px; font-weight: 300; line-height: 1.5;">Full-stack engineer with over 3 years of professional experience delivering reliable, robust, and scalable web applications. High work standards, meticulous attention to detail, and a strong drive for learning and improvement. Dependable and collaborative team member with solid interpersonal skills and an openness to discussion and feedback.</p>

## Skills & tools

### Languages

<div class="tech-array">
  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/python-snakes-only.png" alt="Python programming language" />
    </div>
    <div class="tech-caption">
      <span>Python</span>
    </div>
  </div>


  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/php.png" alt="PHP Hypertext Preprocessing" />
    </div>
    <div class="tech-caption">
      <span>PHP</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/javascript.png" alt="JavaScript / TypeScript" />
    </div>
    <div class="tech-caption">
      <span>JavaScript</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/typescript.png" alt="TypeScript" />
    </div>
    <div class="tech-caption">
      <span>TypeScript</span>
    </div>
  </div>
</div>

### Frameworks

<div class="tech-array">
  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/symfony_sf.png" alt="Symfony framework" />
    </div>
    <div class="tech-caption">
      <span>Symfony</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/django.png" alt="Django framework" />
    </div>
    <div class="tech-caption">
      <span>Django</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/vue.png" alt="Vue.js framework" />
    </div>
    <div class="tech-caption">
      <span>Vue.js</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/nextjs_long.png" alt="Next.js framework" />
    </div>
    <div class="tech-caption">
      <span>Next.js</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/bootstrap.png" alt="Bootstrap css framework" />
    </div>
    <div class="tech-caption">
      <span>Bootstrap</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/tailwindcss.png" alt="Tailwindcss framework" />
    </div>
    <div class="tech-caption">
      <span>Tailwindcss</span>
    </div>
  </div>
</div>

### Databases

<div class="tech-array">
  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/mysql.png" alt="MySQL" />
    </div>
    <div class="tech-caption">
      <span>MySQL</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/sql_server_white.png" alt="Microsoft SQL Server" />
    </div>
    <div class="tech-caption">
      <span>Microsoft SQL Server</span>
    </div>
  </div>
</div>

### Tools

<div class="tech-array">
  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/git.png" alt="Git source code management" />
    </div>
    <div class="tech-caption">
      <span>Git</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/github.png" alt="GitHub platform" />
    </div>
    <div class="tech-caption">
      <span>GitHub</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/ansible.png" alt="Ansible" />
    </div>
    <div class="tech-caption">
      <span>Ansible</span>
    </div>
  </div>

  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/docker.png" alt="Docker" />
    </div>
    <div class="tech-caption">
      <span>Docker</span>
    </div>
  </div>

</div>

### Platforms

<div class="tech-array">
  <div class="tech-square">
    <div class="tech-icon">
      <img src="assets/images/logo/azure.png" alt="Microsoft Azure" />
    </div>
    <div class="tech-caption">
      <span>Microsoft Azure</span>
    </div>
  </div>
</div>

## Featured work

### Professional projects

#### Customer Relationship Management application

<div class="tech-stack">
  <img src="assets/images/logo/php.png"  />
  <img src="assets/images/logo/symfony.png" />
  <img src="assets/images/logo/javascript.png" />
  <img src="assets/images/logo/bootstrap.png" />
</div>

<div class="crm-grid">
  <picture class="rounded border">
    <source srcset="assets/images/order.webp" type="image/webp" />
    <img src="assets/images/order.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/signature.webp" type="image/webp" />
    <img src="assets/images/signature.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/order_mobile.webp" type="image/webp" />
    <img src="assets/images/order_mobile.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/login.webp" type="image/webp" />
    <img src="assets/images/login.png"  draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/calendar.webp" type="image/webp" />
    <img src="assets/images/calendar.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/map.webp" type="image/webp" />
    <img src="assets/images/map.png" draggable="false" />
  </picture>
</div>

Charged with the design, implementation, deployment, and maintenance of a custom <abbr title="Customer Relationship Management">CRM</abbr> application that includes customer data processing, sales appointment scheduling and tracking, as well as order and invoice handling.

Non-exhaustive list of features:
- Online digital signature of customer orders.
- Real-time notification system with <a class="external-link" href="https://mercure.rocks/" target="_blank">Mercure</a>.
- Integration with third-party invoicing service.
- Handles different tax rates for mainland France and oversea territories.
- Automatic generation of multiple types of documents.
- Role-based permission system for users.

#### Tour agency management software
<div class="tech-stack">
  <img src="assets/images/logo/php.png"  />
  <img src="assets/images/logo/symfony.png" />
  <img src="assets/images/logo/nextjs.png" />
  <img src="assets/images/logo/typescript.png" />
  <img src="assets/images/logo/tailwindcss.png" />
</div>

<div class="tour-grid">
  <picture class="rounded border">
    <source srcset="assets/images/landing.webp" type="image/webp" />
    <img src="assets/images/landing.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/excursion_page_1.webp" type="image/webp" />
    <img src="assets/images/excursion_page_1.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/reservation_form.webp" type="image/webp" />
    <img src="assets/images/reservation_form.png" draggable="false" />
  </picture>
</div>

<p>Tour agency management application comprising a public-facing website paired with a back office that allows authenticated users to dynamically modify the site's content and receive reservation requests from visitors through the web form.</p>

### Personal projects

#### Library catalog
<div class="tech-stack">
  <img src="assets/images/logo/php.png"  />
  <!-- <img src="assets/images/logo/symfony.png" /> -->
  <img src="assets/images/logo/api-platform.png" />
  <img src="assets/images/logo/vue.png" />
  <img src="assets/images/logo/typescript.png" />
  <img src="assets/images/logo/tailwindcss.png" />
</div>

<div class="lib-grid">
  <video autoplay muted playsinline preload="metadata" class="rounded border">
    <source src="assets/videos/library_catalog.mp4" type="video/mp4" />
    <source src="assets/videos/library_catalog.webm" type="video/webm" />
  </video>

  <picture class="rounded border">
    <source srcset="assets/images/library_book.webp" type="image/webp" />
    <img src="assets/images/library_book.png" draggable="false" />
  </picture>

  <picture class="rounded border">
    <source srcset="assets/images/library_mobile.webp" type="image/webp" />
    <img src="assets/images/library_mobile.png" draggable="false" />
  </picture>
</div>

<div class="project-header">
  <h4 id="3d-cube">3D cube</h4>
  <a class="view-code-button" href="https://github.com/kerpell/3d-cube" target="_blank">
    <div class="icon">{%- include svg/icon/social/github.svg -%}</div>
    View code
  </a>
</div>

<div class="tech-stack">
  <img src="assets/images/logo/sdl.png" style="height: 1.5rem;" />
  <img src="assets/images/logo/cpp.png" style="height: 2rem;" />
</div>

<video autoplay muted loop playsinline preload="metadata" class="" width="400" style="display: block;">
  <source src="assets/videos/cube.mp4" type="video/mp4" />
  <source src="assets/videos/cube.webm" type="video/webm" />
</video>

<div class="project-header">
  <h4 id="archery-game">Checkers</h4>
</div>

<div class="tech-stack">
  <img src="assets/images/logo/python.png"  />
  <img src="assets/images/logo/pygame.png" />
</div>

<video autoplay muted loop playsinline preload="metadata" class="rounded border" style="display: block; max-width: 100%;">
  <source src="assets/videos/checkers.mp4" type="video/mp4" />
  <source src="assets/videos/checkers.webm" type="video/webm" />
</video>

<div class="project-header">
  <h4 id="archery-game">Archery game</h4>
</div>

<div class="tech-stack">
  <img src="assets/images/logo/python.png"  />
  <img src="assets/images/logo/pygame.png" />
</div>

<video autoplay muted loop playsinline preload="metadata" class="rounded border" style="display: block; max-width: 100%;">
  <source src="assets/videos/archery.webm" type="video/webm" />
  <source src="assets/videos/archery.mp4" type="video/mp4" />
</video>


<div class="project-header">
  <h4 id="sort-algorithms-visualization">Sort algorithms visualization</h4>
  <a class="view-code-button" href="https://github.com/kerpell/sort-visualization" target="_blank">
    <div class="icon">{%- include svg/icon/social/github.svg -%}</div>
    View code
  </a>
</div>

<div class="tech-stack">
  <img src="assets/images/logo/python.png"  />
  <img src="assets/images/logo/pygame.png" />
</div>

<video autoplay muted loop playsinline preload="metadata" class="rounded border" style="display: block; max-width: 100%;">
  <source src="assets/videos/sort.mp4" type="video/mp4" />
  <source src="assets/videos/sort.webm" type="video/webm" />
</video>

<div class="project-header">
  <h4 id="sierpiński-triangle">Sierpiński triangle</h4>
  <a class="view-code-button" href="https://github.com/kerpell/sierpinski-triangle" target="_blank">
    <div class="icon">{%- include svg/icon/social/github.svg -%}</div>
    View code
  </a>
</div>

<div class="tech-stack">
  <img src="assets/images/logo/racket_long.png"  />
</div>

<div style="display: flex; justify-content: center; margin-top: -25px;">
  <video autoplay muted loop playsinline preload="metadata" class="" style="display: block; width: 600px; max-width: 100%;">
    <source src="assets/videos/sierpinski.mp4" type="video/mp4" />
    <source src="assets/videos/sierpinski.webm" type="video/webm" />
  </video>
</div>

## References

<div class="reference">
  <div class="tech-array">
    <div class="tech-square">
      <div class="tech-icon" style="padding: 1.5rem;">
        <img src="assets/images/anass.png" class="rounded" alt="Headshot of Mr. Anass Karabila" />
      </div>
    </div>
  </div>
  <div class="reference-body">
    <div class="reference-name">Anass Karabila</div>
    <small class="reference-title">Information system architect at Sofrecom, subsidiary of Orange Group.</small >
    <div>
      <p>"I had the pleasure of working with Amine on the development of a Symfony/PHP CRM, and I can attest to his reliability, professionalism, and technical skills as a full-stack developer.</p>
      <p>Beyond his complete mastery of PHP, he is a dedicated, reliable, and solution-oriented individual. He quickly grasps requirements, proposes relevant solutions, and works effectively as part of a team.</p>
      <p>I highly recommend him for any project requiring a skilled and committed full-stack developer."</p>
    </div>
    <a class="external-link" href="https://www.linkedin.com/in/anasskarabila/" target="_blank">LinkedIn</a>
  </div>
</div>

## Contact
For all inquiries, you can contact me at this e-mail address: <amine.devl@proton.me>