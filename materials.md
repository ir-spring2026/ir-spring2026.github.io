---
layout: page
title: Materials
permalink: /materials/
---

<style>
  .materials-container {
    max-width: 100%;
  }
  .top-section {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    align-items: center;
    margin-bottom: 2rem;
  }
  .image-card {
    flex: 0 0 180px;
    background: #f8fafc;
    padding: 10px;
    border-radius: 16px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    text-align: center;
  }
  .image-card img {
    max-width: 100%;
    border-radius: 12px;
  }
  .intro-text {
    flex: 1;
  }
  .books-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    margin: 1.5rem 0;
  }
  .books-table th,
  .books-table td {
    padding: 14px 12px;
    border-bottom: 1px solid #e2e8f0;
    vertical-align: middle;
  }
  .books-table thead tr {
    background: #1e3c72;
    color: #ffffff;
    text-align: left;
    font-weight: 600;
  }
  .books-table tbody tr {
    background-color: #ffffff;
    transition: all 0.2s ease;
  }
  .books-table tbody tr:nth-child(even) {
    background-color: #f8fafc;
  }
  .books-table tbody tr:hover {
    background-color: #eef2ff;
    transform: scale(1.01);
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }
  .download-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: #f1f5f9;
    padding: 6px 12px;
    border-radius: 30px;
    font-size: 0.85rem;
    font-weight: 500;
    color: #1e3c72;
    text-decoration: none;
    transition: background 0.2s;
  }
  .download-link:hover {
    background: #e2e8f0;
    color: #0f2b4f;
    text-decoration: none;
  }
  .external-link {
    color: #1e3c72;
    text-decoration: none;
    font-weight: 500;
  }
  .external-link:hover {
    text-decoration: underline;
  }
  .similar-courses {
    background: #f8fafc;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    margin: 1.5rem 0;
    border-left: 5px solid #1e3c72;
  }
  .similar-courses ul {
    margin: 0;
    padding-left: 1.2rem;
  }
  .similar-courses li {
    margin: 0.5rem 0;
  }
  .extra-card {
    margin-top: 1.5rem;
    background: #f1f5f9;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    border-left: 5px solid #1e3c72;
  }
  .extra-card h3 {
    margin-top: 0;
    color: #0f2b4f;
  }
  .extra-card ul {
    margin-bottom: 0;
  }
  @media (max-width: 700px) {
    .top-section {
      flex-direction: column;
      align-items: center;
    }
    .image-card {
      flex-basis: auto;
      max-width: 200px;
    }
    .books-table th, .books-table td {
      padding: 10px 8px;
    }
    .download-link {
      padding: 4px 8px;
      font-size: 0.75rem;
    }
  }
</style>

<div class="materials-container">
  <div class="top-section">
    <div class="image-card">
      <img src="{{ site.baseurl }}/_images/screenshots/OIP.webp" alt="Information Retrieval illustration">
    </div>
    <div class="intro-text">
      <p><strong>Lecture slides</strong> are available per session in the <a href="{{ site.baseurl }}/lectures/" class="external-link">Lectures section</a>. There is no single comprehensive handout.</p>
    </div>
  </div>

  <h2>📖 Recommended Books & References</h2>

  <table class="books-table">
    <thead>
      <tr>
        <th>Ref.</th>
        <th>Book Title / Authors</th>
        <th>Download / Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>[MRS]</strong></th>
        <td>Christopher D. Manning, Prabhakar Raghavan, Hinrich Schütze – <em>Introduction to Information Retrieval</em> (Cambridge, 2008)</th>
        <td><a class="download-link" href="https://nlp.stanford.edu/IR-book/pdf/irbookonlinereading.pdf">📄 PDF</a></th>
      </tr>
      <tr>
        <td><strong>[HNG]</strong></th>
        <td>Hang Li – <em>Learning to Rank for Information Retrieval and Natural Language Processing</em> (Morgan & Claypool, 2011)</th>
        <td><a class="download-link" href="https://www.iro.umontreal.ca/~nie/IFT6255/Books/Learning-to-rank.pdf">📄 PDF</a></th>
      </tr>
      <tr>
        <td><strong>[MC]</strong></th>
        <td>Bhaskar Mitra, Nick Craswell – <em>An Introduction to Neural Information Retrieval</em> (Foundations and Trends in IR, 2018)</th>
        <td><a class="external-link" href="https://www.emerald.com/ftinr/article-abstract/13/1/1/1328679/An-Introduction-to-Neural-Information-Retrieval?redirectedFrom=fulltext">🔗 Access Link</a></th>
      </tr>
    </tbody>
  </table>

  <div class="similar-courses">
    <h3>🌐 Similar Courses</h3>
    <ul>
      <li><a href="https://web.stanford.edu/class/cs276/" class="external-link">CS276 / LING286: Information Retrieval and Web Search</a> – Stanford University</li>
      <li><a href="https://www.cs.purdue.edu/homes/clifton/cs54701/" class="external-link">CS54701: Information Retrieval</a> – Purdue University</li>
      <li><a href="https://www.youtube.com/watch?v=MM48kc5Zq8A&list=PL8PYTP1V4I8D4BeyjwWczukWq9d8PNyZp" class="external-link">Advanced NLP Fall 2024 (Retrieval and RAG)</a> – CMU (YouTube)</li>
      <li><a href="https://systems.ethz.ch/education/courses/2024-spring/information-retrieval-.html" class="external-link">Information Retrieval</a> – ETH Zurich</li>
      <li><a href="https://www.cl.cam.ac.uk/teaching/1718/InfoRtrv/materials.html" class="external-link">Information Retrieval</a> – University of Cambridge</li>
    </ul>
  </div>

  <div class="extra-card">
    <h3>🛠 Additional Course Materials</h3>
    <ul>
      <li><a href="https://www.nltk.org/" class="external-link">NLTK</a> – Python library for text processing</li>
      <li><a href="https://scikit-learn.org/stable/modules/classes.html#module-sklearn.feature_extraction.text" class="external-link">Scikit-learn</a> – Text feature extraction (TF‑IDF)</li>
      <li><a href="https://www.elastic.co/" class="external-link">Elasticsearch</a> – Open‑source search engine</li>
      <li><a href="https://whoosh.readthedocs.io/" class="external-link">Whoosh</a> – Pure‑Python search library</li>
      <li><a href="https://sourceforge.net/p/lemur/wiki/RankLib/" class="external-link">RankLib</a> – Learning to rank library</li>
    </ul>
    <p><em>More resources will be added during the semester.</em></p>
  </div>
</div>
