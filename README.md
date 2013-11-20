Starter-Zurb Foundation-D6
======================

Starter pour D6 utilisant SaSS,Compass,Zurb Foundation 4

Installer Zurb Foundation 4

    run gem install zurb-foundation
    Add require "zurb-foundation" to your config.rb file
    cd path/to/your-project/sass-folder
    run compass install -r zurb-foundation foundation

Grille sémantique
------------------
<pre>
#masthead { @include grid-row; @include panel;
  & > hgroup { @include grid-column(4); }
  & > section { @include grid-column(8); }
}
</pre>

Réglages par défaut
-------------------

<pre>
$row-width: em-calc(1000);
$column-gutter: em-calc(30);
$total-columns: 12 !default;
</pre>