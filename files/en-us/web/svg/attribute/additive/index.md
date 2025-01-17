---
title: additive
slug: Web/SVG/Attribute/additive
tags:
  - NeedsCompatTable
  - NeedsExample
  - SVG
  - SVG Attribute
---
{{SVGRef}}

The **`additive`** attribute controls whether or not an animation is additive.

It is frequently useful to define animation as an offset or delta to an attribute's value, rather than as absolute values.

You can use this attribute with the following SVG elements:

- {{SVGElement("animate")}}
- {{SVGElement("animateColor")}}
- {{SVGElement("animateMotion")}}
- {{SVGElement("animateTransform")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td><code>replace</code> | <code>sum</code></td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td><code>replace</code></td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>No</td>
    </tr>
  </tbody>
</table>

- sum
    - : Specifies that the animation will add to the underlying value of the attribute and other lower priority animations.
- replace
    - : Specifies that the animation will override the underlying value of the attribute and other lower priority animations. This is the default, however the behavior is also affected by the animation value attributes {{SVGAttr("by")}} and {{SVGAttr("to")}}, as described in [SMIL Animation: How from, to and by attributes affect additive behavior](https://www.w3.org/TR/2001/REC-smil-animation-20010904/#FromToByAndAdditive).

## Specifications

<table class="no-markdown">
  <thead>
    <tr>
      <th scope="col">Specification</th>
      <th scope="col">Status</th>
      <th scope="col">Comment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        {{SpecName("SVG Animations 2", "#AdditiveAttribute", "additive")}}
      </td>
      <td>{{Spec2("SVG Animations 2")}}</td>
      <td>No change</td>
    </tr>
    <tr>
      <td>
        {{SpecName("SVG1.1", "animate.html#AdditiveAttribute", "additive")}}
      </td>
      <td>{{Spec2("SVG1.1")}}</td>
      <td>Initial definition</td>
    </tr>
  </tbody>
</table>

## See also

- [SMIL Animation specification](https://www.w3.org/TR/2001/REC-smil-animation-20010904/#AdditiveAttribute)
