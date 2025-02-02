<h1>Activity Life Cycle Phase</h1>

<img src="https://developer.android.com/images/activity_lifecycle.png" alt="Activity Life Cycle Diagram" width="600"/>

<h3>onCreate()</h3>

<h3>onStart()</h3>

<h3>onResume()</h3>

<h3>onPause()</h3>

<h3>onStop()</h3>

<h3>onDestroy()</h3>

<p>When you create Activity A, the <code>onStart()</code>, <code>onCreate()</code>, and <code>onResume()</code> methods are called.</p>

<p>When you redirect from the first activity to the second activity, the <code>onPause()</code> and <code> onStop()</code>method of the first activity is called.</p>

<p>The second activity then calls <code>onStart()</code>, <code>onResume()</code>, and <code>onCreate()</code>.</p>

<p>After redirecting back to the first activity, the second activity calls <code>onDestroy()</code>,<code>onStop()</code> and the first activity calls the <code>onStart()</code> and <code>onResume()</code> methods again.</p>

