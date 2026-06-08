

<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: var(--font-sans); }

.profile-header {
  text-align: center;
  padding: 2.5rem 1.5rem 2rem;
  border-bottom: 0.5px solid var(--color-border-tertiary);
}
.avatar {
  width: 80px; height: 80px; border-radius: 50%;
  background: #534AB7;
  display: flex; align-items: center; justify-content: center;
  font-size: 28px; font-weight: 500; color: #EEEDFE;
  margin: 0 auto 1rem;
}
.profile-name {
  font-size: 22px; font-weight: 500;
  color: var(--color-text-primary);
}
.profile-title {
  font-size: 14px; color: var(--color-text-secondary); margin-top: 4px;
}
.badges {
  display: flex; flex-wrap: wrap; gap: 8px;
  justify-content: center; margin-top: 1rem;
}
.badge {
  font-size: 12px; padding: 4px 12px;
  border-radius: 99px;
  border: 0.5px solid var(--color-border-secondary);
  color: var(--color-text-secondary);
}
.badge.purple { background: #EEEDFE; color: #3C3489; border-color: #AFA9EC; }
.badge.teal   { background: #E1F5EE; color: #085041; border-color: #5DCAA5; }
.badge.amber  { background: #FAEEDA; color: #633806; border-color: #EF9F27; }
.badge.coral  { background: #FAECE7; color: #712B13; border-color: #F0997B; }
.badge.green  { background: #EAF3DE; color: #27500A; border-color: #97C459; }

.section { padding: 1.5rem; border-bottom: 0.5px solid var(--color-border-tertiary); }
.section-title {
  font-size: 13px; font-weight: 500; letter-spacing: 0.06em;
  text-transform: uppercase; color: var(--color-text-tertiary);
  margin-bottom: 1rem;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
  gap: 8px;
}
.skill-chip {
  background: var(--color-background-secondary);
  border-radius: var(--border-radius-md);
  padding: 8px 6px;
  text-align: center;
  font-size: 12px; color: var(--color-text-secondary);
  border: 0.5px solid var(--color-border-tertiary);
}
.skill-chip i { display: block; font-size: 20px; margin-bottom: 4px; color: var(--color-text-primary); }

.ecom-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 10px;
}
.ecom-card {
  border-radius: var(--border-radius-lg);
  border: 0.5px solid var(--color-border-tertiary);
  padding: 1rem;
  background: var(--color-background-primary);
}
.ecom-card-header {
  display: flex; align-items: center; gap: 8px; margin-bottom: 10px;
}
.ecom-dot {
  width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0;
}
.ecom-name { font-size: 14px; font-weight: 500; color: var(--color-text-primary); }
.ecom-skills { list-style: none; }
.ecom-skills li {
  font-size: 12px; color: var(--color-text-secondary);
  padding: 3px 0;
  border-bottom: 0.5px solid var(--color-border-tertiary);
  display: flex; align-items: center; gap: 6px;
}
.ecom-skills li:last-child { border-bottom: none; }
.ecom-skills li i { font-size: 13px; }

.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 10px;
}
.project-card {
  border-radius: var(--border-radius-lg);
  border: 0.5px solid var(--color-border-tertiary);
  background: var(--color-background-primary);
  padding: 1rem;
}
.project-title { font-size: 14px; font-weight: 500; color: var(--color-text-primary); margin-bottom: 4px; }
.project-desc { font-size: 12px; color: var(--color-text-secondary); margin-bottom: 10px; line-height: 1.5; }
.project-tags { display: flex; flex-wrap: wrap; gap: 4px; margin-bottom: 10px; }
.tag {
  font-size: 11px; padding: 2px 8px;
  border-radius: 99px;
  background: var(--color-background-secondary);
  color: var(--color-text-secondary);
  border: 0.5px solid var(--color-border-tertiary);
}
.project-links { display: flex; gap: 8px; }
.project-links a {
  font-size: 12px; color: var(--color-text-info);
  text-decoration: none;
  display: flex; align-items: center; gap: 3px;
}

.stats-row {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 8px;
}
.stat-card {
  background: var(--color-background-secondary);
  border-radius: var(--border-radius-md);
  padding: 12px;
  text-align: center;
}
.stat-num { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
.stat-label { font-size: 11px; color: var(--color-text-tertiary); margin-top: 2px; }

.contact-row {
  display: flex; gap: 8px; flex-wrap: wrap; padding: 1.5rem;
  justify-content: center;
}
.contact-btn {
  display: flex; align-items: center; gap: 6px;
  padding: 8px 16px;
  border-radius: var(--border-radius-md);
  border: 0.5px solid var(--color-border-secondary);
  font-size: 13px; font-weight: 500;
  color: var(--color-text-primary);
  background: var(--color-background-primary);
  cursor: pointer; text-decoration: none;
}
.contact-btn i { font-size: 16px; }
</style>

<h2 class="sr-only">GitHub profile preview for Mostafa Mosad Al-Tonbary, front-end developer</h2>

<div style="border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); overflow: hidden; background: var(--color-background-primary);">

  <div class="profile-header">
    <div class="avatar">MM</div>
    <div class="profile-name">Mostafa Mosad Al-Tonbary</div>
    <div class="profile-title">Front-End Developer &nbsp;·&nbsp; Egypt</div>
    <div class="badges" style="margin-top: 12px;">
      <span class="badge purple"><i class="ti ti-brand-react" aria-hidden="true"></i> React</span>
      <span class="badge purple">Next.js</span>
      <span class="badge purple">TypeScript</span>
      <span class="badge green">Shopify</span>
      <span class="badge amber">Salla</span>
      <span class="badge coral">Zid</span>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Tech stack</div>
    <div class="skills-grid">
      <div class="skill-chip"><i class="ti ti-brand-react" aria-hidden="true"></i>React</div>
      <div class="skill-chip"><i class="ti ti-brand-typescript" aria-hidden="true"></i>TypeScript</div>
      <div class="skill-chip"><i class="ti ti-brand-javascript" aria-hidden="true"></i>JavaScript</div>
      <div class="skill-chip"><i class="ti ti-brand-nextjs" aria-hidden="true"></i>Next.js</div>
      <div class="skill-chip"><i class="ti ti-brand-tailwind" aria-hidden="true"></i>Tailwind</div>
      <div class="skill-chip"><i class="ti ti-brand-sass" aria-hidden="true"></i>Sass</div>
      <div class="skill-chip"><i class="ti ti-versions" aria-hidden="true"></i>Redux</div>
      <div class="skill-chip"><i class="ti ti-brand-git" aria-hidden="true"></i>Git</div>
      <div class="skill-chip"><i class="ti ti-brand-vite" aria-hidden="true"></i>Vite</div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">E-commerce platforms</div>
    <div class="ecom-grid">
      <div class="ecom-card">
        <div class="ecom-card-header">
          <div class="ecom-dot" style="background: #96BF48;"></div>
          <span class="ecom-name">Shopify</span>
        </div>
        <ul class="ecom-skills">
          <li><i class="ti ti-template" aria-hidden="true"></i>Theme dev</li>
          <li><i class="ti ti-code" aria-hidden="true"></i>Liquid</li>
          <li><i class="ti ti-plug" aria-hidden="true"></i>Storefront API</li>
          <li><i class="ti ti-layout-grid" aria-hidden="true"></i>Sections & blocks</li>
        </ul>
      </div>
      <div class="ecom-card">
        <div class="ecom-card-header">
          <div class="ecom-dot" style="background: #FF6B35;"></div>
          <span class="ecom-name">Salla</span>
        </div>
        <ul class="ecom-skills">
          <li><i class="ti ti-template" aria-hidden="true"></i>Custom themes</li>
          <li><i class="ti ti-terminal" aria-hidden="true"></i>Salla CLI</li>
          <li><i class="ti ti-code" aria-hidden="true"></i>Twig</li>
          <li><i class="ti ti-webhook" aria-hidden="true"></i>Webhooks & APIs</li>
        </ul>
      </div>
      <div class="ecom-card">
        <div class="ecom-card-header">
          <div class="ecom-dot" style="background: #5B2D8E;"></div>
          <span class="ecom-name">Zid</span>
        </div>
        <ul class="ecom-skills">
          <li><i class="ti ti-template" aria-hidden="true"></i>Theme custom</li>
          <li><i class="ti ti-plug" aria-hidden="true"></i>REST API</li>
          <li><i class="ti ti-layout-grid" aria-hidden="true"></i>Custom widgets</li>
          <li><i class="ti ti-language" aria-hidden="true"></i>Arabic market</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-title">Featured projects</div>
    <div class="projects-grid">
      <div class="project-card">
        <div class="project-title">Modern web app</div>
        <div class="project-desc">Full-featured application with beautiful UI and clean architecture</div>
        <div class="project-tags">
          <span class="tag">React</span><span class="tag">Next.js</span><span class="tag">Tailwind</span>
        </div>
        <div class="project-links">
          <a href="#"><i class="ti ti-external-link" aria-hidden="true"></i> Demo</a>
          <a href="#"><i class="ti ti-brand-github" aria-hidden="true"></i> Code</a>
        </div>
      </div>
      <div class="project-card">
        <div class="project-title">Shopify custom theme</div>
        <div class="project-desc">High-converting storefront with custom sections and mobile-first design</div>
        <div class="project-tags">
          <span class="tag">Shopify</span><span class="tag">Liquid</span><span class="tag">JS</span>
        </div>
        <div class="project-links">
          <a href="#"><i class="ti ti-external-link" aria-hidden="true"></i> Demo</a>
          <a href="#"><i class="ti ti-brand-github" aria-hidden="true"></i> Code</a>
        </div>
      </div>
      <div class="project-card">
        <div class="project-title">Salla store theme</div>
        <div class="project-desc">Arabic-first e-commerce experience with full RTL support</div>
        <div class="project-tags">
          <span class="tag">Salla</span><span class="tag">Twig</span><span class="tag">Tailwind</span>
        </div>
        <div class="project-links">
          <a href="#"><i class="ti ti-external-link" aria-hidden="true"></i> Demo</a>
          <a href="#"><i class="ti ti-brand-github" aria-hidden="true"></i> Code</a>
        </div>
      </div>
      <div class="project-card">
        <div class="project-title">Analytics dashboard</div>
        <div class="project-desc">Data visualization platform with real-time charts and export</div>
        <div class="project-tags">
          <span class="tag">React</span><span class="tag">Chart.js</span><span class="tag">Redux</span>
        </div>
        <div class="project-links">
          <a href="#"><i class="ti ti-external-link" aria-hidden="true"></i> Demo</a>
          <a href="#"><i class="ti ti-brand-github" aria-hidden="true"></i> Code</a>
        </div>
      </div>
    </div>
  </div>

  <div class="section" style="border-bottom: none;">
    <div class="section-title">GitHub stats</div>
    <div class="stats-row">
      <div class="stat-card">
        <div class="stat-num">42+</div>
        <div class="stat-label">Repos</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">3</div>
        <div class="stat-label">Platforms</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">9</div>
        <div class="stat-label">Technologies</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">100%</div>
        <div class="stat-label">Passion</div>
      </div>
    </div>
  </div>

  <div class="contact-row" style="border-top: 0.5px solid var(--color-border-tertiary);">
    <a href="mailto:melfeshawy42@gmail.com" class="contact-btn"><i class="ti ti-mail" aria-hidden="true"></i> Email</a>
    <a href="#" class="contact-btn"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn</a>
    <a href="#" class="contact-btn"><i class="ti ti-world" aria-hidden="true"></i> Portfolio</a>
  </div>

</div>
