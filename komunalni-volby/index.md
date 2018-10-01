---
layout: communal-elections
title: Komunální volby v Opavě
campaignCategoryUid: magistrat2018
candidateListUid: radnice # uid z `_candidates/radnice.md`
---


> Poctivou přípravou, usilovnou a důslednou prací v zastupitelstvech v Praze, v Mariánských Lázních, v Brně, či dalších městech se Piráti postupně vylodili také v zastupitelstvech krajů a úspěšně dopluli do Poslanecké sněmovny Parlamentu České republiky. Ani ve Sněmovně „neusnuli na vavřínech“ a nezahálejí. Plní, co slíbili. Nekážou vodu, aniž by pili víno. Jsou aktivní, zásadoví, věrohodní, spolehliví. O své práci občany informují, občanům naslouchají, pro občany pracují. Takto chceme společně s našimi nestranickými spolukandidáty, aby to fungovalo i v našem městě. Na stejné vlně hodláme vplout do zastupitelstva statutárního města Opavy. Budeme pracovat pro město HOSPODÁRNĚ, OTEVŘENĚ, S ÚCTOU A RESPEKTEM. DRŽÍME KURZ!“

> Hana Brňáková
> lídryně a kandidátka na primátorku

<section class="o-section o-section--spaceBot">
  <div class="o-section-inner">
    <div class="o-section-block">
      <div class="c-BasicPage">
        <div class="c-BasicPage-content">
          {% assign program = site.program | where: "campaignCategoryUid","magistrat2018" | sort: 'order' %}
          <div class="row small-up-3 medium-up-6 large-up-9">
            {% for item in program %}
              <div class="column column-block">
                <a href="{{ item.url | relative_url }}">
                  <img class="program-icon" src="{{ item.img | prepend: 'assets/img/' | relative_url }}" alt="{{item.shortTitle}}" />
                  <center>
                    <h6>{{item.shortTitle}}</h6>
                  </center>
                </a>
              </div>
            {% endfor %}
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
