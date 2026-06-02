---
layout: page
title: Course Project
permalink: /project/
---

<style>
  .project-container {
    max-width: 100%;
    overflow-x: auto;
  }
  .project-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }
  .project-table thead tr {
    background: #1e3c72;
    color: #ffffff;
    text-align: left;
    font-weight: 600;
  }
  .project-table th,
  .project-table td {
    padding: 14px 12px;
    border-bottom: 1px solid #e2e8f0;
    vertical-align: middle;
  }
  .project-table tbody tr {
    background-color: #ffffff;
    transition: all 0.2s ease;
  }
  .project-table tbody tr:nth-child(even) {
    background-color: #f8fafc;
  }
  .project-table tbody tr:hover {
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
  .deadline-badge {
    background: #fef9c3;
    color: #854d0e;
    padding: 5px 12px;
    border-radius: 30px;
    font-size: 0.8rem;
    font-weight: 500;
    display: inline-block;
  }
  .note-card {
    margin-top: 2rem;
    background: #f1f5f9;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    border-left: 5px solid #1e3c72;
  }
  .note-card p {
    margin: 0;
  }
  @media (max-width: 700px) {
    .project-table th, .project-table td {
      padding: 10px 8px;
    }
    .download-link {
      padding: 4px 8px;
      font-size: 0.75rem;
    }
  }
</style>

<div class="project-container">
  <table class="project-table">
    <thead>
      <tr>
        <th style="width: 10%;">Phase</th>
        <th style="width: 50%;">Goal / Description</th>
        <th style="width: 20%;">Deadline</th>
        <th style="width: 20%;">Download</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>1</strong></td>
        <td>Implement a simple indexer and Boolean search over a document collection.</td>
        <td><span class="deadline-badge">To be announced</span></td>
        <td><a class="download-link" href="{{ site.baseurl }}/static_files/project/F1/MIR__4042__Phase-1.zip">📄 ZIP</a></td>
      </tr>
      <tr>
        <td><strong>2</strong></td>
        <td>Implement TF‑IDF, cosine similarity, and evaluation metrics.</td>
        <td><span class="deadline-badge">To be announced</span></td>
        <td><a class="download-link" href="{{ site.baseurl }}/static_files/project/F2/IR__Phase-2.zip">📄 ZIP</a></td>
      </tr>
      <tr>
        <td><strong>3</strong></td>
        <td>Apply machine learning ranking models (e.g., Ranking SVM or LightGBM) and compare with traditional methods.</td>
        <td><span class="deadline-badge">To be announced</span></td>
        <td><a class="download-link" href="{{ site.baseurl }}/static_files/project/F3/IR__Spring2026__Phase3.zip">📄 ZIP</a></td>
      </tr>
    </tbody>
  </table>
</div>

<div class="note-card">
  <p><strong>📌 Note:</strong> Detailed instructions and submission guidelines for each phase will be announced via the Telegram channel and this website. If you face any issue with downloading, please contact the teaching assistants.</p>
</div>
