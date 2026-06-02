---
layout: lectures
title: Lectures
permalink: /lectures/
---

<style>
  .lectures-container {
    max-width: 100%;
    overflow-x: auto;
  }
  .lectures-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }
  .lectures-table thead tr {
    background: #1e3c72;
    color: #ffffff;
    text-align: left;
    font-weight: 600;
  }
  .lectures-table th,
  .lectures-table td {
    padding: 14px 12px;
    border-bottom: 1px solid #e2e8f0;
    vertical-align: middle;
  }
  .lectures-table tbody tr {
    background-color: #ffffff;
    transition: all 0.2s ease;
  }
  .lectures-table tbody tr:nth-child(even) {
    background-color: #f8fafc;
  }
  .lectures-table tbody tr:hover {
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
  .future-badge {
    background: #fef9c3;
    color: #854d0e;
    padding: 5px 12px;
    border-radius: 30px;
    font-size: 0.8rem;
    font-weight: 500;
    display: inline-block;
  }
  .two-columns {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    margin-bottom: 2rem;
  }
  .column {
    flex: 1;
    min-width: 280px;
  }
  .column h2 {
    margin-top: 0;
    color: #1e3c72;
    border-bottom: 2px solid #1e3c72;
    display: inline-block;
    padding-bottom: 0.3rem;
  }
  .supplement-card {
    margin-top: 2rem;
    background: #f1f5f9;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    border-left: 5px solid #1e3c72;
  }
  .supplement-card h3 {
    margin-top: 0;
    color: #0f2b4f;
  }
  @media (max-width: 700px) {
    .lectures-table th, .lectures-table td {
      padding: 10px 8px;
    }
    .download-link {
      padding: 4px 8px;
      font-size: 0.75rem;
    }
  }
</style>

<div class="two-columns">
  <!-- ستون اول: جدول جلسات -->
  <div class="column">
    <h2>📖 Lectures (Sessions 1–21)</h2>
    <div class="lectures-container">
      <table class="lectures-table">
        <thead>
          <tr>
            <th style="width: 12%;">Session</th>
            <th style="width: 60%;">Chapter Title</th>
            <th style="width: 28%;">Download</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>1</td><td>Boolean retrieval</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch1.pdf">📄 PDF</a></td></tr>
          <tr><td>2</td><td>The term vocabulary and postings lists</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch2.pdf">📄 PDF</a></td></tr>
          <tr><td>3</td><td>Dictionaries and tolerant retrieval</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch3.pdf">📄 PDF</a></td></tr>
          <tr><td>4</td><td>Index construction</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch4.pdf">📄 PDF</a></td></tr>
          <tr><td>5</td><td>Index compression</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch5.pdf">📄 PDF</a></td></tr>
          <tr><td>6</td><td>Scoring, term weighting and the vector space model</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch6.pdf">📄 PDF</a></td></tr>
          <tr><td>7</td><td>Computing scores in a complete search system</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch7.pdf">📄 PDF</a></td></tr>
          <tr><td>8</td><td>Evaluation in information retrieval</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch8.pdf">📄 PDF</a></td></tr>
          <tr><td>9</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>10</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>11</td><td>Chapter 11 <em>(title to be confirmed)</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch11.pdf">📄 PDF</a></td></tr>
          <tr><td>12</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>13</td><td>Chapter 13 <em>(title to be confirmed)</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/ch13.pdf">📄 PDF</a></td></tr>
          <tr><td>14</td><td>Vector space classification</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/Ch14.pdf">📄 PDF</a></td></tr>
          <tr><td>15</td><td>Support vector machines and machine learning on documents</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/Ch15.pdf">📄 PDF</a></td></tr>
          <tr><td>16</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>17</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>18</td><td><em>Will be added later</em></td><td><span class="future-badge">🔜 Coming soon</span></td></tr>
          <tr><td>19</td><td>Web search basics</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/Ch19.pdf">📄 PDF</a></td></tr>
          <tr><td>20</td><td>Web crawling and indexes</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/Ch20.pdf">📄 PDF</a></td></tr>
          <tr><td>21</td><td>Link analysis</td><td><a class="download-link" href="{{ site.baseurl }}/static_files/lectures/Ch21.pdf">📄 PDF</a></td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- ستون دوم: جدول کوئیزها -->
  <div class="column">
    <h2>📝 Quizzes</h2>
    <div class="lectures-container">
      <table class="lectures-table">
        <thead>
          <tr>
            <th>Quiz</th>
            <th>Title / Description</th>
            <th>Download</th>
          </tr>
        </thead>
        <tbody>
          <tr><td><strong>1</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-1.pdf">📄 PDF</a></td></tr>
          <tr><td><strong>2</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-2.PDF">📄 PDF</a></td></tr>
          <tr><td><strong>3</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-3%20.pdf">📄 PDF</a></td></tr>
          <tr><td><strong>4</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-4%20.pdf">📄 PDF</a></td></tr>
          <tr><td><strong>5</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-5.pdf">📄 PDF</a></td></tr>
          <tr><td><strong>6</strong></td><td><em>Title to be announced</em></td><td><a class="download-link" href="{{ site.baseurl }}/static_files/quizzes/Quiz-6%E2%80%94The%20Last%20Chapter...pdf">📄 PDF</a></td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="supplement-card">
  <h3>📊 Supplementary Material – Evaluation Metrics</h3>
  <p>A concise yet comprehensive summary of key evaluation metrics in Information Retrieval (precision, recall, MAP, nDCG, etc.) accompanied by practical exercises.</p>
  <a class="download-link" href="{{ site.baseurl }}/static_files/lectures/metrics+ex.pdf" style="background:#e2e8f0;">📄 Download Metrics + Exercises (PDF)</a>
</div>
