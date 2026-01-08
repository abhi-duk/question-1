<h2>UI/UX → React Learning Experiment</h2>

<p><strong>Author:</strong> Abhi Krishnan R<br/>
<strong>Role:</strong> Lead UI/UX Developer, CDIPD</p>

<h3>Context</h3>

<p>
I come primarily from a <strong>UI/UX background</strong>. My journey into React started out of curiosity and a genuine interest in learning. Initially, even understanding how a JavaScript function behaves inside a React component was challenging. Over time, by exploring React concepts such as hooks, state, effects, and data flow, things gradually became clearer.
</p>

<p>
This repository represents that learning process.
</p>

<p>
Instead of keeping the implementation minimal, I intentionally treated this as a <strong>data-heavy interface</strong> to understand how React behaves under realistic conditions and how well I could handle optimization, safety, and graceful loading using my current knowledge.
</p>

<p>
<em>This may be a small project in scope, but if time permits, I believe even small projects should aim for the best possible outcome.</em>
</p>

<h3>Live Demo</h3>

<p>
The application is hosted on Vercel:
</p>

<p>
<a href="https://question-1-abhi-cdipd.vercel.app" target="_blank">
https://question-1-abhi-cdipd.vercel.app
</a>
</p>

<h3>What I Tried to Do (and Why)</h3>

<p>
Below are the technical and architectural decisions I made based on my current understanding of React. I am honestly open to feedback on whether these approaches are correct, over-engineered, or could be simplified.
</p>

<ul>
  <li>
    Cached API responses in <code>sessionStorage</code> with a TTL to reduce repeated fetches and improve load performance.
  </li>
  <li>
    Used <code>AbortController</code> along with clear loading and error states to keep the UI responsive and safe during network interruptions.
  </li>
  <li>
    Implemented deferred search input and memoized filtering logic to maintain performance as the dataset grows.
  </li>
  <li>
    Virtualized the user list using a fixed-size window to ensure smooth rendering for large data volumes.
  </li>
  <li>
    Built derived analytics such as counts by city and company using memoization to avoid unnecessary recalculations.
  </li>
  <li>
    Added CSV export functionality for both filtered data and the full dataset to meet data-handling requirements.
  </li>
  <li>
    Included filter reset options, filtered totals, and basic coverage metrics to make data exploration easier and clearer.
  </li>
</ul>

<h3>An Honest Note</h3>

<p>
This project is part of my <strong>learning journey</strong>, not a claim of expertise. If any of the decisions here are incorrect, excessive, or could be handled in a better or simpler way, I would genuinely appreciate that feedback.
</p>

<p>
Suggestions on architecture, performance strategies, React best practices, or overall approach are most welcome.
</p>

<p>
Thank you for taking the time to review this.
</p>

<p>
<strong>— Abhi Krishnan R</strong>
</p>
