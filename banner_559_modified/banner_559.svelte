<script>
    export let subtitle, title, link0, link1, image0, height, width, alt, source0, source1;
</script>

<!-- ============================================ -->
<!--                Banner 559                  -->
<!-- ============================================ -->

<!-- ============================================ -->
<!--                   Banner                     -->
<!-- ============================================ -->
<div id="banner-559">
<div class="cs-container">
<span class="cs-int-topper">{subtitle}</span>
<span class="cs-int-title">{title}</span>
<div class="cs-breadcrumbs">
<a class="cs-link" href="{link0}">Home</a>
<a class="cs-link cs-active" href="{link1}">About</a>
</div>
</div>
<!--Background Image-->
<picture class="cs-background">
<!--Mobile Image-->
<source media="(max-width: 600px)" srcset="{source0}"/>
<!--Tablet and above Image-->
<source media="(min-width: 601px)" srcset="{source1}"/>
<img alt="{alt}" aria-hidden="true" decoding="async" height="{height}" loading="lazy" src="{image0}" width="{width}"/>
</picture>
</div>
