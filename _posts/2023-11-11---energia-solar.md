---
title: Energia Solar
excerpt: Serviços para projetos fotovoltaicos. Visitas técnicas, treinamento e assessoria.
tags: featured
priority: 0.8
options: minihead
permalink: /solar/
categories:
  - solar
background-image: PV2.jpg
#date/lastmod are optional
date: 2018-10-10 12:24:41 -0300
#lastmod: 2019-04-25 16:54:41 -0300
---
{% include post_picwrap.html pos="left" src="/images/dsp001.jpg" %}

## PROJETOS FOTOVOLTAICOS - GERAÇÃO DISTRIBUÍDA

Com foco no cliente final e em novos empreenderores no ramo de micro e mini geração distribuída oferecemos serviços de treinamento, capacitação, consultoria e assessoria para projetos, instalação e homologação de sistemas de geração fotovoltaica.

### Serviços Principais

{% include post_picwrap.html pos="right" src="/images/solar4.jpg" %}

##### Visitas Técnicas

Para uma avaliação mais precisa do dimensionamento e custo de uma instalação é necessário uma visita técnica, quando são definidos aspectos mecânicos, elétricos e logísticos.

##### Treinamento, capacitação e consultoria

Com a expansão e popularização dos sistemas fotovoltaicos instalados se tornou corriqueiro pequenos empreendedores de outros ramos a se aventurarem nas instalações de sistema de energia solar. 

Fornecemos treinamentos e capacitação para quem quer entrar no ramo de Geração Distribuída, assim como consultoria e assessoria para pequenos empreendedores e clientes.

{% include post_picwrap.html pos="left" src="/images/solar2.jpg" %}

##### Homologação e assessoria.

Contamos com corpo de engenheiros elétricos experientes na aprovação e homologação de projetos junto a todas as concessionárias de energia elétrica da região sul do país. 

Acompanhamos todas as etapas de execução dos projetos com emissão de relatórios fotográficos pontuais, oferecendo maior agilidade e segurança para o seu investimento.



<!--{%
if site.social.linkedin-square %}
<div class="table-wrapper">
  <table class="alt"><tbody><tr><td style="text-align: center;">Visit my
  <a target="_blank" href="{{ site.social.linkedin-square }}">LinkedIn profile</a></td>
  </tr></tbody></table>
</div>{%
endif %}
{%
if site.categories.eolica %}
<div class="table-wrapper">
  <table>
    <tbody>{%
      include fn_groupsort_reverse.html unsorted=site.categories.eolica groupby='priority' sortby='date'
%}{%  for eolica in sorted_list %}
      <tr>
        <td><b><a href="{{ eolica.url | prepend: site.baseurl }}">{{ eolica.title }}</a></b></td>
        <td>{{ eolica.date | date: "%b %Y" }}</td>
        <td>{{ eolica.excerpt | strip_html | truncatewords: 12 }}</td>
        <td>
          {% include techlist.html %}
        </td>
      </tr>{%
      endfor %}
    </tbody>
  </table>
</div>{%
  if site.eolica_in_progress %}
  <div class="works_inprogress">In-progress, more to come.</div>{%
  endif %}{%
endif
%}-->
