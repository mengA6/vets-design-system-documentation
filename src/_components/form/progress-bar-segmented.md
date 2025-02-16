---
layout: component
permalink: /components/form/progress-bar-segmented
has-parent: /components/form/
title: "Progress bar - Segmented"
intro-text: "A segmented progress bar updates users on their progress through a multi-step process."
aka: Step indicator
research-title: Progress bars
sketch-link: https://www.sketch.com/s/a52734dd-00d0-44f1-9c9e-ff4016130e5c/p/2FCC2B76-88D4-477C-AF19-EC1A1A6DA6B7/canvas
status: use-deployed
uswds-v3: default
web-component: va-segmented-progress-bar
anchors:
  - anchor: Examples - v1
  - anchor: Examples - v3
  - anchor: Usage
  - anchor: Code usage
  - anchor: Accessibility considerations
---

## Examples - v1

### Default

{% include storybook-preview.html story="components-va-segmented-progress-bar--default" link_text="va-segmented-progress-bar default" height="200px" %}

## Examples - v3

### Default

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--default" link_text="va-segmented-progress-bar v3 default" height="200px" %}

### Step Labels

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--step-labels" link_text="va-segmented-progress-bar v3 step labels" height="200px" %}

### Centered Step Labels

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--centered-step-labels" link_text="va-segmented-progress-bar v3 centered step labels" height="200px" %}

### Counters

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--counters" link_text="va-segmented-progress-bar v3 counters" height="200px" %}

### Small Counters

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--small-counters" link_text="va-segmented-progress-bar v3 small counters" height="200px" %}

### Centered Counters

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--centered-counters" link_text="va-segmented-progress-bar v3 centered counters" height="200px" %}

### Centered Small Counters

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--centered-small-counters" link_text="va-segmented-progress-bar v3 centered small counters" height="200px" %}

### Custom Header Level

{% include storybook-preview.html story="uswds-va-segmented-progress-bar--custom-header-level" link_text="va-segmented-progress-bar v3 custom header level" height="200px" %}

## Usage

<a class="vads-c-action-link--blue" href="https://designsystem.digital.gov/components/step-indicator/">Refer to the U.S. Web Design System for usage guidance</a>

### Additional guidance for VA

### When to consider something else

* **Tracking progress over an extended period of time**: If the steps in a process span multiple interactions or an extended period of time then use the [Process list]({{ site.baseurl }}/components/process-list) component.
* **Steps can be completed in any order**: If steps can be completed in any order consider the [Master/Detail screen pattern](https://designingwebinterfaces.com/designing-web-interfaces-12-screen-patterns) and provide status as to when each section is complete and when the overall process is complete.
* **Checklist**: The progress bar is not intended to handle a checklist.

### Placement

* The progress bar should appear directly below the h1 title of the process and before the form itself.
 
{% include component-docs.html component_name=page.web-component %}

## Accessibility considerations

<a class="vads-c-action-link--blue" href="https://designsystem.digital.gov/components/alert/#accessibility-alert">Refer to the U.S. Web Design System for accessibility guidance</a>

## Related

* [Activity progress bar]({{ site.baseurl }}/components/progress-bar)
* [Process list]({{ site.baseurl }}/components/process-list)