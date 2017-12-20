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
   test.replace("Employment", "Test")
   var new_test = test.replace("Employment", "Test")
   h3.innerHTML = new_test

4. body.style.backgroundColor = 'red'
