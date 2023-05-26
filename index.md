---
title: Buttons
---

---
---
{
	"title": "Buttons",
	"language": "en",
	"description": "Buttons page including working examples to test how various text appears on different backgrounds.",
	"dateModified": "2023-05-23"
}
---

<p>This page showcases wet-boew utility features including some integration from Bootstrap 4 such as: <code>bg-primary</code>, <code>text-center</code>, <code>text-white</code> and others.</p>
<p>Please note that some backported Bootstrap 4 classes have been adjusted to follow Bootstrap 3.4's view breakpoints. For example, small (<code>sm</code>) view's minimum width is 768px in Bootstrap 3.4, as opposed to 576px in Bootstrap 4.</p>

<h2>On this page:</h2>

<ul>
	<li><a href="#wetoverride">WET Override</a></li>
	<li><a href="#bootstrap">Bootstrap</a></li>
	<li><a href="#gcweb">GCWeb</a></li>
</ul>

<h2 id="wetoverride">WET Override</h2>

<h3><code>text-white</code></h3>
<p>Set the text color to white.</p>
<h4>Working example</h4>
<h5>Paragraph</h5>
<p class="bg-dark text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
<h5>Link</h5>
<p class="bg-dark"><a class="text-white" href="#">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</a></p>
<h5>Button</h5>
<button type="button" class="btn bg-dark text-white">button</button>
<h4>Code sample</h4>
<pre><code>
&lt;h5&gt;Paragraph&lt;/h5&gt;
&lt;p class="bg-dark <strong>text-white</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
&lt;h5&gt;Link&lt;/h5&gt;
&lt;p class="bg-dark"&gt;&lt;a class="<strong>text-white</strong>" href="#"&gt; Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/a&gt;&lt;/p&gt;
&lt;h5&gt;Button&lt;/h5&gt;
&lt;button type="button" class="btn bg-dark <strong>text-white</strong>"&gt; Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/button&gt;</code></pre>

<h3><code>text-sm-left</code></h3>
<p>Align text to the left in small view and over.</p>
<h4>Working example</h4>
<p class="text-right text-sm-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
<h4>Code sample</h4>
<pre><code>&lt;p class="text-right <strong>text-sm-left</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;</code></pre>

<h3><code>text-sm-right</code></h3>
<p>Align text to the right in small view and over.</p>
<h4>Working example</h4>
<p class="text-sm-right">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
<h4>Code sample</h4>
<pre><code>&lt;p class="<strong>text-sm-right</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;</code></pre>

<h2 id="bootstrap">Bootstrap</h2>

<h3>Button Sizes</h3>
<p>Bootstrap provides 3 different size options: Small, Regular, and Large.</p>
<h4>Working example</h4>
<button type="button" class="btn btn-sm">Small button</button>
<button type="button" class="btn">Regular button</button>
<button type="button" class="btn btn-lg">Large button</button>

<h4>Code sample</h4>
<pre><code>
	&lt;button type="button" class="btn <strong>btn-sm</strong>"&gt;
	Small button
	&lt;/button&gt;
	&lt;button type="button" class="btn"&gt;
	Regular button
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-lg</strong>"&gt;
	Large button
	&lt;/button&gt;</code></pre>

<h3>Common Styles</h3>
<p>Bootstrap provides different styles of buttons.</p>
<h4>Working example</h4>
<button type="button" class="btn btn-default">Default</button>
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-danger">Danger</button>

<h4>Code sample</h4>
<pre><code>
	&lt;button type="button" class="btn <strong>btn-default</strong>"&gt;
	Default
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-primary</strong>"&gt;
	Primary
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-success</strong>"&gt;
	Success
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-info</strong>"&gt;
	Info
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-warning</strong>"&gt;
	Warning
	&lt;/button&gt;
	&lt;button type="button" class="btn <strong>btn-danger</strong>"&gt;
	Danger
	&lt;/button&gt;</code></pre>

<p>Links can also be styled to look like buttons</p>
<h4>Working example</h4>
<a href="" class="btn">Link</a>

<h4>Code sample</h4>
<pre><code>&lt;a href="" class="<strong>btn</strong>"&gt;Link&lt;/a&gt;
</code></pre>

<h3>Button groups (Horizontal)</h3>
<p>Group a series of buttons together on a single line with the button group</p>
<h4>Working Example</h4>
<div class="btn-group">
	<button type="button" class="btn">Left</button>
	<button type="button" class="btn">Middle</button>
	<button type="button" class="btn">Right</button>
</div>

<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>btn-group</strong>"&gt;
	&lt;button type="button" class="btn"&gt;
	Left
	&lt;/button&gt;
	&lt;button type="button" class="btn"&gt;
	Middle
	&lt;/button&gt;
	&lt;button type="button" class="btn"&gt;
	Right
	&lt;/button&gt;
&lt;/div&gt;</code></pre>

<h3>Button groups (Vertical)</h3>
<p>Make a set of buttons appear vertically stacked rather than horizontally.</p>
<h4>Working Example</h4>
<div class="btn-group-vertical">
	<button type="button" class="btn">Top</button>
	<button type="button" class="btn">Middle</button>
	<button type="button" class="btn">Bottom</button>
</div>

<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>btn-group-vertical</strong>"&gt;
	&lt;button type="button" class="btn"&gt;
	Top
	&lt;/button&gt;
	&lt;button type="button" class="btn"&gt;
	Middle
	&lt;/button&gt;
	&lt;button type="button" class="btn"&gt;
	Bottom
	&lt;/button&gt;
&lt;/div&gt;</code></pre>

<h3>Button toolbar</h3>
<p>Combine sets of button groups into button toolbars for more complex components.</p>
<h4>Working Example</h4>
<div class="btn-toolbar" role="toolbar" aria-label="Toolbar with button groups">
  <div class="btn-group mr-2" role="group" aria-label="First group">
    <button type="button" class="btn">1</button>
    <button type="button" class="btn">2</button>
    <button type="button" class="btn">3</button>
    <button type="button" class="btn">4</button>
  </div>
  <div class="btn-group mr-2" role="group" aria-label="Second group">
    <button type="button" class="btn">5</button>
    <button type="button" class="btn">6</button>
    <button type="button" class="btn">7</button>
  </div>
  <div class="btn-group" role="group" aria-label="Third group">
    <button type="button" class="btn">8</button>
  </div>
</div>

<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>btn-toolbar</strong>" role="toolbar" aria-label="Toolbar with button groups"&gt;
	&lt;div class="btn-group" role="group" aria-label="First group"&gt;
		&lt;button type="button" class="btn"&gt;
		1
		&lt;/button&gt;
		&lt;button type="button" class="btn"&gt;
		2
		&lt;/button&gt;
		&lt;button type="button" class="btn"&gt;
		3
		&lt;/button&gt;
		&lt;button type="button" class="btn"&gt;
		4
		&lt;/button&gt;
	&lt;/div&gt;

	&lt;div class="btn-group" role="group" aria-label="Second group"&gt;
		&lt;button type="button" class="btn"&gt;
		5
		&lt;/button&gt;
		&lt;button type="button" class="btn"&gt;
		6
		&lt;/button&gt;
		&lt;button type="button" class="btn"&gt;
		7
		&lt;/button&gt;
	&lt;/div&gt;

	&lt;div class="btn-group" role="group" aria-label="Third group"&gt;
		&lt;button type="button" class="btn"&gt;
		8
		&lt;/button&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3>Input Groups</h3>
<p>Easily extend form controls by adding buttons, or button groups on either side of textual inputs, custom selects, and custom file inputs.</p>
<h4>Working Example</h4>
<div class="input-group mb-3">
  <div class="input-group-btn">
    <button class="btn" type="button">Button</button>
  </div>
  <input type="text" class="form-control">
</div>

<div class="input-group mb-3">
  <input type="text" class="form-control">
   <div class="input-group-btn">
    <button class="btn" type="button">Button</button>
  </div>
</div>

<h4>Code Sample</h4>
<pre><code>&lt;div class="<strong>input-group</strong> mb-3"&gt;
	&lt;div class="<strong>input-group-btn</strong>"&gt;
		&lt;button class="btn" type="button"&gt;Button&lt;/button&gt;
	&lt;/div&gt;
	&lt;input type="text" class="form-control"&gt;
&lt;/div&gt;

&lt;div class="<strong>input-group</strong> mb-3"&gt;
	&lt;input type="text" class="form-control"&gt;
	&lt;div class="<strong>input-group-btn</strong>"&gt;
		&lt;button class="btn" type="button"&gt;Button&lt;/button&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>


<h3>Text Colors</h3>
<p>Set text to one of the Bootstrap colors.</p>
<h4>Working example</h4>
<div class="well">
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Muted</h5>
		<p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Primary</h5>
		<p class="text-primary">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Success</h5>
		<p class="text-success">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Info</h5>
		<p class="text-info">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Warning</h5>
		<p class="text-warning">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Danger</h5>
		<p class="text-danger">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="well"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Muted&lt;/h5&gt;
		&lt;p class="<strong>text-muted</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Primary&lt;/h5&gt;
		&lt;p class="<strong>text-primary</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Success&lt;/h5&gt;
		&lt;p class="<strong>text-success</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Info&lt;/h5&gt;
		&lt;p class="<strong>text-info</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Warning&lt;/h5&gt;
		&lt;p class="<strong>text-warning</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Danger&lt;/h5&gt;
		&lt;p class="<strong>text-danger</strong>"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3>Text Align</h3>
<p>Align text on the page.</p>
<h4>Working example</h4>
<div class="well">
	<div class="well mrgn-tp-md mrgn-bttm-md text-left">
		<h5 class="mrgn-tp-md">Aligned-left</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md text-right">
		<h5 class="mrgn-tp-md">Aligned-right</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md text-center">
		<h5 class="mrgn-tp-md">Aligned-center</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md text-justify">
		<h5 class="mrgn-tp-md">Aligned-justify</h5>
		<p>Ambitioni dedisse scripsisse iudicaretur. Cras mattis iudicium purus sit amet fermentum. Donec sed odio operae, eu vulputate felis rhoncus. Praeterea iter est quasdam res quas ex communi. At nos hinc posthac, sitientis piros Afros. Petierunt uti sibi concilium totius Galliae in diem certam indicere. Cras mattis iudicium purus sit amet fermentum.</p>
	</div>
	<div class="well mrgn-tp-md mrgn-bttm-md text-nowrap" style="width: 8rem; border: 2px solid black">
		<h5 class="mrgn-tp-md">No wrap</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="well"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>text-left</strong>"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Aligned-left&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>text-right</strong>"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Aligned-right&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>text-center</strong>"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Aligned-center&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>text-justify</strong>"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Aligned-justify&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>text-nowrap</strong>" style="width: 8rem; border: 2px solid black"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;No wrap&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h2 id="gcweb">GCWeb</h2>

<h3><code>bg-gctheme</code></h3>
<p>Set background to the gctheme.</p>
<h4>Working example</h4>
<div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="bg-gctheme text-white well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="<strong>bg-gctheme</strong> text-white well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3><code>bg-cover</code></h3>
<p>Set background image to fully cover the box size.</p>
<h4>Working example</h4>
<div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>bg-cover</strong> well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3><code>bg-center</code></h3>
<p>Set background image in the center of the container.</p>
<h4>Working example</h4>
<div class="bg-center well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>bg-center</strong> well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3><code>bg-norepeat</code></h3>
<p>Prevent background image to be repeated in the container.</p>
<h4>Working example</h4>
<div class="bg-norepeat well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="well mrgn-tp-md mrgn-bttm-md">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="<strong>bg-norepeat</strong> well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3><code>bg-darker</code></h3>
<p>Set a black background to an element.</p>
<h4>Working example</h4>
<div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="well mrgn-tp-md mrgn-bttm-md bg-darker text-white">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>bg-darker</strong> text-white"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>

<h3><code>bg-dark</code></h3>
<p>Set a dark background to an element.</p>
<h4>Working example</h4>
<div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg">
	<div class="well mrgn-tp-md mrgn-bttm-md bg-dark text-white">
		<h5 class="mrgn-tp-md">Heading</h5>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.</p>
	</div>
</div>
<h4>Code sample</h4>
<pre><code>&lt;div class="bg-cover well" data-bgimg="../../demos/tabs/img/investinourfuture.jpg"&gt;
	&lt;div class="well mrgn-tp-md mrgn-bttm-md <strong>bg-dark</strong> text-white"&gt;
		&lt;h5 class="mrgn-tp-md"&gt;Heading&lt;/h5&gt;
		&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ante nulla, condimentum at mollis et, scelerisque quis dolor. Suspendisse viverra in ante id consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Fusce sodales ipsum vitae faucibus iaculis. Nulla in blandit dolor. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean non interdum sapien. Nunc non volutpat dui, in malesuada justo. Etiam feugiat accumsan pulvinar. Quisque blandit est in placerat finibus. Sed et ullamcorper velit. Nullam euismod iaculis ligula sit amet consequat. Aenean luctus quis nisi nec feugiat.&lt;/p&gt;
	&lt;/div&gt;
&lt;/div&gt;</code></pre>
