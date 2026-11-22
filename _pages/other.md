---
layout: archive
title: "Other"
permalink: /other/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<style>
  .other-page {
    margin-top: 0.5rem;
  }

  .other-page .other-intro {
    margin: 0 0 1.25rem;
    color: var(--global-text-color);
    line-height: 1.6;
  }

  .other-page .other-section {
    margin: 2.25rem 0 0.5rem;
  }

  .other-page .other-section h2 {
    margin-bottom: 0.35rem;
    padding-bottom: 0.4rem;
    border-bottom: 1px solid var(--global-border-color);
  }

  .other-page .other-lead {
    margin: 0 0 1rem;
    color: var(--global-text-color-light);
    font-size: 0.95em;
    line-height: 1.55;
  }

  .other-page .other-list {
    display: flex;
    flex-direction: column;
    gap: 0.85rem;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .other-page .other-card,
  .other-page .other-quote {
    margin: 0;
    padding: 0.95rem 1.05rem 1rem;
    border: 1px solid var(--global-border-color);
    border-radius: 8px;
    background: var(--global-bg-color);
  }

  .other-page .other-card-head {
    display: flex;
    align-items: baseline;
    gap: 0.65rem;
  }

  .other-page .other-index {
    flex: 0 0 auto;
    min-width: 1.6rem;
    color: var(--global-base-color);
    font-weight: 700;
    font-variant-numeric: tabular-nums;
  }

  .other-page .other-title {
    margin: 0;
    font-size: 1.05em;
    font-weight: 650;
    line-height: 1.35;
  }

  .other-page .other-meta {
    margin: 0.45rem 0 0.7rem 2.25rem;
    padding: 0;
    list-style: none;
  }

  .other-page .other-meta li {
    margin: 0.15rem 0;
    color: var(--global-text-color);
    font-size: 0.92em;
    line-height: 1.45;
  }

  .other-page .other-meta span {
    color: var(--global-text-color);
    font-weight: 600;
  }

  .other-page .other-link {
    display: inline-block;
    margin-left: 2.25rem;
    padding: 0.2rem 0.65rem;
    border: 1px solid var(--global-base-color);
    border-radius: 999px;
    color: var(--global-base-color);
    font-size: 0.85em;
    font-weight: 600;
    text-decoration: none;
    line-height: 1.5;
  }

  .other-page .other-link:hover {
    background: var(--global-base-color);
    color: #fff;
  }

  .other-page .other-quote {
    border-left: 3px solid var(--global-base-color);
  }

  .other-page .other-kicker {
    margin: 0 0 0.55rem;
    color: var(--global-base-color);
    font-size: 0.78em;
    font-weight: 700;
    letter-spacing: 0.04em;
    text-transform: uppercase;
  }

  .other-page .other-quote blockquote {
    margin: 0 0 0.75rem;
    padding: 0;
    border: 0;
    color: var(--global-text-color);
    font-style: italic;
    line-height: 1.65;
  }

  .other-page .other-quote blockquote p {
    margin: 0;
  }

  .other-page .other-attr {
    margin: 0 0 0.7rem;
    color: var(--global-text-color);
    font-size: 0.92em;
  }

  .other-page .other-attr em {
    color: var(--global-text-color-light);
  }

  .other-page .other-related {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 0.7rem;
    margin: 0;
    padding-top: 0.65rem;
    border-top: 1px solid var(--global-border-color);
  }

  .other-page .other-related a {
    font-size: 0.88em;
  }

  @media (max-width: 480px) {
    .other-page .other-meta,
    .other-page .other-link {
      margin-left: 0;
    }
  }
</style>

<div class="other-page" markdown="0">

<section class="other-section">
  <h2>All Time Classic Music I Like</h2>
  <p class="other-lead">A small collection of timeless compositions and performances that have stayed with me over the years.</p>

  <ol class="other-list">
    <li class="other-card">
      <div class="other-card-head">
        <span class="other-index">01</span>
        <h3 class="other-title">To Vals Ton Hamenon Oniron</h3>
      </div>
      <ul class="other-meta">
        <li><span>Composer</span> · Manos Chatzidakis</li>
      </ul>
      <a class="other-link" href="https://youtu.be/KV0vPtPv3lw" target="_blank" rel="noopener">Listen</a>
    </li>

    <li class="other-card">
      <div class="other-card-head">
        <span class="other-index">02</span>
        <h3 class="other-title">I Melagholia Tis Eftihias</h3>
      </div>
      <ul class="other-meta">
        <li><span>Composer</span> · Manos Chatzidakis</li>
      </ul>
      <a class="other-link" href="https://youtu.be/m4-_Gk76pCU" target="_blank" rel="noopener">Listen</a>
    </li>

    <li class="other-card">
      <div class="other-card-head">
        <span class="other-index">03</span>
        <h3 class="other-title">Tha Simanoun Oi Kampanes</h3>
      </div>
      <ul class="other-meta">
        <li><span>Performer</span> · Grigoris Bithikotsis</li>
        <li><span>Lyrics</span> · Giannis Ritsos</li>
        <li><span>Composer</span> · Mikis Theodorakis</li>
      </ul>
      <a class="other-link" href="https://youtu.be/BD9GfcIEE6Y" target="_blank" rel="noopener">Listen</a>
    </li>

    <li class="other-card">
      <div class="other-card-head">
        <span class="other-index">04</span>
        <h3 class="other-title">The World We Knew</h3>
      </div>
      <ul class="other-meta">
        <li><span>Performer</span> · Frank Sinatra</li>
      </ul>
      <a class="other-link" href="https://youtu.be/dthgRdTf0Ds" target="_blank" rel="noopener">Listen</a>
    </li>
  </ol>
</section>

<section class="other-section">
  <h2>Poetry and Quotes</h2>
  <p class="other-lead">A curated selection of poetry, excerpts, and reflections that resonate with me. These pieces revolve around responsibility, humanity, and the journey of life.</p>

  <ol class="other-list">
    <li class="other-quote">
      <p class="other-kicker">01 · Responsibility</p>
      <blockquote>
        <p>Love responsibility. Say: It is my duty, and mine alone, to save the earth.<br>
        If it is not saved, then I alone am to blame.</p>
      </blockquote>
      <p class="other-attr"><strong>Nikos Kazantzakis</strong>, <em>Ascesis</em> (1927)</p>
      <div class="other-related">
        <a href="https://en.wikipedia.org/wiki/The_Saviors_of_God" target="_blank" rel="noopener">About the book</a>
        <a href="https://www.kazantzaki.gr/en" target="_blank" rel="noopener">Nikos Kazantzakis Museum</a>
        <a href="https://youtu.be/BVsSSkUJCkQ" target="_blank" rel="noopener">Documentary (English)</a>
        <a href="https://youtu.be/vOeoRrhmuZw" target="_blank" rel="noopener">Documentary (Greek)</a>
      </div>
    </li>

    <li class="other-quote">
      <p class="other-kicker">02 · Humanity as the Solution</p>
      <blockquote>
        <p>In our gradually shrinking world, everyone is in need of all the others.<br>
        We must look for man wherever we can find him.<br>
        When on his way to Thebes Oedipus encountered the Sphinx, his answer to its riddle was: ‘Man’.<br>
        That simple word destroyed the monster.</p>
      </blockquote>
      <p class="other-attr"><strong>Giorgos Seferis</strong>, Nobel Prize Banquet Speech (1963)</p>
      <div class="other-related">
        <a href="https://www.nobelprize.org/prizes/literature/1963/seferis/speech/" target="_blank" rel="noopener">Full speech</a>
        <a href="https://youtu.be/V92VPDYHg5Q" target="_blank" rel="noopener">Documentary (Greek)</a>
      </div>
    </li>

    <li class="other-quote">
      <p class="other-kicker">03 · Ithaka</p>
      <blockquote>
        <p>As you set out for Ithaka<br>
        hope the voyage is a long one,<br>
        full of adventure, full of discovery.<br>
        Laistrygonians, Cyclops,<br>
        angry Poseidon—don’t be afraid of them:<br>
        you’ll never find things like that on your way<br>
        as long as you keep your thoughts raised high,<br>
        as long as a rare excitement<br>
        stirs your spirit and your body.</p>
      </blockquote>
      <p class="other-attr"><strong>Konstantinos Kavafis</strong>, <em>Ithaka</em> (1975)</p>
      <div class="other-related">
        <a href="https://www.poetryfoundation.org/poems/51296/ithaka-56d22eef917ec" target="_blank" rel="noopener">Full poem</a>
        <a href="https://youtu.be/BPZ4HVkcoYU" target="_blank" rel="noopener">Documentary (Greek)</a>
      </div>
    </li>
  </ol>
</section>

</div>
