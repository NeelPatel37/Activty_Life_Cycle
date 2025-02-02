<h1>Activity Life Cycle Phase</h1>

<img src="https://developer.android.com/images/activity_lifecycle.png" alt="Activity Life Cycle Diagram" width="600"/>

<h2>onCreate()</h2>

<h2>onStart()</h2>

<h2>onResume()</h2>

<h2>onPause()</h2>

<h2>onDestroy()</h2>


<p>When you create Activity A, the <code>onStart()</code>, <code>onCreate()</code>, and <code>onResume()</code> methods are called.</p>

<p>When you redirect from the first activity to the second activity, the <code>onPause()</code> method of the first activity is called.</p>

<p>The second activity then calls <code>onStart()</code>, <code>onResume()</code>, and <code>onCreate()</code>.</p>

<p>After redirecting back to the first activity, the second activity calls <code>onDestroy()</code>, and the first activity calls the <code>onStart()</code> and <code>onResume()</code> methods again.</p>

