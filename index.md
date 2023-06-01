---
layout: home
header:
  title: Forest Adventure
  text: >
    Рогейны и спортивное ориентирование для всех!
  action: # action button is optional
    label: Календарь
    url: '#events'


sections:
  - type: call-to-action.html
    section_id: nearestevent
    background_style: bg-info text-white
    title: Рогейн ЁЛКИНО-2
    text: >-
      1 июля, Ёлкино Воскресенского городского округа
    actions:
      - title: Заявка
        url: 'https://orgeo.ru/event/fa2023'
        class: btn-light
      #- title: Результаты
      #  url: '2022/bno/res.html'
      #  class: btn-light

  - type: events.html
    section_id: events
    #background_style: bg-dark
    title: Наши события
    events:
      - title: Рогейн ЁЛКИНО-2
        img: assets/img/2023/index1.jpg
        date: 1 июля 2023 г. (сб)
        place: Воскресенский ГО, у деревни Ёлкино
        format: 6/3 часа бегом и на велосипеде
        text: >-
          Продолжение полюбившегося рогейна, который состоится в рамках спортивного фестиваля.
        actions:
          - title: Инфобюллетень
            url: 'fa2023-info'
            small: true
          - title: Заявка
            url: 'https://orgeo.ru/event/fa2023'
            small: true
        #  - title: Результаты
        #    url: '2023/fa/res.html'
        #    small: true
        #  - title: Карта
        #    url: '2023/fa/map300dpi.png'
        #    small: true

      - title: Большое ночное ориентирование Андрея Зайцева
        img: assets/img/2023/index2.jpg
        date: 11-12 ноября 2023 г.
        text: >-
          18-е традиционные соревнования.
          Место старта пока держим в тайне.
        #actions:
        #  - title: Подробнее
        #    url: 'bno2022/'
        #    small: true

  - type: call-to-action.html
    section_id: historylink
    background_style: bg-primary
    #background_style: bg-info text-white
    title: История
    text: Результаты, карты, фотографии прошедших событий
    actions:
      - title: Подробнее
        url: 'history'
        class: btn-light

#  - type: aside.html
#    section_id: aside
#    title: Free Download at Start Bootstrap!
#    actions:
#      - title: Download Now!
#        url: https://startbootstrap.com/themes/creative/
#        class: btn-light
#
#  - type: members.html
#    section_id: members
#    title: Our Crew!
#    background_style: bg-info text-white
#    members:
#      - title: Christina M. Aponte
#        text: Singer and Songwriter
#        image: assets/img/members/person1.jpg
#        url: '#'
#      - title: Gary D. Stevens
#        text: Bass guitar.
#        image: assets/img/members/person2.jpg
#        url: '#'
#      - title: Devon J. Fletcher
#        text: Lead guitar.
#        image: assets/img/members/person3.jpg
#        url: '#'
#      - title: Todd E. Anderson
#        text: Drums, percussion.
#        image: assets/img/members/person5.jpg
#        url: '#'
#      - title: Daniel T. Riley
#        text: Musician, songwriter, producer.
#        image: assets/img/members/person6.jpg
#        url: '#'
#      - title: Ella P. Walter
#        text: PR.
#        image: assets/img/members/person7.jpg
#        url: '#'

#  - type: timeline.html
#    section_id: timeline
#    title: История
#    background_style: bg-dark text-primary
#    last_image: assets/img/timeline-end.png
#    actions:
#      - image: assets/img/portfolio/thumbnails/1.jpg
#        title: >+
#          2015-2019
#          Владимирский рогейн
#      - image: assets/img/portfolio/thumbnails/2.jpg
#        title: >+
#          2016-...
#          БНО
#        text:

  - type: gallery.html
    section_id: gallery
    background_style: bg-dark
    images:
      - img: gallery/0.jpg
        thumb: gallery/thumb0.jpg
      - img: gallery/1.jpg
        thumb: gallery/thumb1.jpg
      - img: gallery/2.jpg
        thumb: gallery/thumb2.jpg
      - img: gallery/3.jpg
        thumb: gallery/thumb3.jpg
      - img: gallery/4.jpg
        thumb: gallery/thumb4.jpg
      - img: gallery/5.jpg
        thumb: gallery/thumb5.jpg
      - img: gallery/6.jpg
        thumb: gallery/thumb6.jpg
      - img: gallery/7.jpg
        thumb: gallery/thumb7.jpg
      - img: gallery/8.jpg
        thumb: gallery/thumb8.jpg
      - img: gallery/9.jpg
        thumb: gallery/thumb9.jpg
      - img: gallery/10.jpg
        thumb: gallery/thumb10.jpg
      - img: gallery/11.jpg
        thumb: gallery/thumb11.jpg

  - type: paragraph.html
    section_id: about
    title: О нас
    text_style: text-center
    text: >+
      Мы команда **Forest Adventure**.

      Мы проводим Большое ночное ориентирование с 2016 года, а также проводили [Владимирский рогейн](https://vrogaining.ru) с 2015 до 2018 года.

      Автор карт и дистанций, идейный вдохновитель проекта — **Семён Якимов**,
      чемпион России по рогейну 2021, многократный победитель и призёр рогейнов,
      российских и международных приключенческих гонок, навигатор команды Blizzard.

      Мы любим лес, карты и дух соперничества.
      И хотим делится этой любовью с нашими участниками.
      Мы всегда рады видеть на наших стартах старых и новых друзей.

      Присоединяйтесь!

  - type: contact.html
    section_id: contacts
    title: Оставайтесь на связи!
    text: >-
      Новости, фотографии, полезную информацию мы публикуем на наших страницах в социальных сетях.
      Там же вы можете задать любые вопросы, поделиться впечатлениями.
      Или пишите нам на электнонную почту, с радостью ответим!
    actions:
    - title: 'info@forestadventure.ru'
      icon: fa-envelope
      url: mailto:info@forestadventure.ru
    - title: '@forestadventure'
      icon: fa-telegram
      icon_type: fab
      url: 'https://t.me/forestadventure'
    - title: forestadventureru
      icon: fa-vk
      icon_type: fab
      url: 'https://vk.com/forestadventureru'
    - title: '@forest_adventure_ru'
      icon: fa-instagram
      icon_type: fab
      url: 'http://instagram.com/forest_adventure_ru'

  - type: sponsors.html
    section_id: sponsors
    title: Спонсоры и партнёры
    items:
      - name: Veloforma.Net
        url: https://veloforma.net
        img: assets/img/2020/veloforma-logo-200.png
      - name: Arena
        url: https://arenasportfood.ru
        img: assets/img/2021/arena.png
      - name: Правильная подушка
        url: https://www.ozon.ru/brand/proekt-pravilnaya-podushka-100111938/
        img: assets/img/2022/pillow.jpg
      - name: Территория странствий
        url: https://tur-eda.ru
        img: assets/img/2022/terr.png

---
