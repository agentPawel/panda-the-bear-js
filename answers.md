1. a) $('.profile-image').attr('src', 'https://placebear.com/400/403')
   b) $('#left-image').children('img').attr('src', 'https://placebear.com/325/225')

2. $('h1.highlight').text('Pawel Parafianwowicz')

3. $('#employment h3').html()
   var i = $('#employment h3').html()
   var res = i.replace("Employment", "Jobs")
   $('#employment h3').html(res)

4. $('#time-travel').parent().remove()

5. $('body').css('background-colour', 'red')

6. $('.highlight').css('colour', 'blue')

7. $('.h1').css('font-family', 'monospace')

8. $('.action-icon-bg').css('background-color', 'red')

9. $('.contact-info#name').attr('placeholder', 'Identify Yourself')

10. $('#message').attr('placeholder', 'state your business')

11. $('#name').attr('placeholder', "Your nemesis")

12. $('#email').attr('placeholder', 'koalathebear@gmail.com')

13. $('#submit').attr('value', 'En Garde')

Adding Elements to DOM

1. $('#right-image img').clone().appendTo('form')

2. for (i = 0; i < 10; i++) { $('#right-image img').clone().appendTo('form'); }
