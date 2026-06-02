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
  <!-- ستون جزوه‌ها (با دو static_files) -->
  <div class="column">
    <h2>📖 Lectures (Sessions 1–21)</h2>
    <div class="lectures-container">
      <table class="lectures-table">
        <thead>
          <tr><th>Session</th><th>Chapter Title</th><th>Download</th></tr>
        </thead>
        <tbody>
          <tr><td style="text-align:center;">1</th><td>Boolean retrieval</th><td><a class="download-link" href="/static_files/static_files/lectures/ch1.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">2</th><td>The term vocabulary and postings lists</th><td><a class="download-link" href="/static_files/static_files/lectures/ch2.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">3</th><td>Dictionaries and tolerant retrieval</th><td><a class="download-link" href="/static_files/static_files/lectures/ch3.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">4</th><td>Index construction</th><td><a class="download-link" href="/static_files/static_files/lectures/ch4.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">5</th><td>Index compression</th><td><a class="download-link" href="/static_files/static_files/lectures/ch5.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">6</th><td>Scoring, term weighting and the vector space model</th><td><a class="download-link" href="/static_files/static_files/lectures/ch6.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">7</th><td>Computing scores in a complete search system</th><td><a class="download-link" href="/static_files/static_files/lectures/ch7.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">8</th><td>Evaluation in information retrieval</th><td><a class="download-link" href="/static_files/static_files/lectures/ch8.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">9</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <tr><td style="text-align:center;">10</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <tr><td style="text-align:center;">11</th><td>Chapter 11 (title to be confirmed)</th><td><a class="download-link" href="/static_files/static_files/lectures/ch11.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">12</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <tr><td style="text-align:center;">13</th><td>Chapter 13 (title to be confirmed)</th><td><a class="download-link" href="/static_files/static_files/lectures/ch13.pdf">📄 PDF</a></th></td>
          <tr><td style="text-align:center;">14</th><td>Vector space classification</th><td><a class="download-link" href="/static_files/static_files/lectures/Ch14.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">15</th><td>Support vector machines and machine learning on documents</th><td><a class="download-link" href="/static_files/static_files/lectures/Ch15.pdf">📄 PDF</a></th></td>
          <tr><td style="text-align:center;">16</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <td><td style="text-align:center;">17</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <tr><td style="text-align:center;">18</th><td><em>Will be added later</em></th><td><span class="future-badge">🔜 Coming soon</span></th></tr>
          <tr><td style="text-align:center;">19</th><td>Web search basics</th><td><a class="download-link" href="/static_files/static_files/lectures/Ch19.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">20</th><td>Web crawling and indexes</th><td><a class="download-link" href="/static_files/static_files/lectures/Ch20.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">21</th><td>Link analysis</th><td><a class="download-link" href="/static_files/static_files/lectures/Ch21.pdf">📄 PDF</a></th></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- ستون کوئیزها و پاسخ‌نامه‌ها -->
  <div class="column">
    <h2>📝 Quizzes</h2>
    <div class="lectures-container">
      <table class="lectures-table">
        <thead><tr><th>Quiz</th><th>Title</th><th>Download</th></tr></thead>
        <tbody>
          <tr><td style="text-align:center;">1</th><td>Quiz 1</th><td><a class="download-link" href="/static_files/quizzes/Quiz-1.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">2</th><td>Quiz 2</th><td><a class="download-link" href="/static_files/quizzes/Quiz-2.PDF">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">3</th><td>Quiz 3</th><td><a class="download-link" href="/static_files/quizzes/Quiz-3%20.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">4</th><td>Quiz 4</th><td><a class="download-link" href="/static_files/quizzes/Quiz-4%20.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">5</th><td>Quiz 5</th><td><a class="download-link" href="/static_files/quizzes/Quiz-5.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">6</th><td>Quiz 6</th><td><a class="download-link" href="/static_files/quizzes/Quiz-6%E2%80%94The%20Last%20Chapter...pdf">📄 PDF</a></th></tr>
        </tbody>
      </table>
    </div>

    <h2>🔑 Answer Keys</h2>
    <div class="lectures-container">
      <table class="lectures-table">
        <thead>
          <tr>
            <th>Quiz</th>
            <th>Answer Key</th>
            <th>Download</th>
          </tr>
        </thead>
        <tbody>
          <tr><td style="text-align:center;">1</th>
            <td>Quiz 1 Answer</th>
            <td><a class="download-link" href="/static_files/answer_Q/IR-Quiz-1-Answer.pdf">📄 PDF</a></th>
          </tr>
          <tr><td style="text-align:center;">2</th>
            <td>Quiz 2 Answer</th>
            <td><a class="download-link" href="/static_files/answer_Q/IR-Quiz-2-Answer.pdf">📄 PDF</a></th>
          </tr>
          <tr><td style="text-align:center;">3</th>
            <td>Quiz 3 Answer</th>
            <td><a class="download-link" href="/static_files/answer_Q/IR-Quiz-3-Answer.pdf">📄 PDF</a></th>
          </tr>
          <tr><td style="text-align:center;">4</th>
            <td>Quiz 4 Answer</th>
            <td><a class="download-link" href="/static_files/answer_Q/IR-Quiz-4-Answer.pdf">📄 PDF</a></th>
          </tr>
          <tr><td style="text-align:center;">5</th>
            <td>Quiz 5 Answer</th>
            <td><a class="download-link" href="/static_files/answer_Q/IR-Quiz-5-Answer.pdf">📄 PDF</a></th>
          </tr>
          <tr><td style="text-align:center;">6</th>
            <td>Quiz 6 Answer (Soon)</th>
            <td><span class="future-badge">🔜 Coming soon</span></th>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="supplement-card">
  <h3>📊 Supplementary Material – Evaluation Metrics</h3>
  <p>A concise summary of key evaluation metrics in IR (precision, recall, MAP, nDCG, etc.) with exercises.</p>
  <a class="download-link" href="/static_files/static_files/lectures/metrics+ex.pdf">📄 Download Metrics + Exercises (PDF)</a>
</div>
