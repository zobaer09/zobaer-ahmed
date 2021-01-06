+++
# Gallery section using the Blank widget and Gallery element (shortcode).
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 66  # Order that this section will appear.

title = "Gallery"
subtitle = ""
+++

<style>
#image-container img {
    border-radius: 10px;
    max-width: 40%;
    height: auto;
}
</style>

<div id="image-container">
{{< gallery >}}
</div>

