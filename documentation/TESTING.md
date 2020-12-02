# This page contains documentation for testing and debugging the project.

# Milestone Project 1

## The H20 Crisis

Please forward questions to my [e-mail](patrik.svahnstrom@gmail.com)

1. <strong>Testing</strong>
2. <strong>Bugs & Errors</strong>
3. <strong>Final Testing</strong><br>
   - Testing Landing Page - Line 73.
   - Testing Resources Page - Line 104.
   - Testing Partner Page - Line 142.

# 1. Testing

Color codes:<br>
<span style="color:red;">Red is errors <br>
<span style="color:orange;">Orange is warnings<br>
<span style="color:green;">Green is fixed errors or warnings<br>

> <strong>#2020-12-02</strong> (~19:35) [Testing placeholder 404 page]
>
> > Expected result: 404 page to show when invalid link is selected.
> >
> > > Actual Result:
> >
> > > Measure Taken:

> <strong>#2020-12-02 (~13:20)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:orange;">unknown supplier extension</span><br>
> >
> > > - -webkit-background-size
> > > - -moz-background-size
> > > - -o-background-size
> > >   > Measure Tanken:<span style="color:green;">No warnings found when removing webkit/moz/o-background-size.</span>

> <strong>#2020-12-01 (~18:30)</strong> [W3C CSS Validator - Jigsaw](https://jigsaw.w3.org/css-validator/)
>
> > <span style="color:red;">filepath errors across all pages.</span>
> >
> > > <span style="color: green;">Filepath errors across all pages (Fixed)</span>

> > <span style="color:red;">Background image slows down loading.</span>
> >
> > > <span style="color: green;">Backgrond image slows down loading (Fixed)</span>

> > <span style="color: orange;">Redundant code in css.style.</span>
> >
> > > <span style="color: red;">Redundant code in css.style </span>

# 2. Bugs & Errors

> <span style="color: orange;">Active link not showing correct color. (2020-11-30)

> - <strong>Expected result:</strong>
>   > "Help Us & Contacts" link to be correct color when active, and not green as it is in idle state.
>   >
>   > - <strong>Result:</strong>
>   >   > <span style="color: red;"> "Help Us & Contacts" link turns the wrong color on active but is being overwritten to turn back to green. </span>
>   > - <strong>Solution:</strong>
>   >   > <span style="color: green;">Targetting the correct class with proper selector</span>

# 3. Final Testing

Color schematic: <br id="landingpagetesting">
- <span style="color:#007bff">Blue is Top Navigation Elements</span><br>
- <span style="color:#d39e00">Orange is In-page navigation Elements</span><br>
- <span style="color:#bf7272;">Red is Navigation Elements</span><br>
- <span style="color:#3e0e0e;">Burgundy is Anchor Element</span><br>
    * Prerequisite to being approved is that the anchor element opens in a new tab. <br>
    if the link references to an external page.
- <span style="color:#d300cd;">Magenta is Social Media icons Elements</span><br>
- <span style="color:#001ad3;">Ultramarine is Footer Navigation Elements</span><br>
- <span style="color:#00d3c9;">Cyan is Footer email Element</span><br>

> Testing Landing page
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link</span>

> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Navigation "What is happening?"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Nav. "Why is it happening?"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">inpage Nav. "What can we do?" </span>

> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Water Scarcity Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Resouces Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">GWI Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UNECE Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UN SDG-6 Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Solar Desalination Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Smart Irrigation (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Partner's Link (Internal)</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Resources</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>

> Testing Resources Page
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link</span>

> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Navigation "Let's Learn"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">Inpage Nav. "Water Facts"</span>
> > > - <span style="color:green;">[X] <span style="color:#d39e00">inpage Nav. "Formal Sources" </span>

> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Why is it happening (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">World Wildlife Foundation Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Ramsar Convention link(_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">68 Wetlands Links(_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UK Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Mexico Link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">SDG-6 Link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Water Footprint Network Link (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">UNESCO-IHE (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">National Water Footprint Accounts link (_blank_)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Yangtze link (_blank)</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 1 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 2 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 3 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 4 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 5 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 6 Links</span>
> > > - <span style="color:green;">[X] <span style="color:#3e0e0e;">Table 7 Links</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to The H2O Crisis</span>
> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Partners</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>

> Testing Partners Page
>
> > Does the link work?
> >
> > > - <span style="color:green;">[X] <span style="color:#007bff">Navigator Brand link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Informational Resources" link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Partners" link (internal)</span>
> > > - <span style="color:green;">[X] <span style="color:#007bff">Nav. "Help us" link (internal)</span>

> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to The H2O Crisis</span>
> > > - <span style="color:green;">[X] <span style="color:#001ad3;">Footer Navigation to Partners</span>

> > > - <span style="color:green;">[X]<span style="color:#00d3c9;">Email link</span>