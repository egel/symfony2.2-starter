TODO: zrobic koniecznie - wiele aplikacji na jednym SF2: http://jolicode.com/blog/multiple-applications-with-symfony2

TODO: zrobieniu do tego skryptu instalacyjnego? sprawdzającego wymagania i wykonującego zdania instalacyjne?

TODO:
Kolejna fajna rzecz, która powinna być w starterze to paczka https://github.com/avalanche123/AvalancheImagineBundle
Ta paczka pozwala w locie przetwarzać zdjęcia, a potem wyrzuca je z cache, nie musisz obrabiaż w entity zdjęć itp. 
Wystarczy tylko w szablonie twig podać coś takiego:
<img src="{{ '/relative/path/to/image.jpg' | apply_filter('thumbnail') }}" />
I robi się sama fotka, jedynie w entity trzeba samemu usuwać cache fotek jak robi się update, ale to już nie jest problemem

By Sławek
EOF TODO

TODO: zainstaluj > https://packagist.org/packages/doctrine/doctrine-fixtures-bundle

TODO: zainstaluj initializr

TODO: cos nie dziala httaccess