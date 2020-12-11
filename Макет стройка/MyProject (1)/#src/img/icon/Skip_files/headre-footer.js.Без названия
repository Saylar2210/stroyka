$(function () {  // Загрузка DOM JQUERY
   /*-------------------BURGER(JQUERY)----------------------------*/
   $('.header__burger').click(function () {
      $('.header-menu, .header__burger, .header-menu__list').toggleClass('active')
      $('body').toggleClass('lock')
   })
   /*-------------------BURGER----------------------------*/

   /*-------------------FOOTER-MOBILE-TAB(JQUERY)----------------------------*/
   function windowSize() {
      if ($(window).width() > '770') {
         $('.pages-footer__list').slideDown();
         $('.menu-footer__list').slideDown();
         $('.contacts-footer__contacts').slideDown();
      }
      else {
         $('.pages-footer__list').slideUp()
         $('.menu-footer__list').slideUp()
         $('.contacts-footer__contacts').slideUp()
      }
   }
   $('.pages-footer__label').click(function () {
      if ($(window).width() <= '770') {
         $('.pages-footer__list').slideToggle(500)
         $('.menu-footer__list').slideUp(500)
         $('.contacts-footer__contacts').slideUp(500)
      }

   })
   $('.menu-footer__label').click(function () {
      if ($(window).width() <= '770') {
         $('.menu-footer__list').slideToggle(500)
         $('.contacts-footer__contacts').slideUp(500)
         $('.pages-footer__list').slideUp(500)
      }
   })
   $('.contacts-footer__label').click(function () {
      if ($(window).width() <= '770') {
         $('.contacts-footer__contacts').slideToggle(500)
         $('.pages-footer__list').slideUp(500)
         $('.menu-footer__list').slideUp(500)
      }
   })
   $(window).on('load resize', windowSize);
   /*-------------------FOOTER-MOBILE-TAB----------------------------*/

})