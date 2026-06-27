---
layout: page
title: '"Taking Stock at FAccT"'
nav_title: Home
permalink: /
description: Using Participatory Design to Co-Create a Vision for the Fairness, Accountability and Transparency Community
_styles: |
  .project-hero {
    margin-top: 1.25rem;
  }

  .project-hero img {
    width: 100%;
    border-radius: 8px;
    border: 1px solid var(--global-divider-color);
    display: block;
  }

  .project-resource-buttons {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.85rem;
    margin: 1.5rem 0 1.75rem;
  }

  .project-resource-button {
    align-items: center;
    background: var(--global-theme-color);
    border: 1px solid var(--global-theme-color);
    border-radius: 8px;
    color: var(--global-bg-color);
    display: flex;
    font-size: 1.1rem;
    font-weight: 700;
    justify-content: center;
    min-height: 4.25rem;
    padding: 0.9rem 1rem;
    text-align: center;
  }

  .project-resource-button:hover {
    color: var(--global-bg-color);
    filter: brightness(0.92);
    text-decoration: none;
  }

  .project-resource-button.disabled {
    background: transparent;
    color: var(--global-text-color-light);
    cursor: default;
    filter: none;
  }

  .project-abstract {
    font-size: 1.05rem;
    line-height: 1.7;
  }

  @media (max-width: 575px) {
    .project-resource-buttons {
      grid-template-columns: 1fr;
    }
  }
---

<div class="project-hero">
  <img src="{{ '/assets/img/taking-stock-hero.png' | relative_url }}" alt="Illustration of participatory design discussion, online voting, and report synthesis">
</div>

<div class="project-resource-buttons" aria-label="Project resources">
  <a class="project-resource-button" href="https://dl.acm.org/doi/10.1145/3805689.3812270">Paper</a>
  <a class="project-resource-button" href="https://github.com/facct25pd/taking_stock_at_facct">Code</a>
  <span class="project-resource-button disabled" aria-disabled="true" title="Report PDF coming soon">Report</span>
</div>

## Abstract

<p class="project-abstract">
ACM FAccT brings together scholars, advocates, civil society members, and government representatives to examine the social impacts of AI and machine learning. This project reports on a large-scale participatory design process for reflexive conference governance, combining an in-person CRAFT session, an asynchronous Polis poll, and a governance-facing report for FAccT leadership. Participants helped set the agenda by writing seed statements, contributing new statements, and surfacing patterns of agreement, disagreement, and uncertainty through collective voting. The work offers an early example of participatory design applied to a venue that critically studies AI's societal impacts, and contributes a scalable case study for large-scale co-design.
</p>
