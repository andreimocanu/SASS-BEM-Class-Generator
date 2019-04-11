# SASS BEM Class Generator

An easy to use mixin for generating classess using BEM elements and modifiers naming system.

<h3>Usage</h3>

<pre>
.selector {

	@include e(element) {
		font-size: 10px;
	}

	@include m(modifier) {
		font-size: 15px;
	}
}
</pre>

<h3>Result</h3>

<pre>
.selector__element {
	font-size: 10px;
}

.selector--modifier {
	font-size: 15px;
}
</pre>
