<script>
    export let p, h1, h2, h3, a, input, option, img, button, span, label;
</script>

<!-- ============================================ -->
<!--                cs-navigation-1343                  -->
<!-- ============================================ -->

<!-- ============================================ -->
<!--                 Navigation                   -->
<!-- ============================================ -->
<header id="cs-navigation">
<div class="cs-top-bar">
<div class="cs-top-container">
<!--Nav Logo-->
<a aria-label="back to home" class="cs-logo" href="{a.href_0attribute}">{a.a_0}</a>
<div class="cs-contact-group">
<a class="cs-contact-link" href="{a.href_1attribute}">{a.a_1}</a>
<a class="cs-contact-link" href="{a.href_2attribute}">{a.a_2}</a>
<a class="cs-button-solid" href="{a.href_3attribute}">{a.a_3}</a>
</div>
<!--Dark Mode toggle, uncomment button code if you want to enable a dark mode toggle-->
<button aria-label="dark mode toggle" id="dark-mode-toggle">{button.button_0}</button>
</div>
</div>
<!--Wrapped the bottom container in a wrapper div so we can have a full width background color, and centered the container inside of it-->
<div class="cs-bottom-bar">
<div class="cs-container">
<!--Navigation List-->
<nav class="cs-nav" role="navigation">
<!--Mobile Nav Toggle-->
<button aria-label="mobile menu toggle" class="cs-toggle">{button.button_1}</button>
<!-- We need a wrapper div so we can set a fixed height on the cs-ul in case the nav list gets too long from too many dropdowns being opened and needs to have an overflow scroll. This wrapper acts as the background so it can go the full height of the screen and not cut off any overflowing nav items while the cs-ul stops short of the bottom of the screen, which keeps all nav items in view no matter how mnay there are-->
<div class="cs-ul-wrapper">
<ul aria-expanded="false" class="cs-ul" id="cs-expanded">
<li class="cs-li">
<a class="cs-li-link cs-active" href="{a.href_4attribute}">{a.a_4}</a>
</li>
<li class="cs-li">
<a class="cs-li-link" href="{a.href_5attribute}">{a.a_5}</a>
</li>
<!--Copy and paste this cs-dropdown list item and replace any .cs-li with this cs-dropdown group to make a new dropdown and it will work-->
<li class="cs-li cs-dropdown" tabindex="0">
<span class="cs-li-link">
                                Services
                                <img alt="{img.alt_1attribute}" aria-hidden="true" class="cs-drop-icon" decoding="async" height="{img.height_1attribute}" src="{img.src_1attribute}" width="{img.width_1attribute}"/>
</span>
<ul class="cs-drop-ul">
<li class="cs-drop-li">
<a class="cs-li-link cs-drop-link" href="{a.href_6attribute}">{a.a_6}</a>
</li>
<li class="cs-drop-li">
<a class="cs-li-link cs-drop-link" href="{a.href_7attribute}">{a.a_7}</a>
</li>
</ul>
</li>
<li class="cs-li">
<a class="cs-li-link" href="{a.href_8attribute}">{a.a_8}</a>
</li>
<li class="cs-li">
<a class="cs-li-link" href="{a.href_9attribute}">{a.a_9}</a>
</li>
<li class="cs-li">
<a class="cs-li-link" href="{a.href_10attribute}">{a.a_10}</a>
</li>
</ul>
</div>
</nav>
<a class="cs-call" href="{a.href_11attribute}">{a.a_11}</a>
</div>
</div>
</header>
