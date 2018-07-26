---
layout: home
title: Home
permalink: /
order: 1
cards:
  - title: "La Lazio"
    description: "Here is some more information about this product that is only revealed once clicked on"
    image: "https://upload.wikimedia.org/wikipedia/en/thumb/e/e4/SS_Lazio.svg/1200px-SS_Lazio.svg.png"
    url: "/lazio/"
  - title: "Il Laziale"
    description: "Here is some more information about this product that is only revealed once clicked on"
    image: "https://www.laziochannel.it/wp-content/uploads/2015/08/Giuseppe-Signori.jpg"
    url: "/about/"
  - title: "La Dogana"
    description: "Here is some more information about this product that is only revealed once clicked on"
    image: "http://www.ilsecoloxix.it/rf/Image-lowres_Multimedia/IlSecoloXIXWEB/italia/foto/2012/08/29/jackpot_salaGiochi_13701-F110207184247--U160764327031lP-440x250.jpg"
    url: "/dogana/"
---
<div>
  <div id="img-container">
    <h1 class="header">Benvenuto nel sito del Laziale!</h1>
    <h6>Qui per raccontare tutto di uno dei personaggi piu' interessanti del nuovo millennio...</h6>
  </div>
  <div id="text-container" class="container">
    <div>
      <h1 class="header center">Perche'?</h1>
      <h6 class="header col s12 bold">
        Questo sito nasce dall'esigenza dei ragazzi di saint di raccontare al mondo le storie del 
        <b>Laziale</b>. In questo sito abbiamo voluto raccogliere il meglio del laziale, comprendendo
        le sue storie piu' famose, i suoi aforismi e molto altro.
        Eu aliqua velit ipsum reprehenderit laboris. Non quis est ea eiusmod id et dolor sit dolore nostrud ex quis. Enim quis cupidatat sunt labore mollit dolor mollit incididunt. Nulla ut amet non eu deserunt adipisicing dolore labore.
        Eu aliqua velit ipsum reprehenderit laboris. Non quis est ea eiusmod id et dolor sit dolore nostrud ex quis. Enim quis cupidatat sunt labore mollit dolor mollit incididunt. Nulla ut amet non eu deserunt adipisicing dolore labore.
        Questo sito nasce dall'esigenza dei ragazzi di saint di raccontare al mondo le storie del 
        <b>Laziale</b>. In questo sito abbiamo voluto raccogliere il meglio del laziale, comprendendo
        le sue storie piu' famose, i suoi aforismi e molto altro.
        Eu aliqua velit ipsum reprehenderit laboris. Non quis est ea eiusmod id et dolor sit dolore nostrud ex quis. Enim quis cupidatat sunt labore mollit dolor mollit incididunt. Nulla ut amet non eu deserunt adipisicing dolore labore.
        Eu aliqua velit ipsum reprehenderit laboris. Non quis est ea eiusmod id et dolor sit dolore nostrud ex quis. Enim quis cupidatat sunt labore mollit dolor mollit incididunt. Nulla ut amet non eu deserunt adipisicing dolore labore.
      </h6>
    </div>
  </div>
  <div>
    <div id="video-container">
      <iframe
        width="740"
        height="400"
        src="https://www.youtube.com/embed/MYLWKG4VXX0"
        frameborder="0"
        allow="autoplay; encrypted-media"
        allowfullscreen>
      </iframe>
    </div>
  </div>
  <div id="card-section">
    <div class="container row">
      {% for card in page.cards %}
        <div class="col s12 m4">
            <div class="card small">
              <div class="card-image waves-effect waves-block waves-light">
                <img class="activator" src="{{ card.image }}">
              </div>
              <div class="card-content">
                <span class="card-title activator grey-text text-darken-4">
                  {{ card.title }}<i class="material-icons right">more_vert</i>
                </span>
                <p><a href="{{ card.url }}">Leggi di piu'</a></p>
              </div>
              <div class="card-reveal">
                <span class="card-title grey-text text-darken-4">
                  Card Title<i class="material-icons right">close</i>
                </span>
                <p>
                  {{ card.title }}
                </p>
              </div>
            </div>
        </div>
      {% endfor %}
    </div>
  </div>
</div>