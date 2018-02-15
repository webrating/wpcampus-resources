---
ID: 15742
post_title: Accessibility
author: WPCampus
post_excerpt: >
  Accessibility refers to the inclusive
  practice of removing barriers that
  prevent interaction with, or access to,
  websites by people with disabilities.
layout: resource
permalink: >
  https://wpcampus.org/resources/accessibility/
published: true
post_date: 2017-10-24 22:07:45
---
<h2>What is accessibility?</h2>

Refers to the inclusive practice of removing barriers that prevent interaction with, or access to, websites by people with disabilities.

Though estimates vary, most studies find that about one fifth (20%) of the population has some kind of disability. Each of the major categories of disabilities requires certain types of adaptations in the design of web content. Most of the time, these adaptations benefit nearly everyone, not just people with disabilities. Almost everyone benefits from helpful illustrations, properly-organized content, and clear navigation. Similarly, while captions are a necessity for deaf users, they can be helpful to others, including anyone who views a video without audio.

<h3>The major categories of disability types</h3>

<ul>
	<li>Visual
		<ul>
			<li>Blindness, low vision, color-blindness</li>
		</ul>
	</li>
	<li>Hearing
		<ul>
			<li>Deafness and hard-of-hearing</li>
		</ul>
	</li>
	<li>Motor
		<ul>
			<li>Inability to use a mouse, slow response time, limited fine motor control</li>
		</ul>
	</li>
	<li>Cognitive
		<ul>
			<li>Learning disabilities, distractibility, inability to remember or focus on large amounts of information</li>
		</ul>
	</li>
</ul>

<h3>Common barriers</h3>

<ul>
	<li>Non-text content (images, videos, audio, etc) without text equivalent
		<ul>
			<li>Do images have alt attributes? Do videos have captions?</li>
		</ul>
	</li>
	<li>Being unable to access actions and functionality via keyboard and keyboard traps
		<ul>
			<li>Can you access links, buttons, modals, tooltips, form fields, esp. radios and checkboxes?</li>
		</ul>
	</li>
	<li>Actions without defined purpose or context
		<ul>
			<li>For example: &lt;buttons&gt; without text or a title attribute</li>
			<li>A screen reader would just read "button" and user would have no idea what happens when they click the button.</li>
		</ul>
	</li>
	<li>Using color to convey information and insufficient design contrast (for those with color blindness)
		<ul>
			<li>For example: links that are not underlined.</li>
			<li>If a user is color blind to blue and there is no underline, they can't tell that a word is a different color and are unaware of the action.</li>
		</ul>
	</li>
	<li>Unable to visually determine if an element has focus
		<ul>
			<li>If you tab to a button, a link, or a form field, can the user tell it has focus?</li>
		</ul>
	</li>
	<li>Unable to skip large blocks of repeatable content
		<ul>
			<li>For example: If a user is navigating via keyboard, and can't skip over the header, they have to tab through your entire header on every page.</li>
		</ul>
	</li>
</ul>

<h2>How To Get Started</h2>
Introducing accessibility practices into your workflow has a few steps but over time it will become second nature. It makes your technology better for everyone. You'll find all the information you need on this page.

<ol>
	<li>Become familiar with WCAG standards and practices (text alternatives, access via keyboard, etc).</li>
	<li>Adopt a checklist into your workflow to ensure you've addressed needs for new content and functionality.</li>
	<li>Scan new content and functionality for standard violations.</li>
</ol>

<h2>Standards</h2>

<ul>
 	<li>WCAG 2.0
		<ul>
		 	<li><a href="https://www.w3.org/WAI/WCAG20/quickref/?currentsidebar=%23col_customize&amp;levels=a%2Caaa">How to meet WCAG 2.0</a></li>
			<li><a href="http://adrianroselli.com/2017/08/whats-new-in-wcag-2-1.html">What's new in WCAG 2.1</a></li>
		</ul>
	</li>
 	<li>Section 508
 		<ul>
			<li><strong>Section 508 now incorporates (WCAG) 2.0.</strong> Must comply beginning January 18, 2018.</li>
 			<li><a href="https://www.section508.gov/node/493">The Section 508 Update</a></li>
 			<li><a href="https://www.section508.gov/content/build/website-accessibility-improvement">Improving Website Accessibility</a></li>
 		</ul>
 	</li>
	<li><a href="https://www.levelaccess.com/accessibility-regulations/">International accessibility laws and standards</a></li>
</ul>

<h2>ARIA (Accessible Rich Internet Applications)</h2>

WAI-ARIA (Accessible Rich Internet Applications or ARIA) is a W3C protocol for enhancing and supporting accessibility of scripted and dynamic content to be provided to assistive technology. It especially helps with dynamic content and advanced user interface controls developed with Ajax, HTML, JavaScript, and related technologies. ARIA enhances accessibility of interactive controls (such as tree menus, drag and drop, sliders, sort controls, etc.), provides content roles for identifying page structure (navigation, search, main content, etc.), areas that can be dynamically updated (called "live regions" in ARIA), better support for keyboard accessibility and interactivity, and much more.

ARIA is supported by most up-to-date browsers and screen readers. It is also supported by many scripting libraries. Although ARIA is not yet universally supported, when used with existing HTML and scripting accessibility techniques, it can provide additional accessibility support where it is supported while not causing compatibility issues where it is not yet supported.

<ul>
	<li><a href="https://www.w3.org/TR/wai-aria/introduction">W3C: (WAI-ARIA) 1.1</a></li>
	<li><a href="https://www.w3.org/WAI/intro/aria">W3C: WAI-ARIA Overview</a></li>
	<li><a href="https://developers.google.com/web/fundamentals/accessibility/semantics-aria/">Google: Introduction to ARIA</a></li>
	<li><a href="https://developer.mozilla.org/en-US/docs/Web/Accessibility/An_overview_of_accessible_web_applications_and_widgets">MDN: An overview of accessible web applications and widgets</a></li>
	<li><a href="http://accessibility%20of%20rich%20internet%20applications/">WebAIM: ARIA</a></li>
</ul>

<h2>Resources</h2>

<h3>Articles</h3>
<ul>
	<li><a href="https://the-pastry-box-project.net/anne-gibson/2014-july-31">An Alphabet of Accessibility Issues</a></li>
    <li><a href="http://universaldesign.ie/What-is-Universal-Design/The-7-Principles/">7 Principles of Universal Design</a></li>
    <li><a href="https://axesslab.com/accessibility-according-to-pwd/">Accessibility according to actual people with disabilities</a></li>
    <li><a href="https://axesslab.com/colorblind-accessibility-web-fail-success-cases/">Colorblind Accessibility on the Web – Fail and Success Cases</a></li>
    <li><a href="http://inclusivedesignprinciples.org/">Inclusive Design Principles</a></li>
    <li><a href="https://css-tricks.com/lets-talk-speech-css/">Let's Talk About Speech CSS</a></li>
    <li><a href="https://github.com/joe-watkins/top-people-to-follow-in-web-accessibility">People to Follow in Web Accessibility</a></li>
    <li><a href="https://www.fastcodesign.com/3047080/try-reading-this-font-and-youll-better-understand-what-dyslexia-is-like">Try Reading This Font And You'll Better Understand What Dyslexia Is Like</a></li>
    <li><a href="https://medium.com/@matuzo/writing-css-with-accessibility-in-mind-8514a0007939">Writing CSS with Accessibility in Mind</a></li>
    <li><a href="https://medium.com/alistapart/writing-html-with-accessibility-in-mind-a62026493412">Writing HTML with Accessibility in Mind</a></li>
    <li><a href="https://medium.com/@matuzo/writing-javascript-with-accessibility-in-mind-a1f6a5f467b9">Writing JavaScript with Accessibility in Mind</a></li>
    <li><a href="https://css-tricks.com/small-tweaks-can-make-huge-impact-websites-accessibility/">Small Tweaks That Can Make a Huge Impact on Your Website’s Accessibility</a></li>
</ul>

<h3>Books</h3>
<ul>
 	<li><a href="https://abookapart.com/products/accessibility-for-everyone">Accessibility for Everyone, by Laura Kalbag</a></li>
 	<li><a href="https://abookapart.com/products/design-for-real-life">Design for Real Life, by Eric Meyer &amp; Sara Wachter-Boettcher</a></li>
</ul>

<h3>Checklists</h3>
<ul>
    <li><a href="https://accessibility.18f.gov/checklist/">18F Accessibility Checklist</a></li>
    <li><a href="http://a11yproject.com/checklist.html">The A11Y Project Checklist</a></li>
    <li><a href="https://webaim.org/standards/wcag/checklist">WebAIM WCAG 2.0 Checklist</a></li>
    <li><a href="https://www.wuhcag.com/wcag-checklist/">"Wuhcag" WCAG 2.0 Checklist</a></li>
    <li><a href="https://itunes.apple.com/it/app/wcag-accessibility-checklist/id1130086539?l=en&mt=8">WCAG Accessibility Checklist (Mac iOS app)</a></li>
</ul>

<h3>Courses/Professional Development</h3>
<ul>
 	<li><a href="https://webaccessibility.withgoogle.com/course">Google: Introduction to Web Accessibility</a></li>
	<li><a href="https://www.udacity.com/course/web-accessibility--ud891">Developing with empathy: Web Accessibility course from Google and Udacity</a></li>
	<li><a href="https://www.inclusivedesign24.org/">Inclusive Design 24 conference</a>
		<ul>
			<li>A free 24-hour online community event on accessibility, archived on YouTube.</li>
		</ul>
	</li>
</ul>

<h3>Newsletters/Podcasts</h3>
<ul>
 	<li><a href="http://a11yweekly.com/">Accessibility Weekly</a></li>
 	<li><a href="https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g">A11ycasts</a></li>
 	<li><a href="https://wpcampus.org/podcast/accessibility/">WPCampus Podcast: Accessibility</a></li>
</ul>

<h3>References (by subject)</h3>
<h4>Modals/Dialogs</h4>
<ul>
	<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog">The &lt;dialog&gt; element</a></li>
	<li><a href="https://keithjgrant.com/posts/2018/meet-the-new-dialog-element/">Meet the New Dialog Element</a></li>
	<li><a href="https://www.marcozehe.de/2015/02/05/advanced-aria-tip-2-accessible-modal-dialogs/">How to make accessible modal dialogs</a></li>
</ul>

<h3>Websites</h3>
<ul>
 	<li><a href="http://a11yproject.com/">The A11Y Project</a></li>
 	<li><a href="https://www.microsoft.com/en-us/design/inclusive">Inclusive Design at Microsoft</a></li>
 	<li><a href="https://webaim.org/">WebAIM</a></li>
	<li><a href="https://a11ywins.tumblr.com/">Accessibility Wins</a>
		<ul>
			<li>Showcasing accessible user interfaces and tools.</li>
		</ul>
	</li>
</ul>

<h3>WPCampus Sessions</h3>
<em>The following sessions include video recordings.</em>
<ul>
 	<li><a href="https://2017.wpcampus.org/schedule/lightning-talks/accessibility-case-study-wcag-screen-reader-solutions-accordions-tabs/">Accessibility case study: WCAG and screen reader solutions for accordions and tabs</a></li>
 	<li><a href="https://online.wpcampus.org/schedule/empathy-and-accessibility-for-the-web/">Empathy and Accessibility for the Web</a></li>
 	<li><a href="https://2016.wpcampus.org/schedule/techniques-tools-resources-accessibility/">Techniques, Tools and Resources for Making WordPress Website WCAG 2.0 Compliant</a></li>
 	<li><a href="https://2017.wpcampus.org/schedule/tools-approaches-managing-content-accessibility-web-identity-scale/">Tools and approaches for managing content, accessibility and web identity at scale</a></li>
 	<li><a href="https://2016.wpcampus.org/schedule/wordpress-accessibility/">WordPress Accessibility: Where We Are and Where We’re Going</a></li>
 	<li><a href="https://2017.wpcampus.org/schedule/a11y-workshop/">WORKSHOP: WordPress and A11y</a></li>
</ul>

<h2>What Schools Are Using</h2>
<ul>
 	<li>Birkbeck, University of London
 		<ul>
 			<li><a href="http://bbk.ac.uk/birkbeck-for-all">Birkbeck for All: Joined-up thinking on accessibility</a>
 				<ul>
 					<li>Guidelines to support inclusivity of learning resources.</li>
 				</ul>
 			</li>
 		</ul>
 	</li>
 	<li>Hampshire College
		<ul>
			<li><a href="http://hampshirecollege.github.io/a11yeval">Built a web app using the WAVE API</a> to scan multiple URLs.</li>
		</ul>
	</li>
 	<li>Harvard University
 		<ul>
 			<li><a href="https://accessibility.huit.harvard.edu/">Harvard University Online Accessibility</a>
 				<ul>
 					<li>Contains checklists, guides, resources, and policies.</li>
 				</ul>
 			</li>
 		</ul>
 	</li>
 	<li>University of Nebraska-Lincoln
 		<ul>
 			<li><a href="https://webaudit.unl.edu/">UNL Web Audit</a>
 				<ul>
 					<li>Uses Axe. Helps you maintain your site by running automatic audits that help you find and fix problems that affect user experience.</li>
 				</ul>
 			</li>
 		</ul>
 	</li>
 	<li>NC State
 		<ul>
 			<li><a href="https://github.com/briandeconinck/ncsu-a11y-helper">NC State Accessibility Helper</a> uses aXe to check for common accessibility issues.</li>
 		</ul>
 	</li>
 	<li>Stanford University
 		<ul>
 			<li><a href="https://soap.stanford.edu/">Stanford's Online Accessibility Program (SOAP)</a></li>
 		</ul>
 	</li>
 	<li>Washington State University
 		<ul>
 			<li>Audit process:
 				<ul>
				 	<li>Automatic scan with accessibility collector.</li>
				 	<li>Browser scan with Axe Chrome extension.</li>
				 	<li>Manual check of elements not caught by automatic scans.</li>
				</ul>
			</li>
			<li><a href="https://web.wsu.edu/accessibility/">Accessibility Policy</a></li>
			<li><a href="https://web.wsu.edu/accessibility-guides/">Accessibility Guides</a> for the web, forked from the <a href="https://github.com/18F/accessibility/">18F accessibility guides</a>.</li>
			<li><a href="https://github.com/washingtonstateuniversity/WSU-Accessibility-Collector">WSU Accessibility Collector</a> (in development)
				<ul>
					<li>Uses <a href="https://github.com/pa11y/pa11y">Pa11y</a> for accessibility checking, which in turn uses <a href="https://github.com/squizlabs/HTML_CodeSniffer">HTML_CodeSniffer</a>.</li>
				</ul>
			</li>
			<li><a href="https://github.com/washingtonstateuniversity/WSU-Accessibility-Dashboard">WSU Accessibility Dashboard</a> (in development) and the corresponding <a href="https://dashboard.wsu.edu/accessibility/">public facing dashboard</a>.</li>
			<li>They have a lot of open-sources tools <a href="https://github.com/Washingtonstateuniversity">in their Github repo</a>.</li>
		</ul>
	</li>
</ul>

<h2>Tools</h2>

<h3>Color Contrast</h3>
<ul>
	<li>Color Contrast Analyzer
		<ul>
			<li>Is a <a href="https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll">Google Chrome extension</a>.</li>
			<li>Adds a button to the top of the browser that, when clicked, will analyze a web page for conformance with WCAG 2.0 color contrast requirements.</li>
		</ul>
	</li>
	<li>"I want to see like the colour blind"
		<ul>
			<li>Is a <a href="https://chrome.google.com/webstore/detail/i-want-to-see-like-the-co/jebeedfnielkcjlcokhiobodkjjpbjia">Google Chrome extension</a>.</li>
			<li>Adds a button to the top of the browser that, when clicked, will show you how your web page appears to those with color blindness.</li>
		</ul>
	</li>
    <li><a href="http://colorsafe.co/">Color Safe</a>
        <ul>
            <li>Accessible color palettes based on WCAG Guidelines of text and background contrast ratios.﻿</li>
        </ul>
    </li>
 	<li><a href="https://material.io/color/#!/?view.left=0&amp;view.right=0">Color Tool</a>
		<ul>
		 	<li>Web page that allows you to insert your color palette and view accessibility information.</li>
		</ul>
	</li>
    <li><a href="https://itunes.apple.com/us/app/sim-daltonism/id693112260">Sim Daltonism</a>
        <ul>
            <li>Free Mac OS app that lets you visualize colors as they are perceived with various types of color blindness.﻿﻿</li>
        </ul>
    </li>
 	<li><a href="https://webaim.org/resources/contrastchecker/">WebAIM color contrast checker</a>
		<ul>
		 	<li>Simple foreground vs. background checker.</li>
		</ul>
	</li>
</ul>

<h3>Components</h3>
<ul>
	<li><a href="https://www.w3.org/blog/wai-components-gallery/">Accessible UI Components List</a> from the W3C</li>
	<li>Modals
		<ul>
            <li><a href="https://launchy.io/">Launchy, an accessible modal window</a></li>
		</ul>
	</li>
</ul>

<h3>Scanning/Audits</h3>
<ul>
 	<li>Accessibility Developer Tools
		<ul>
		 	<li>Is a <a href="https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb">Google Chrome extension</a>.</li>
		 	<li>Adds a tab to your developer tools to run a scan/audit of your current page.</li>
		</ul>
	</li>
	<li><a href="https://addyosmani.com/a11y/">A11y Command-line Tools</a>
		<ul>
			<li>Web accessibility audits powered by the Chrome Accessibility Developer Tools.</li>
			<li>Run audits against local or remote URLs in the command-line to return a list of accessibility improvements that can be made.</li>
		</ul>
	</li>
 	<li><a href="https://www.deque.com/products/axe/">Axe</a>
 	    <ul>
		 	<li><a href="https://github.com/dequelabs/axe-core">Axe-core</a> is a Javascript file you can use to scan your site.</li>
		 	<li>Offers a <a href="https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd">Google Chrome extension</a>. Adds a tab to your developer tools to run a scan/audit of your current page.
				<ul>
					<li><a href="https://chrome.google.com/webstore/detail/axe-coconut/iobddmbdndbbbfjopjdgadphaoihpojp">aXe-Coconut</a> is a Chrome extension that allows you to try their latest APIs and experimental rules before they are released.</li>
				</ul>
		    	</li>
		 	<li>They offer premium services.</li>
	    </ul>
	</li>
 	<li>ARIA validator
		<ul>
			<li>Is a <a href="https://chrome.google.com/webstore/detail/aria-validator/oigghlanfjgnkcndchmnlnmaojahnjoc">Google Chrome extension</a>.</li>
			<li>Adds a button to the top of the browser that, when clicked, will scan and audit ARIA usage.</li>
		</ul>
	</li>
 	<li><a href="https://fae.disability.illinois.edu">Functional Accessibility Evaluator</a>
		<ul>
			<li>Developed by the Disability Research and Educational Services at the University of Illinois at Urbana-Champaign. <a href="https://fae.disability.illinois.edu/abouts/">Learn more about the tool</a></li>
		</ul>
	</li>
 	<li><a href="https://squizlabs.github.io/HTML_CodeSniffer/">HTML CodeSniffer</a>
		<ul>
		 	<li>A Javascript application that can be used to run scans.</li>
		 	<li>Also has a bookmarklet for quick scans on any web page.</li>
		</ul>
	</li>
	<li><a href="https://open-indy.github.io/Koa11y/">Koa11y</a>
		<ul>
			<li>Koa11y is a desktop app that allows you to automatically detect accessibility issues on webpages.</li>
		</ul>
	</li>
 	<li><a href="https://developers.google.com/web/tools/lighthouse/">Lighthouse</a>
		<ul>
			<li>Works as a Chrome DevTool, CLI, or node module.</li>
			<li>Will check for accessibility issues along with performance issues, best practices, and if the site is a progressive web app.</li>
		</ul>
	</li>
 	<li><a href="https://github.com/pa11y">Pa11y</a>
		<ul>
		 	<li>They have a lot of open source tools.</li>
		</ul>
	</li>
 	<li><a href="https://siteimprove.com/">Siteimprove</a>
		<ul>
		 	<li>Offers a <a href="https://chrome.google.com/webstore/detail/siteimprove-accessibility/efcfolpjihicnikpmhnmphjhhpiclljc">Google Chrome extension</a>. Adds a button to the top of the browser that, when clicked, will scan/audit your web page.</li>
		 	<li>They offer premium services.</li>
		</ul>
	</li>
 	<li><a href="http://khan.github.io/tota11y/">Tota11y</a>
		<ul>
			<li>Has Javascript file you can place on site.</li>
			<li>Offers a <a href="https://chrome.google.com/webstore/detail/tota11y-plugin-from-khan/oedofneiplgibimfkccchnimiadcmhpe">Google Chrome extension</a>.</li>
			<li>Both the file and the extension will add a button to the bottom of your page that, when clicked, will show you the results of a scan.</li>
		</ul>
	</li>
 	<li><a href="http://wave.webaim.org/">WAVE</a>
		<ul>
		 	<li>Offers a <a href="https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh">Google Chrome extension</a>.</li>
		 	<li>Both the main tool and the extension will scan/audit your site and show you results.</li>
		 	<li>They also have a premium API.</li>
		</ul>
	</li>
</ul>

<h3>Screen Readers</h3>
<ul>
    <li><a href="http://www.afb.org/prodBrowseCatResults.aspx?CatID=49">List of available screen readers</a> from the American Foundation for the Blind</li>
    <li><a href="https://webaim.org/techniques/screenreader/">Designing for Screen Reader Compatibility</a></li>
    <li><a href="https://dequeuniversity.com/screenreaders/survival-guide">Screen Reader Survival Guide</a></li>
    <li><a href="http://nvaccess.org">For Windows: NVDA</a>
        <ul>
            <li>Free Open-source screen reader. Only works with Microsoft Windows.</li>
            <li>Works well with Firefox. Can be installed as a portable app on a thumb drive.</li>
        </ul>
    </li>
    <li><a href="https://www.apple.com/voiceover/info/guide/_1124.html">For Mac: VoiceOver</a>
        <ul>
            <li>Is built-in to Mac OS.</li>
			<li><a href="http://accessibility.psu.edu/screenreaders/voiceover/">Helpful guide to VoiceOver commands</a></li>
        </ul>
    </li>
    <li>Chromevox
        <ul>
            <li>Is a <a href="https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en">Google Chrome extension</a>.</li>
        </ul>
    </li>
</ul>

<h3>Generators</h3>
<ul>
 	<li>Documentation
		<ul>
		 	<li><a href="https://developer.paciellogroup.com/blog/2017/09/infusion-an-inclusive-documentation-builder/">Infusion, an accessible documentation builder</a></li>
		</ul>
	</li>
</ul>

<h3>WordPress Plugins</h3>
<ul>
 	<li><a href="https://wordpress.org/plugins/font-resizer/">Font Resizer</a>
		<ul>
		 	<li>Allows you to give the visitors of your site the option to change the font size.</li>
		</ul>
	</li>
 	<li><a href="https://wordpress.org/plugins/gspeech/">GSpeech Text to Speech</a>
		<ul>
		 	<li>A text to speech solution for WordPress. It uses Google power to provide you the best quality of automatic text to speech service.</li>
		</ul>
	</li>
 	<li><a href="https://github.com/briandeconinck/ncsu-a11y-helper">NC State Accessibility Helper</a>
		<ul>
			<li>Adds "Run Accessibility Check" button to post editor, generating an annotated preview highlighting potential accessibility issues.</li>
			<li>Still in active development - contributions welcome!</li>
		</ul>
	</li>
 	<li><a href="https://wordpress.org/plugins/wp-accessibility/">WP Accessibility</a>
		<ul>
		 	<li>Helps with a variety of common accessibility problems in WordPress themes.</li>
		</ul>
	</li>
 	<li><a href="https://wordpress.org/plugins/automatic-alternative-text/">Automatic Alternative Text</a>
		<ul>
		 	<li>Adds alt text using Microsoft cognitive services</li>
		</ul>
	</li>
</ul>
