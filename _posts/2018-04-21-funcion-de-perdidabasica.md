---
layout: post
title: Funcion de perdida(Basica)
category: Machine Learning
---

La p&eacute;rdida&nbsp;**L2**&nbsp;para un ejemplo determinado tambi&eacute;n se denomina **error al cuadrado.**

= Cuadrado de la diferencia entre la predicci&oacute;n y la etiqueta

= (observaci&oacute;n - predicci&oacute;n)2

= (y - y')2

Ya que queremos no solo reducir la p&eacute;rdida en un solo ejemplo, sino que nos interesa reducir la perdida en todo nuestro conjunto de datos:

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <semantics>
    <mrow>
      <mi>p</mi>
      <mrow class="MJX-TeXAtom-ORD">
        <mo>&#xE9;</mo>
      </mrow>
      <mi>r</mi>
      <mi>d</mi>
      <mi>i</mi>
      <mi>d</mi>
      <mi>a</mi>
      <mi>N</mi>
      <mn>2</mn>
      <mo>=</mo>
      <munder>
        <mo>&#x2211;<!-- ∑ --></mo>
        <mrow class="MJX-TeXAtom-ORD">
          <mo stretchy="false">(</mo>
          <mi>x</mi>
          <mo>,</mo>
          <mi>y</mi>
          <mo stretchy="false">)</mo>
          <mo>&#x2208;<!-- ∈ --></mo>
          <mi>D</mi>
        </mrow>
      </munder>
      <mo stretchy="false">(</mo>
      <mi>y</mi>
      <mo>&#x2212;<!-- − --></mo>
      <mi>p</mi>
      <mi>r</mi>
      <mi>e</mi>
      <mi>d</mi>
      <mi>i</mi>
      <mi>c</mi>
      <mi>c</mi>
      <mi>i</mi>
      <mrow class="MJX-TeXAtom-ORD">
        <mo>&#xF3;</mo>
      </mrow>
      <mi>n</mi>
      <mo stretchy="false">(</mo>
      <mi>x</mi>
      <mo stretchy="false">)</mo>
      <msup>
        <mo stretchy="false">)</mo>
        <mn>2</mn>
      </msup>
    </mrow>
    <annotation encoding="application/x-tex">pérdida N2 = \sum_{(x,y)\in D} (y - predicción(x))^2</annotation>
  </semantics>
</math>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <semantics>
    <mrow>
      <mo>&#x2211;<!-- ∑ --></mo>
      <mtext>:Sumamos todos los ejemplos en el conjunto de entrenamiento.</mtext>
    </mrow>
    <annotation encoding="application/x-tex">\sum \text{:Sumamos todos los ejemplos en el conjunto de entrenamiento.}</annotation>
  </semantics>
</math>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <semantics>
    <mrow>
      <mi>D</mi>
      <mtext>: A veces es &#xFA;til promediar todos los ejemplos,</mtext>
    </mrow>
    <annotation encoding="application/x-tex">D \text{: A veces es útil promediar todos los ejemplos,}</annotation>
  </semantics>
</math>

&nbsp;