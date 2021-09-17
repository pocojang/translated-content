---
title: border-inline-start-color
slug: Web/CSS/border-inline-start-color
tags:
  - CSS
  - Experimental
  - Propriété
  - Propriété logique
  - Reference
translation_of: Web/CSS/border-inline-start-color
---
<div>{{CSSRef}}{{SeeCompatTable}}</div>

<p>La propriété <strong><code>border-inline-start-color</code></strong> définit la couleur de la bordure pour le côté du début de l'élément orienté dans l'axe de lecture. Elle correspond à une propriété physique selon le mode d'écriture de l'élément, sa directionnalité et l'orientation du texte. Autrement dit, elle correspond à l'une des propriétés {{cssxref("border-top-color")}}, {{cssxref("border-right-color")}}, {{cssxref("border-bottom-color")}} ou {{cssxref("border-left-color")}} selon les valeurs des propriétés {{cssxref("writing-mode")}}, {{cssxref("direction")}} et {{cssxref("text-orientation")}}.</p>

<div>{{EmbedInteractiveExample("pages/css/border-inline-start-color.html")}}</div>

<p>Cette propriété est à rapprocher des autres propriétés logiques permettant de définir les couleurs de la bordure d'un élément :</p>

<ul>
 <li>{{cssxref("border-block-start-color")}},</li>
 <li>{{cssxref("border-block-end-color")}},</li>
 <li>{{cssxref("border-inline-end-color")}}.</li>
</ul>

<h2 id="Syntaxe">Syntaxe</h2>

<pre class="brush:css no-line-numbers">border-inline-start-color: red;
border-inline-start-color: #fffff;
border-inline-start-color: rgb(200, 0, 0);
</pre>

<h3 id="Valeurs">Valeurs</h3>

<dl>
 <dt><code>&lt;'border-color'&gt;</code></dt>
 <dd>La couleur de la bordure, voir {{cssxref("border-color")}} et {{cssxref("&lt;color&gt;")}}.</dd>
</dl>

<h3 id="Syntaxe_formelle">Syntaxe formelle</h3>

{{csssyntax}}

<h2 id="Exemples">Exemples</h2>

<h3 id="CSS">CSS</h3>

<pre class="brush: css">div {
  background-color: yellow;
  width: 120px;
  height: 120px;
}

.exemple {
  writing-mode: vertical-lr;
  border: 10px solid blue;
  border-inline-start-color: red;
}</pre>

<h3 id="HTML">HTML</h3>

<pre class="brush: html">&lt;div&gt;
  &lt;p class="exemple"&gt;Texte d'exemple&lt;/p&gt;
&lt;/div&gt;
</pre>

<h3 id="Résultat">Résultat</h3>

<p>{{EmbedLiveSample("Exemples", 140, 140)}}</p>

<h2 id="Spécifications">Spécifications</h2>

<table class="standard-table">
 <thead>
  <tr>
   <th scope="col">Spécification</th>
   <th scope="col">État</th>
   <th scope="col">Commentaires</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName("CSS Logical Properties", "#propdef-border-inline-start-color", "border-inline-start-color")}}</td>
   <td>{{Spec2("CSS Logical Properties")}}</td>
   <td>Définition initiale.</td>
  </tr>
 </tbody>
</table>

<p>{{cssinfo}}</p>

<h2 id="Compatibilité_des_navigateurs">Compatibilité des navigateurs</h2>

<p>{{Compat("css.properties.border-inline-start-color")}}</p>

<h2 id="Voir_aussi">Voir aussi</h2>

<ul>
 <li>Les propriétés physiques correspondantes :
  <ul>
   <li>{{cssxref("border-top-color")}},</li>
   <li>{{cssxref("border-right-color")}},</li>
   <li>{{cssxref("border-bottom-color")}},</li>
   <li>{{cssxref("border-left-color")}}.</li>
  </ul>
 </li>
 <li>{{cssxref("writing-mode")}}, {{cssxref("direction")}}, {{cssxref("text-orientation")}}</li>
</ul>