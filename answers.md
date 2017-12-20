1. var profilePic = document.body.querySelector('img')
   profilePic.src = 'https://static.giantbomb.com/uploads/square_medium/15/155548/2353605-pandaman.png'
1. var body = document.body
   var section = body.querySelector('section')
   var sky = section.querySelector('img')
   sky.src = 'http://cdn.newsapi.com.au/image/v1/fbea7b3a223c746aca3104e2cf942ec6?width=650'

2. var heading = section.querySelector('.highlight')
   heading.innerText = 'Brandon Levy'

3. var employment = section.querySelector('#employment')
   var h3 = employment.querySelector('h3')
   var test = h3.innerHTML
   var new_test = test.replace("Employment", "Test")
   h3.innerHTML = new_test

4. body.style.backgroundColor = 'red'

5. var highlights = body.querySelectorAll('.highlight')
   for(i=0;i<highlights.length;i++){highlights[0].style.color = 'blue'}

6. var h1 = body.querySelectorAll('h1')
   h1.forEach(function(h1){h1.style.fontFamily = 'monospace'})

7. var icons = body.querySelectorAll('.action-container > .action-icon-container')
   icons.forEach(function(icon){icon.querySelector('a').style.backgroundColor = 'red'})

8. body.querySelector('#name').placeholder = "identify yourself"

9. body.querySelector('#message').placeholder = "state your business"

10. body.querySelector('#name').value = "your nemesis"

11. body.querySelector('#email').value = "koalathebear@gmail.com"

12. body.querySelector('#submit').value = "En garde!"

13. body.querySelector('#submit').disabled = true

14. var bio = body.querySelector('.bio-info')
    bio.hidden = true
