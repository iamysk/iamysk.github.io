---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.85rem 1.25rem; background: #eff6ff; border: 1px solid #dbeafe; border-radius: 10px; margin-bottom: 1.75rem; color: #1e40af; font-size: 0.9rem; flex-wrap: wrap; gap: 0.75rem;">
    <span>For real-time citation metrics, h-index, and updates, visit my Google Scholar profile.</span>
    <a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener noreferrer" class="pub-btn pub-btn--primary">
      <i class="ai ai-google-scholar"></i> Google Scholar
    </a>
  </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
